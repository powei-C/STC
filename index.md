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
<div style="text-align: justify"> All samples are synthesized with the pretrained vocoders.</div>

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
            <source src="target_waves/breathy.wav"></audio></td>
    </tr>
    <tr>
      <td>Vocal Fry</td>
      <td><audio controls="" preload="auto">
            <source src="target_waves/vocal_fry.wav"></audio></td>
    </tr>
    <tr>
      <td>Vibrato</td>
      <td><audio controls="" preload="auto">
            <source src="target_waves/vibrato.wav"></audio></td>
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
      <td>1.</td>
      <td><audio controls="" preload="auto">
            <source src="source_waves/natural_singing.wav"></audio></td>
    </tr>
    <tr>
      <td>2.</td>
      <td><audio controls="" preload="auto">
            <source src="source_waves/natural_singing.wav"></audio></td>
    </tr>
    <tr>
      <td>3.</td>
      <td><audio controls="" preload="auto">
            <source src="source_waves/natural_singing.wav"></audio></td>
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
      <td><audio controls="" preload="auto"><source src="sample/a.wav"></audio></td>
      <td><audio controls="" preload="auto"><source src="sample/a.wav"></audio></td>
      <td><audio controls="" preload="auto"><source src="sample/a.wav"></audio></td>
      <td><audio controls="" preload="auto"><source src="sample/a.wav"></audio></td>
    </tr>
    <tr>
      <td>3.</td>
      <td><audio controls="" preload="auto"><source src="sample/a.wav"></audio></td>
      <td><audio controls="" preload="auto"><source src="sample/a.wav"></audio></td>
      <td><audio controls="" preload="auto"><source src="sample/a.wav"></audio></td>
      <td><audio controls="" preload="auto"><source src="sample/a.wav"></audio></td>
    </tr>
    <tr>
      <td>4.</td>
      <td><audio controls="" preload="auto"><source src="sample/a.wav"></audio></td>
      <td><audio controls="" preload="auto"><source src="sample/a.wav"></audio></td>
      <td><audio controls="" preload="auto"><source src="sample/a.wav"></audio></td>
      <td><audio controls="" preload="auto"><source src="sample/a.wav"></audio></td>
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
      <td><audio controls="" preload="auto"><source src="sample/a.wav"></audio></td>
      <td><audio controls="" preload="auto"><source src="sample/a.wav"></audio></td>
      <td><audio controls="" preload="auto"><source src="sample/a.wav"></audio></td>
      <td><audio controls="" preload="auto"><source src="sample/a.wav"></audio></td>
    </tr>
    <tr>
      <td>2.</td>
      <td><audio controls="" preload="auto"><source src="sample/a.wav"></audio></td>
      <td><audio controls="" preload="auto"><source src="sample/a.wav"></audio></td>
      <td><audio controls="" preload="auto"><source src="sample/a.wav"></audio></td>
      <td><audio controls="" preload="auto"><source src="sample/a.wav"></audio></td>
    </tr>
    <tr>
      <td>3.</td>
      <td><audio controls="" preload="auto"><source src="sample/a.wav"></audio></td>
      <td><audio controls="" preload="auto"><source src="sample/a.wav"></audio></td>
      <td><audio controls="" preload="auto"><source src="sample/a.wav"></audio></td>
      <td><audio controls="" preload="auto"><source src="sample/a.wav"></audio></td>
    </tr>
    <tr>
      <td>4.</td>
      <td><audio controls="" preload="auto"><source src="sample/a.wav"></audio></td>
      <td><audio controls="" preload="auto"><source src="sample/a.wav"></audio></td>
      <td><audio controls="" preload="auto"><source src="sample/a.wav"></audio></td>
      <td><audio controls="" preload="auto"><source src="sample/a.wav"></audio></td>
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
      <td><audio controls="" preload="auto"><source src="sample/a.wav"></audio></td>
      <td><audio controls="" preload="auto"><source src="sample/a.wav"></audio></td>
      <td><audio controls="" preload="auto"><source src="sample/a.wav"></audio></td>
      <td><audio controls="" preload="auto"><source src="sample/a.wav"></audio></td>
    </tr>
    <tr>
      <td>2.</td>
      <td><audio controls="" preload="auto"><source src="sample/a.wav"></audio></td>
      <td><audio controls="" preload="auto"><source src="sample/a.wav"></audio></td>
      <td><audio controls="" preload="auto"><source src="sample/a.wav"></audio></td>
      <td><audio controls="" preload="auto"><source src="sample/a.wav"></audio></td>
    </tr>
    <tr>
      <td>3.</td>
      <td><audio controls="" preload="auto"><source src="sample/a.wav"></audio></td>
      <td><audio controls="" preload="auto"><source src="sample/a.wav"></audio></td>
      <td><audio controls="" preload="auto"><source src="sample/a.wav"></audio></td>
      <td><audio controls="" preload="auto"><source src="sample/a.wav"></audio></td>
    </tr>
    <tr>
      <td>4.</td>
      <td><audio controls="" preload="auto"><source src="sample/a.wav"></audio></td>
      <td><audio controls="" preload="auto"><source src="sample/a.wav"></audio></td>
      <td><audio controls="" preload="auto"><source src="sample/a.wav"></audio></td>
      <td><audio controls="" preload="auto"><source src="sample/a.wav"></audio></td>
    </tr>
  </tbody>
</table>

