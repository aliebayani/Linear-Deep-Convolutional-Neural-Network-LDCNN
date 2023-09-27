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

<p align = "justify">
  Also for the PTB Diagnostic ECG Dataset, we've used an <a href=https://www.kaggle.com/datasets/shayanfazeli/heartbeat>annotated dataset</a> of heartbeats already preprocessed by the authors of <a href=https://doi.org/10.1109/ICHI.2018.00092>this paper</a> to see if we can train a model to detect abnormal heartbeats.
</p>

<style>
table, th, td {
  border: 1px solid black;
  border-collapse: collapse;
}
th, td {
  padding: 5px;
  text-align: left;
}
</style>
</head>
<body>

<h2>Table Caption</h2>
<p>To add a caption to a table, use the caption tag.</p>

<table style="width:100%">
  <caption>Monthly savings</caption>
  <tr>
    <th>Month</th>
    <th>Savings</th>
  </tr>
  <tr>
    <td>January</td>
    <td>$100</td>
  </tr>
  <tr>
    <td>February</td>
    <td>$50</td>
  </tr>
</table>

# Results
