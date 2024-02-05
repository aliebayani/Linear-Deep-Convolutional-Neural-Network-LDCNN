# Introduction
<p align = "justify"> 
  The Electrocardiogram (ECG) is an essential and widely used instrument for diagnosing cardiovascular diseases. It involves the recording of electrical signals produced by the heart using electrodes, which depict the activity of cardiac muscles during both contraction and relaxation phases. ECG plays a crucial role in detecting irregular cardiac activity, myocardial infarctions, and various other cardiac conditions. 
</p>

<p align = "justify">
In our research, we developed a novel <strong>one-dimensional deep neural network technique called LDCNN</strong> to identify arrhythmias from ECG signals.
</p>

<p>
  In addition to the CNN model, we've implemented the various machine learning techniques for the datasets.
</p>

# Dataset

<p>
  The original datasets used are <a href=https://physionet.org/content/mitdb/1.0.0/>MIT-BIH Arrhythmia</a> and <a href=https://www.physionet.org/content/ptbdb/1.0.0/>PTB Diagnostic ECG</a> that were preprocessed.
</p>

<!-- <p align = "justify">
  Also for the PTB Diagnostic ECG Dataset, we've used an <a href=https://www.kaggle.com/datasets/shayanfazeli/heartbeat>annotated dataset</a> of heartbeats to see if we can train a model to detect abnormal heartbeats.
</p> -->

<table style="width:100%">
  <caption>An overview of the types of heartbeats we used in the MIT-BIH Arrhythmia Dataset.</caption>
  <tr>
    <th>Classes</th>
    <th>Description</th>
    <th>Count</th>
  </tr>
  <tr>
    <td>N</td>
    <td>Normal beat</td>
    <td>75011</td>
  </tr>
  <tr>
    <td>L</td>
    <td>Left bundle branch block beat</td>
    <td>8071</td>
  </tr>
  <tr>
    <td>R</td>
    <td>Right bundle branch block beat</td>
    <td>7255</td>
  </tr>
  <tr>
    <td>A</td>
    <td>Atrial premature beat</td>
    <td>7129</td>
  </tr>
  <tr>
    <td>V</td>
    <td>Premature ventricular contraction</td>
    <td>2546</td>
  </tr>
</table>
<br>
<table style="width:100%">
  <caption>An overview of the types of heartbeats we used in the PTB Diagnostic ECG Dataset.</caption>
  <tr>
    <th>Classes</th>
    <th>Description</th>
    <th>Count</th>
  </tr>
  <tr>
    <td>normal</td>
    <td>Normal beat, Healthy controls</td>
    <td>4046</td>
  </tr>
  <tr>
    <td>abnormal</td>
    <td>Myocardial infarction, Cardiomyopathy/Heart failure, Bundle branch block, Dysrhythmia, Myocardial hypertrophy, Valvular heart disease, Myocarditis, Miscellaneous</td>
    <td>10506</td>
  </tr>
</table>

<br>
<br>
Ali Bayani
