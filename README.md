# Rain event detection with CMLs and CNNs (an example) [![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/jpolz/cnn_cml_wet-dry_example/master)


Using 1D convolutional neural networks for rain event detection in commercial microwave link data is a concept described in (link to publication-coming soon). The purpose of this repository is to give a full description of the model setup using the Keras API with a Tensorflow back-end and a small example data set to illustrate our results.


## Table of Contents
- [Model](#Model)
- [Training](#Training)
- [Example data](#Example data set)
- [Software](#Software)
- [Further reading](#Further reading)
  - [Publications](#Publications)
  - [Projects](#Projects)


## Model

![alt text](https://raw.githubusercontent.com/jpolz/cnn_cml_wet-dry_example/master/model_arch_v2.png "1D-CNN architecture")

## Training



## Example data set
Since it the full data set, that was used in (link to publication-coming soon) is not publicly available in its full extent, we provide a small [example data set](https://github.com/jpolz/cnn_cml_wet-dry_example/blob/master/paper_example_40cmls_raw.h5). It contains raw data from 40 CMLs with modified CML locations. The time series contains two weeks in September 2018. The pre-processing of the raw data, the classification through the CNN and a comparison to a reference method is contained in [this notebook](https://github.com/jpolz/cnn_cml_wet-dry_example/blob/master/CNN_for_CML_example_nb.ipynb).



## Software
The full python programming environment needed to set up the analysis can be installed from the  [environment.yml](https://github.com/jpolz/cnn_cml_wet-dry_example/blob/master/environment.yml) file. The most important toolboxes we used are:
* [Keras](https://github.com/keras-team/keras)
* [Tensorflow](https://github.com/tensorflow/tensorflow)

## Further reading

### Papers
* [Real-time CML data acquisition](https://www.atmos-meas-tech.net/9/991/2016/amt-9-991-2016-discussion.html)
* [Analysis of one year of data (in review)](https://www.hydrol-earth-syst-sci-discuss.net/hess-2019-423/)
* [Hydrological application of CML derived rainfall maps in alpine regions](https://opus.bibliothek.uni-augsburg.de/opus4/frontdoor/deliver/index/docId/38395/file/0107.pdf)
* Rain event detection methods
  * Rain event detection with CMLs and CNNs (soon)
  * 1
  * 2
  * 3

### Projects
* [DFG-RealPEP](https://www2.meteo.uni-bonn.de/realpep/doku.php)
* [DFG-IMAP](https://www.imk-ifu.kit.edu/projects_2209.php)
* [HGF-Digital Earth](https://www.digitalearth-hgf.de/de)
* [BMBF-HoWa innovativ](https://www.howa-innovativ.sachsen.de/index.html)
