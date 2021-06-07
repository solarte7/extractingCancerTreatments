<h2> Extracting Cancer Treatments from clinical notes written in Spanish</h2>
This repository contains a neural model trained to extract cancer treatments from clinical notes written in Spanish. The model is based on a Bidirectional Long Short Memory (BiLSTM) neural net with a Conditional Random Field (CRF) layer. <br>

This model perform Named Entity Recognition (NER) using an annotated corpus from clinical notes of lung cancer patients. <br> <br>

Next figure shows an example of  annotated sentences with cancer treatments:
<center> <img src="img/treatments.png" width="700" height="400"> </center>
<br> 

The proposed approach was implemented using Python 3.7, TensorFlow and Keras using the following hyper-parameters configuration: learning rate of 0.001, dropout set as 0.5, the number of epochs is set to  50, the BiLSTM hidden size is 300, and the batch size is 512.
<br>
<H3>Repository Files</H3>
<br>
This repository contains the next directories:

<ul>
    <li><strong>BILSTM model:</strong>   This directory contains an implementation of the  BiLSTM-CRF model. This code is use to train the model.  </li> 
    <li><strong>Trained:</strong> This directory contains a trained BILSTM-CRF (saved) model used to an instance to perform NER. To test the model you must open and run the file load_BILSTM.ipybn. This code requires the next libraries to be installed: Python 3.7, TensorFlow, and Keras </li>    
         
</ul>
<br>
Most information please send an email to: oswaldo.solartep@alumnos.upm.es
