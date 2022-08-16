<head>
<link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/katex@0.10.2/dist/katex.min.css" integrity="sha384-yFRtMMDnQtDRO8rLpMIKrtPCD5jdktao2TV19YiZYWMDkUR5GQZR/NOVTdquEx1j" crossorigin="anonymous">
<script defer src="https://cdn.jsdelivr.net/npm/katex@0.10.2/dist/katex.min.js" integrity="sha384-9Nhn55MVVN0/4OFx7EE5kpFBPsEMZxKTCnA+4fqDmg12eCTqGi6+BB2LjY8brQxJ" crossorigin="anonymous"></script>
<script defer src="https://cdn.jsdelivr.net/npm/katex@0.10.2/dist/contrib/auto-render.min.js" integrity="sha384-kWPLUVMOks5AQFrykwIup5lo0m3iMkkHrD0uJ4H5cjeGihAutqP0yW0J6dpFiVkI" crossorigin="anonymous" onload="renderMathInElement(document.body);"></script>
<style>
.katex-display > .katex {
  display: inline-block;
  white-space: nowrap;
  max-width: 100%;
  overflow-x: scroll;
  text-align: initial;
}
.katex {
  font: normal 1.21em KaTeX_Main, Times New Roman, serif;
  line-height: 1.2;
  white-space: normal;
  text-indent: 0;
}
</style>
</head>

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
<div style="text-align: justify"> Samples of training data for each singing tehchnique.</div>
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
<div style="text-align: justify"> Samples of training data for natural singing.</div>
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

**Target:aaaaa Breathy**


<table align="center">
  <thead>
    <tr>
      <th>Sample</th>
      <th>Source Input</th>
      <th><img src="https://render.githubusercontent.com/render/math?math=Base"></th>
      <th><img src="https://render.githubusercontent.com/render/math?math=M_A{wo}"></th>
      <th><img src="https://render.githubusercontent.com/render/math?math=M_{w}"></th>
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


**Target: Vocal Fry**


<table align="center">
  <thead>
    <tr>
      <th>Sample</th>
      <th>Source Input</th>
      <th>$Base$</th>
      <th>$M_{w/o}$</th>
      <th>$M_{w/}$</th>
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
      <th>$Base$</th>
      <th>$M_{w/o}$</th>
      <th>$M_{w/}$</th>
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

