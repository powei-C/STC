# <center>A FEW SHOT LEARNING OF SINGING TECHNIQUE CONVERSION BASED ON CYCLE CONSISTENCY GENERATIVE ADVERSARIAL NETWORKS</center>
<center>Po-Wei Chen, Von-Wen Soo</center><br>
<center>NTHU, Taiwan, R.O.C</center> 
<br>

## Abstract
<div style="text-align: justify"> Submit to ICASSP 2023. Under Review

 </div>

<br>

## Model Architecture
<table border="0">
  <tbody>
    <tr>
      <td><img src="figs/Proposed_FW.pdf" alt="Details of the framework are presented in our manuscript."></td>
    </tr>
  </tbody>
</table>

<br>


## Audio Samples
<div style="text-align: justify"> All samples are synthesized with the pretrained vocoders, where the breathy singing is synthesized by the HiFi-GAN vocoder (denoted as HF) and the others are synthesized by the MelGAN vocoder. (denoted as MEL)</div>

**Target Singing Technique**
<div style="text-align: justify"> Samples of singing tehchniques.</div>
---
<table>
  <thead>
    <tr>
      <th>Target</th>
      <th>Samples</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>Breathy</td>
      <td><audio controls="" preload="auto"><source src="target_wavs/Sample_Breathy.wav"></audio></td>
    </tr>
    <tr>
      <td>Vocal Fry</td>
      <td><audio controls="" preload="auto"><source src="target_wavs/Sample_VocalFry.wav"></audio></td>
    </tr>
    <tr>
      <td>Vibrato</td>
      <td><audio controls="" preload="auto"><source src="target_wavs/Sample_Vibrato.wav"></audio></td>
    </tr>
  </tbody>
</table>
---

**Source Natural Singing**
<div style="text-align: justify"> Samples of natural singing.</div>
<table>
  <thead>
    <tr>
      <th>Source</th>
      <th>Samples</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>1. HF</td>
      <td><audio controls="" preload="auto"><source src="source_wavs/HIFINS.wav"></audio></td>
    </tr>
    <tr>
      <td>1. MEL</td>
      <td><audio controls="" preload="auto"><source src="source_wavs/MELNS.wav"></audio></td>
    </tr>
    <tr>
      <td>2. HF</td>
      <td><audio controls="" preload="auto"><source src="source_wavs/HIFINS2.wav"></audio></td>
    </tr>
    <tr>
      <td>2. MEL</td>
      <td><audio controls="" preload="auto"><source src="source_wavs/MELNS2.wav"></audio></td>
    </tr>

  </tbody>
</table>
---

<br>

## Comparison with Different Frameworks

**Target: Breathy**


