# Deep Learning for Music (DL4M)
The role of this curated list is to gather scientific articles that use deep learning approaches applied to music.
The list is currently under construction but feel free to contribute to the missing fields and to add other resources.

## Table of contents
- [DL4M Articles](#dl4m-articles)
- [Code without articles](#code-without-articles)
- [Additional resources](#additional-resources)
- [How To Contribute](#how-to-contribute)
- [Contributors](#contributors)

## DL4M Articles 
| Article | Code |
|---------------------|-------------------------|
| [Convolutional recurrent neural networks for music classification](http://ieeexplore.ieee.org/abstract/document/7952585/) | [GitHub](https://github.com/keunwoochoi/icassp_2017) |
| [An evaluation of Convolutional Neural Networks for music classification using spectrograms](http://www.inf.ufpr.br/lesoliveira/download/ASOC2017.pdf) | No |
| [Deep Convolutional Neural Networks for Predominant Instrument Recognition in Polyphonic Music](http://dl.acm.org/citation.cfm?id=3068697) | No |
| [End-to-End Musical Key Estimation Using a Convolutional Neural Network](https://arxiv.org/pdf/1706.02921.pdf) | |
| [Multi-Level and Multi-Scale Feature Aggregation Using Sample-level Deep Convolutional Neural Networks for Music Classification](https://arxiv.org/pdf/1706.06810.pdf) | |
| [Melody extraction and detection through LSTM-RNN with harmonic sum loss](http://ieeexplore.ieee.org/abstract/document/7952660/) | |
| [Timbre Analysis of Music Audio Signals with Convolutional Neural Networks](https://arxiv.org/pdf/1703.06697.pdf) | [GitHub](https://github.com/jordipons/EUSIPCO2017) |
| [Designing efficient architectures for modeling temporal features with convolutional neural networks](http://ieeexplore.ieee.org/document/7952601/) | [GitHub](https://github.com/jordipons/ICASSP2017) |
| [Music Feature Maps with Convolutional Neural Networks for Music Genre Classification](https://www.micc.unifi.it/cbmi2017/session/poster-and-demo-session/) | No |
| [Extending Temporal Feature Integration for Semantic Audio Analysis](http://www.aes.org/e-lib/browse.cfm?elib=18682) | No |
| [A study on LSTM networks for polyphonic music sequence modelling](https://qmro.qmul.ac.uk/xmlui/handle/123456789/24946) | [Website](http://www.eecs.qmul.ac.uk/~ay304/code/ismir17) |
| [An Efficient Approach for Segmentation, Feature Extraction and Classification of Audio Signals ](http://file.scirp.org/pdf/CS_2016042615054817.pdf) | No |
| [Towards Playlist Generation Algorithms Using RNNs Trained on Within-Track Transitions](https://arxiv.org/pdf/1606.02096.pdf) | No |
| [Automatic tagging using deep convolutional neural networks](https://arxiv.org/pdf/1606.00298.pdf) | No |
| [Robust Downbeat Tracking Using an Ensemble of Convolutional Networks](http://ieeexplore.ieee.org/abstract/document/7728057/) | |
| [A deep bidirectional long short-term memory based multi-scale approach for music dynamic emotion prediction](http://ieeexplore.ieee.org/document/7471734/) | |
| [Event Localization in Music Auto-tagging](http://mac.citi.sinica.edu.tw/~yang/pub/liu16mm.pdf) | [GitHub](https://github.com/ciaua/clip2frame) |
| [Deep convolutional networks on the pitch spiral for musical instrument recognition](https://github.com/lostanlen/ismir2016/blob/master/paper/lostanlen_ismir2016.pdf) | |
| [Robust Audio Event Recognition with 1-Max Pooling Convolutional Neural Networks](https://arxiv.org/pdf/1604.06338.pdf) | No |
| [Note onset detection in musical signals via neural–network–based multi–odf fusion](https://www.degruyter.com/downloadpdf/j/amcs.2016.26.issue-1/amcs-2016-0014/amcs-2016-0014.pdf) | No |
| [Convolutional neural network for robust pitch determination](http://www.mirlab.org/conference_papers/International_Conference/ICASSP%202016/pdfs/0000579.pdf) | |
| [Deep Convolutional Neural Networks and Data Augmentation for Acoustic Event Detection](https://arxiv.org/pdf/1604.07160.pdf) | No |
| [Unsupervised Feature Learning Based on Deep Models for Environmental Audio Tagging](https://arxiv.org/pdf/1607.03681.pdf) | |
| [Singing voice detection with deep recurrent neural networks](https://hal-imt.archives-ouvertes.fr/hal-01110035/document) | |
| [A software framework for musical data augmentation](https://bmcfee.github.io/papers/ismir2015_augmentation.pdf) | |
| [Musical instrument sound classification with deep convolutional neural network using feature fusion approach](https://arxiv.org/ftp/arxiv/papers/1512/1512.07370.pdf) | |
| [Deep Karaoke: Extracting Vocals from Musical Mixtures Using a Convolutional Deep Neural Network](https://link.springer.com/chapter/10.1007/978-3-319-22482-4_50) | |
| [The Munich LSTM-RNN Approach to the MediaEval 2014 “Emotion in Music” Task](https://pdfs.semanticscholar.org/8a24/c5131d5a28165f719697028c34b00e6d3f60.pdf) | |
| [End-to-end learning for music audio](http://ieeexplore.ieee.org/abstract/document/6854950/) | No |
| [Deep learning for music genre classification](https://courses.engr.illinois.edu/ece544na/fa2014/Tao_Feng.pdf) | No |
| [Improved musical onset detection with convolutional neural networks](http://www.mirlab.org/conference_papers/International_Conference/ICASSP%202014/papers/p7029-schluter.pdf) | No |
| [A hybrid recurrent neural network for music transcription](https://arxiv.org/pdf/1411.1623.pdf) | |
| [Unsupervised feature learning for audio classification using convolutional deep belief networks](http://papers.nips.cc/paper/3674-unsupervised-feature-learning-for-audio-classification-using-convolutional-deep-belief-networks.pdf) | No |

## Code without articles
- [Audio Classifier in Keras using Convolutional Neural Network](https://github.com/drscotthawley/audio-classifier-keras-cnn)

## Additional resources
- [dl4m.bib](dl4m.bib) - the corresponding bibliography.
- [dl4m.csv](dl4m.csv) - more details about each article:
	- Author
	- Year
	- Article name
	- PDF link
	- Source code link
	- Source code reproducible
	- Architecture
	- Number of layers
	- Task
	- Dataset
	- Computation time
	- Hardware
	- Data augmentation
	- Additional notes

## How To Contribute
1. Fork the repo.
2. Add one line per article in [dl4m.csv](dl4m.csv) with every column correctly filled.
3. Submit your pull request and that's it! (Note: the table in the ReadMe is automatically generated thanks to a python script.)

## Contributors
- [Vincent Lostanlen](https://github.com/lostanlen)
- [Keunwoo Choi](https://github.com/keunwoochoi)
