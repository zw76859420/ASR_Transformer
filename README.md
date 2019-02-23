# ASR_Transformer
A Pytorch implementation of Speech Transformer, an End-to-End Automatic Speech Recognition with Transformer Network, Which directly converts acoustic features to character sequence using a signal neural network.<br>
[Reference link](https://github.com/kaituoxu/Speech-Transformer, '悬停显示')<br>
### First Step - Data
  Aishell-01 <br>
  Data can be acquired from here [aishell-01 data](http://www.openslr.org/33/, '悬停显示').<br>
### Necessary library
  `kaldi` <br>
  `pytorch`<br>
### Next - Data preprocess and feature Extration
  We will use kaldi toolkit for data preprocess and feature extration;<br>
  This jod will be finished in one week, because we have a lot of things to do.(20190221-20190228)<br>
### Operation process
 (1) pip install -r requirements.txt<br>
 (2) cd tools -> make KALDI=/home/zhangwei/kaldi<br>
 (3) cd egs/aishell -> bash run.sh (Note: You must use `bash run.sh` rather than `sh run.sh` or `./run.sh`)<br>
### Possible problems
  
### Related Papers
  `Attention Is All You Need`<br>
  `SPEECH-TRANSFORMER  A NO-RECURRENCE SEQUENCE-TO-SEQUENCE MODEL`<br>
  `Syllable-Based Sequence-to-Sequence Speech Recognition with the`<br>