<table align="center">
  <thead>
    <tr>
      <th>          Lyrics          </th>
      <th>Source Input</th>
      <th>Baseline</th>
      <th>Mw/o</th>
      <th>Mw/</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td><ruby>天上的星星笑地上的人<rt>tiān shàng de xīng xīng xiào dì shàng de rén</rt></ruby>   </td>
      <td><audio controls="" preload="auto"><source src="sample/Po3_B_GT.wav"></audio></td>
      <td><audio controls="" preload="auto"><source src="sample/Po3_B_base.wav"></audio></td>
      <td><audio controls="" preload="auto"><source src="sample/Po3_B_RGC.wav"></audio></td>
      <td><audio controls="" preload="auto"><source src="sample/Po3_B_RTL.wav"></audio></td>
    </tr>
    <tr>
      <td><ruby>原來心疼我我那時候不懂<rt>yuán lái xīn téng wǒ wǒ nà shí hòu bù dǒng</rt></ruby></td>
      <td><audio controls="" preload="auto"><source src="sample/Po1_B_GT.wav"></audio></td>
      <td><audio controls="" preload="auto"><source src="sample/Po1_B_base.wav"></audio></td>
      <td><audio controls="" preload="auto"><source src="sample/Po1_B_RGC.wav"></audio></td>
      <td><audio controls="" preload="auto"><source src="sample/Po1_B_RTL.wav"></audio></td>
    </tr>
    <tr>
      <td><ruby>想到就心酸<rt>xiǎng dào jiù xīn suān</rt></ruby></td>
      <td><audio controls="" preload="auto"><source src="sample/Po4_B_GT.wav"></audio></td>
      <td><audio controls="" preload="auto"><source src="sample/Po4_B_base.wav"></audio></td>
      <td><audio controls="" preload="auto"><source src="sample/Po4_B_RGC.wav"></audio></td>
      <td><audio controls="" preload="auto"><source src="sample/Po4_B_RTL.wav"></audio></td>
    </tr>
    <tr>
      <td><ruby>到後來才發現愛你是一種習慣<rt>dào hòu lái cái fā xiàn ài nǐ shì yī zhǒng xí guàn</rt></ruby></td>
      <td><audio controls="" preload="auto"><source src="sample/Po2_B_GT.wav"></audio></td>
      <td><audio controls="" preload="auto"><source src="sample/Po2_B_base.wav"></audio></td>
      <td><audio controls="" preload="auto"><source src="sample/Po2_B_RGC.wav"></audio></td>
      <td><audio controls="" preload="auto"><source src="sample/Po2_B_RTL.wav"></audio></td>
    </tr>
    <tr>
      <td><ruby>可是我真的不夠勇敢<rt>kě shì wǒ zhēn de bù gòu yǒng gǎn</rt></ruby></td>
      <td><audio controls="" preload="auto"><source src="sample/Po2_B_GT2.wav"></audio></td>
      <td><audio controls="" preload="auto"><source src="sample/Po2_B_base2.wav"></audio></td>
      <td><audio controls="" preload="auto"><source src="sample/Po2_B_RGC2.wav"></audio></td>
      <td><audio controls="" preload="auto"><source src="sample/Po2_B_RTL2.wav"></audio></td>
    </tr>
  </tbody>
</table>
---


**Target: Vocal Fry**


<table align="center">
  <thead>
    <tr>
      <th>Lyrics</th>
      <th>Source Input</th>
      <th>Baseline</th>
      <th>Mw/o</th>
      <th>Mw/</th>
    </tr>
  </thead>
  <tbody>
   <tr>
      <td width="250px"><ruby>怎麼去擁有一道彩虹<rt>zěn me qù yōng yǒu yī dào cǎi hóng</rt></ruby></td>
      <td><audio controls="" preload="auto"><source src="sample/Po3_VF_GT.wav"></audio></td>
      <td><audio controls="" preload="auto"><source src="sample/Po3_VF_base.wav"></audio></td>
      <td><audio controls="" preload="auto"><source src="sample/Po3_VF_RGC.wav"></audio></td>
      <td><audio controls="" preload="auto"><source src="sample/Po3_VF_RTL.wav"></audio></td>
    </tr>
   <tr>
      <td><ruby>是一種習慣<rt>shì yī zhǒng xí guàn</rt></ruby></td>
      <td><audio controls="" preload="auto"><source src="sample/Po2_VF_GT.wav"></audio></td>
      <td><audio controls="" preload="auto"><source src="sample/Po2_VF_base.wav"></audio></td>
      <td><audio controls="" preload="auto"><source src="sample/Po2_VF_RGC.wav"></audio></td>
      <td><audio controls="" preload="auto"><source src="sample/Po2_VF_RTL.wav"></audio></td>
    </tr>
   <tr>
      <td><ruby>一夏天的風<rt>yī xià tiān de fēng</rt></ruby></td>
      <td><audio controls="" preload="auto"><source src="sample/Po4_VF_GT.wav"></audio></td>
      <td><audio controls="" preload="auto"><source src="sample/Po4_VF_base.wav"></audio></td>
      <td><audio controls="" preload="auto"><source src="sample/Po4_VF_RGC.wav"></audio></td>
      <td><audio controls="" preload="auto"><source src="sample/Po4_VF_RTL.wav"></audio></td>
    </tr>
   <tr>
      <td><ruby>我卻錯手毀掉<rt>wǒ què cuò shǒu huǐ diào</rt></ruby></td>
      <td><audio controls="" preload="auto"><source src="sample/Po1_VF_GT.wav"></audio></td>
      <td><audio controls="" preload="auto"><source src="sample/Po1_VF_base.wav"></audio></td>
      <td><audio controls="" preload="auto"><source src="sample/Po1_VF_RGC.wav"></audio></td>
      <td><audio controls="" preload="auto"><source src="sample/Po1_VF_RTL.wav"></audio></td>
    </tr>
   <tr>
      <td><ruby>一夏天的風<rt>yī xià tiān de fēng</rt></ruby></td>
      <td><audio controls="" preload="auto"><source src="sample/Po3_VF_GT2.wav"></audio></td>
      <td><audio controls="" preload="auto"><source src="sample/Po3_VF_base2.wav"></audio></td>
      <td><audio controls="" preload="auto"><source src="sample/Po3_VF_RGC2.wav"></audio></td>
      <td><audio controls="" preload="auto"><source src="sample/Po3_VF_RTL2.wav"></audio></td>
    </tr>
  </tbody>
