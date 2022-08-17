# <center> STC</center>
<center>Powei Chen</center><br>
<center>City, Country</center> 
<br>

## Abstract
<div style="text-align: justify"> STC </div>

<br>

## Model Architecture
<table border="0">
  <tbody>
    <tr>
      <td><img src="figs/Proposed_FW.pdf" alt="Overall Architecture"></td>
    </tr>
  </tbody>
</table>

<br>


## Audio Samples
<div style="text-align: justify"> All samples are synthesized with the pretrained vocoders, where the breathy singing is synthesized by the HiFi-GAN vocoder and the others are synthesized by the MelGAN vocoder.</div>

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
      <td><audio controls="" preload="auto">
            <source src="target_waves/Sample_Breathy.wav"></audio></td>
    </tr>
    <tr>
      <td>Vocal Fry</td>
      <td><audio controls="" preload="auto">
            <source src="target_waves/Sample_VocalFry.wav"></audio></td>
    </tr>
    <tr>
      <td>Vibrato</td>
      <td><audio controls="" preload="auto">
            <source src="target_waves/Sample_Vibrato.wav"></audio></td>
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
      <td>1. (HiFiGAN vocoder)</td>
      <td><audio controls="" preload="auto">
            <source src="source_waves/HIFINS.wav"></audio></td>
    </tr>
    <tr>
      <td>1. (MelGAN vocoder)</td>
      <td><audio controls="" preload="auto">
            <source src="source_waves/MELNS.wav"></audio></td>
    </tr>
    <tr>
      <td>2. (HiFiGAN vocoder)</td>
      <td><audio controls="" preload="auto">
            <source src="source_waves/HIFINS2.wav"></audio></td>
    </tr>
    <tr>
      <td>2. (MelGAN vocoder)</td>
      <td><audio controls="" preload="auto">
            <source src="source_waves/MELNS2.wav"></audio></td>
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
      <th>Sample</th>
      <th>Source Input</th>
      <th>Baseline</th>
      <th>Mw/o</th>
      <th>Mw/</th>
    </tr>
  </thead>
  <tbody>
   <tr>
      <td>1.</td>
      <td><audio controls="" preload="auto"><source src="sample/Po3_B_GT.wav"></audio></td>
      <td><audio controls="" preload="auto"><source src="sample/Po3_B_base.wav"></audio></td>
      <td><audio controls="" preload="auto"><source src="sample/Po3_B_RGC.wav"></audio></td>
      <td><audio controls="" preload="auto"><source src="sample/Po3_B_RTL.wav"></audio></td>
    </tr>
    <tr>
      <td>2.</td>
      <td><audio controls="" preload="auto"><source src="sample/Po1_B_GT.wav"></audio></td>
      <td><audio controls="" preload="auto"><source src="sample/Po1_B_base.wav"></audio></td>
      <td><audio controls="" preload="auto"><source src="sample/Po1_B_RGC.wav"></audio></td>
      <td><audio controls="" preload="auto"><source src="sample/Po1_B_RTL.wav"></audio></td>
    </tr>
    <tr>
      <td>3.</td>
      <td><audio controls="" preload="auto"><source src="sample/Po4_B_GT.wav"></audio></td>
      <td><audio controls="" preload="auto"><source src="sample/Po4_B_base.wav"></audio></td>
      <td><audio controls="" preload="auto"><source src="sample/Po4_B_RGC.wav"></audio></td>
      <td><audio controls="" preload="auto"><source src="sample/Po4_B_RTL.wav"></audio></td>
    </tr>
    <tr>
      <td>4.</td>
      <td><audio controls="" preload="auto"><source src="sample/Po2_B_GT.wav"></audio></td>
      <td><audio controls="" preload="auto"><source src="sample/Po2_B_base.wav"></audio></td>
      <td><audio controls="" preload="auto"><source src="sample/Po2_B_RGC.wav"></audio></td>
      <td><audio controls="" preload="auto"><source src="sample/Po2_B_RTL.wav"></audio></td>
    </tr>
    <tr>
      <td>5.</td>
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
      <th>Sample</th>
      <th>Source Input</th>
      <th>Baseline</th>
      <th>Mw/o</th>
      <th>Mw/</th>
    </tr>
  </thead>
  <tbody>
   <tr>
      <td>1.</td>
      <td><audio controls="" preload="auto"><source src="sample/Po3_VF_GT.wav"></audio></td>
      <td><audio controls="" preload="auto"><source src="sample/Po3_VF_base.wav"></audio></td>
      <td><audio controls="" preload="auto"><source src="sample/Po3_VF_RGC.wav"></audio></td>
      <td><audio controls="" preload="auto"><source src="sample/Po3_VF_RTL.wav"></audio></td>
    </tr>
   <tr>
      <td>2.</td>
      <td><audio controls="" preload="auto"><source src="sample/Po2_VF_GT.wav"></audio></td>
      <td><audio controls="" preload="auto"><source src="sample/Po2_VF_base.wav"></audio></td>
      <td><audio controls="" preload="auto"><source src="sample/Po2_VF_RGC.wav"></audio></td>
      <td><audio controls="" preload="auto"><source src="sample/Po2_VF_RTL.wav"></audio></td>
    </tr>
   <tr>
      <td>3.</td>
      <td><audio controls="" preload="auto"><source src="sample/Po4_VF_GT.wav"></audio></td>
      <td><audio controls="" preload="auto"><source src="sample/Po4_VF_base.wav"></audio></td>
      <td><audio controls="" preload="auto"><source src="sample/Po4_VF_RGC.wav"></audio></td>
      <td><audio controls="" preload="auto"><source src="sample/Po4_VF_RTL.wav"></audio></td>
    </tr>
   <tr>
      <td>4.</td>
      <td><audio controls="" preload="auto"><source src="sample/Po1_VF_GT.wav"></audio></td>
      <td><audio controls="" preload="auto"><source src="sample/Po1_VF_base.wav"></audio></td>
      <td><audio controls="" preload="auto"><source src="sample/Po1_VF_RGC.wav"></audio></td>
      <td><audio controls="" preload="auto"><source src="sample/Po1_VF_RTL.wav"></audio></td>
    </tr>
   <tr>
      <td>5.</td>
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
      <th>Sample</th>
      <th>Source Input</th>
      <th>Baseline</th>
      <th>Mw/o</th>
      <th>Mw/</th>
    </tr>
  </thead>
  <tbody>
   <tr>
      <td>1.</td>
      <td><audio controls="" preload="auto"><source src="sample/Po3_VB_GT.wav"></audio></td>
      <td><audio controls="" preload="auto"><source src="sample/Po3_VB_base.wav"></audio></td>
      <td><audio controls="" preload="auto"><source src="sample/Po3_VB_RGC.wav"></audio></td>
      <td><audio controls="" preload="auto"><source src="sample/Po3_VB_RTL.wav"></audio></td>
    </tr>
    <tr>
      <td>2.</td>
      <td><audio controls="" preload="auto"><source src="sample/Po1_VB_GT.wav"></audio></td>
      <td><audio controls="" preload="auto"><source src="sample/Po1_VB_base.wav"></audio></td>
      <td><audio controls="" preload="auto"><source src="sample/Po1_VB_RGC.wav"></audio></td>
      <td><audio controls="" preload="auto"><source src="sample/Po1_VB_RTL.wav"></audio></td>
    </tr>
    <tr>
      <td>3.</td>
      <td><audio controls="" preload="auto"><source src="sample/Po4_VB_GT.wav"></audio></td>
      <td><audio controls="" preload="auto"><source src="sample/Po4_VB_base.wav"></audio></td>
      <td><audio controls="" preload="auto"><source src="sample/Po4_VB_RGC.wav"></audio></td>
      <td><audio controls="" preload="auto"><source src="sample/Po4_VB_RTL.wav"></audio></td>
    </tr>
    <tr>
      <td>4.</td>
      <td><audio controls="" preload="auto"><source src="sample/Po2_VB_GT.wav"></audio></td>
      <td><audio controls="" preload="auto"><source src="sample/Po2_VB_base.wav"></audio></td>
      <td><audio controls="" preload="auto"><source src="sample/Po2_VB_RGC.wav"></audio></td>
      <td><audio controls="" preload="auto"><source src="sample/Po2_VB_RTL.wav"></audio></td>
    </tr>
    <tr>
      <td>5.</td>
      <td><audio controls="" preload="auto"><source src="sample/Po1_VB_GT2.wav"></audio></td>
      <td><audio controls="" preload="auto"><source src="sample/Po1_VB_base2.wav"></audio></td>
      <td><audio controls="" preload="auto"><source src="sample/Po1_VB_RGC2.wav"></audio></td>
      <td><audio controls="" preload="auto"><source src="sample/Po1_VB_RTL2.wav"></audio></td>
    </tr>
  </tbody>
</table>

