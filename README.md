Download Link: https://assignmentchef.com/product/solved-cs6300-mini-project-2-speech-technology
<br>
<strong>You need to do the following task​</strong>:

<ol>

 <li>Isolated Digit Recognition using Discrete HMMs (​<a href="https://drive.google.com/a/smail.iitm.ac.in/file/d/0B3q03NswT20sZjIzSUxyWjZsbXc">code)</a>. Use the given features also​ extract your own features and compare the results.</li>

 <li>Use the HMMs trained in task 1 to recognize continuous digits. You need to concatenate the HMMs trained in task 1 to recognize continuous digits. Use only the given features.</li>

</ol>

<strong>Datasets​</strong>:

Digit dataset:  This dataset consists of spoken utterances.  The MFCC feature files and the original .wav files given.

Data: ​<a href="https://drive.google.com/drive/folders/160xRWNVhQTbaHdrW6aemY0efD7MZNgfw?usp=sharing">download here</a>​<a href="https://drive.google.com/drive/folders/160xRWNVhQTbaHdrW6aemY0efD7MZNgfw?usp=sharing">,</a> Group Mapping: ​<a href="https://drive.google.com/file/d/1kvi_6IuybLu1uwEikuyKd-_mIRXoxzVt/view?usp=sharing">Download here</a>

Continues digits dataset:

<ul>

 <li>Download development data from ​<a href="https://drive.google.com/drive/folders/1FTHe8RV3jkY2BTwRUW_7iTKbnOj-_APC?usp=sharing">here </a>​and test data from ​<a href="https://drive.google.com/drive/folders/1ZNUY7VVYHGeNPD4hozK73NN1rxIS6ZQQ?usp=sharing">here</a><a href="https://drive.google.com/drive/folders/1ZNUY7VVYHGeNPD4hozK73NN1rxIS6ZQQ?usp=sharing">.</a>​</li>

 <li>The data contains directories with the group numbers.</li>

 <li>Each directory contains MFCC features from utterances of multiple digits</li>

</ul>

(corresponding to the isolated digits assigned to your batch).

<ul>

 <li>The set of digits uttered are given below: symbol – uttered word 1 – one 2 – two 3 – three 4 – four 5 – five 6 – six 7 – seven 8 – eight 9 – nine z – zero o – o</li>

 <li>In development data, the file name represents spoken digits. Eg. In file 534.mfcc, the digits spoken are five three four.</li>

 <li>Test data consists of 5 unlabeled sequences (blind data). Provide the possible sequence of digits obtained in the report.</li>

</ul>

<strong>Feature File Format​</strong>:

<ul>

 <li>The data given are the MFCC features of speech audio.</li>

 <li>Structure of MFCC file: The first line of the MFCC file contains two space-separated integers. First integer N​C​ – The dimension of the feature vector (The number of MFC coefficients) Second integer N​F​ – The number of frames, the .wav file is divided into.</li>

 <li>The next NF rows contain the MFCC features of dimension NC. Each row corresponds to a feature vector in the sequence.  Please note that NF varies with the example.</li>

</ul>

<strong>Guidelines​</strong>:

<ol>

 <li>You need to plot ROC, DET and confusion matrices for task 1.</li>

 <li>You can include graphs and tables for your results.</li>

</ol>