</table>
---


**Target: Vibrato**


<table align="center">
  <thead>
    <tr>
      <th>Lyrics</th>
      <th>Source Input</th>
      <th>Baseline</th>
      <th>Mw/o</th>
      <th>Mw/</th>
    </tr>
  </thead>
  <tbody>
   <tr>
      <td width="350"><ruby>不能覺得足夠<rt>bù néng jué dé zú gòu</rt></ruby></td>
      <td><audio controls="" preload="auto"><source src="sample/Po3_VB_GT.wav"></audio></td>
      <td><audio controls="" preload="auto"><source src="sample/Po3_VB_base.wav"></audio></td>
      <td><audio controls="" preload="auto"><source src="sample/Po3_VB_RGC.wav"></audio></td>
      <td><audio controls="" preload="auto"><source src="sample/Po3_VB_RTL.wav"></audio></td>
    </tr>
    <tr>
      <td><ruby>假如我年少有為不<rt>jiǎ rú wǒ nián shǎo yǒu wéi bù</rt></ruby></td>
      <td><audio controls="" preload="auto"><source src="sample/Po1_VB_GT.wav"></audio></td>
      <td><audio controls="" preload="auto"><source src="sample/Po1_VB_base.wav"></audio></td>
      <td><audio controls="" preload="auto"><source src="sample/Po1_VB_RGC.wav"></audio></td>
      <td><audio controls="" preload="auto"><source src="sample/Po1_VB_RTL.wav"></audio></td>
    </tr>
    <tr>
      <td><ruby>怎麼去收藏<rt>zěn me qù shōu cáng</rt></ruby></td>
      <td><audio controls="" preload="auto"><source src="sample/Po4_VB_GT.wav"></audio></td>
      <td><audio controls="" preload="auto"><source src="sample/Po4_VB_base.wav"></audio></td>
      <td><audio controls="" preload="auto"><source src="sample/Po4_VB_RGC.wav"></audio></td>
      <td><audio controls="" preload="auto"><source src="sample/Po4_VB_RTL.wav"></audio></td>
    </tr>
    <tr>
      <td><ruby>該是甚麼模樣<rt>gāi shì shèn me mó yàng</rt></ruby></td>
      <td><audio controls="" preload="auto"><source src="sample/Po2_VB_GT.wav"></audio></td>
      <td><audio controls="" preload="auto"><source src="sample/Po2_VB_base.wav"></audio></td>
      <td><audio controls="" preload="auto"><source src="sample/Po2_VB_RGC.wav"></audio></td>
      <td><audio controls="" preload="auto"><source src="sample/Po2_VB_RTL.wav"></audio></td>
    </tr>
    <tr>
      <td><ruby>原來心疼我我那時候不懂<rt>yuán lái xīn téng wǒ wǒ nà shí hòu bù dǒng</rt></ruby></td>
      <td><audio controls="" preload="auto"><source src="sample/Po1_VB_GT2.wav"></audio></td>
      <td><audio controls="" preload="auto"><source src="sample/Po1_VB_base2.wav"></audio></td>
      <td><audio controls="" preload="auto"><source src="sample/Po1_VB_RGC2.wav"></audio></td>
      <td><audio controls="" preload="auto"><source src="sample/Po1_VB_RTL2.wav"></audio></td>
    </tr>
  </tbody>
</table>

