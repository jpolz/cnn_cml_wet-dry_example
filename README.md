# Page in progress...
# Rain event detection with CMLs and CNNs (an example) [![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/jpolz/cnn_cml_wet-dry_example/master)


![alt text](https://raw.githubusercontent.com/jpolz/cnn_cml_wet-dry_example/master/cml_banner.png "A typical CML antenna")


Using 1D convolutional neural networks for rain event detection in commercial microwave link (CML) data is a concept described in (link to publication-coming soon). The purpose of this repository is to give a full description of the model setup using the Keras API with a Tensorflow back-end and a small example data set to illustrate our results. CMLs can be used to derive rainfall information by exploiting the close to linear relationship between the attenuation caused by rainfall and the path averaged rain rate along the link path.


## Model

The python implementation of the model is shown in [this notebook](https://github.com/jpolz/cnn_cml_wet-dry_example/blob/master/CNN_for_CML_example_nb.ipynb). More details soon...

## Training
We train our model using 4 months of data from 400 randomly chosen CMLs distributed over entire Germany. Afterwards the model is validated using different months of data from all 3904 available CMLs. The number of samples is 70,000 for training and more than $ 4x10^{6} $ for validation.


## Example data set
Since the full data set, that was used in (link to publication-coming soon) is not publicly available in its full extent, we provide a small [example data set](https://github.com/jpolz/cnn_cml_wet-dry_example/blob/master/paper_example_40cmls_raw.h5). It contains raw data from 40 CMLs with modified CML locations. The time series contains two weeks in September 2018. The pre-processing of the raw data, the classification through the CNN and a comparison to a reference method is contained in [this notebook](https://github.com/jpolz/cnn_cml_wet-dry_example/blob/master/CNN_for_CML_example_nb.ipynb).


## Software
The full python programming environment needed to set up the analysis can be installed from the  [environment.yml](https://github.com/jpolz/cnn_cml_wet-dry_example/blob/master/environment.yml) file. The most important toolboxes we used are:
* [Keras](https://github.com/keras-team/keras)
* [Tensorflow](https://github.com/tensorflow/tensorflow)


## Further reading

### Publications
* [Real-time CML data acquisition](https://www.atmos-meas-tech.net/9/991/2016/amt-9-991-2016-discussion.html)
* [Analysis of one year of data (in review)](https://www.hydrol-earth-syst-sci-discuss.net/hess-2019-423/)
* [Hydrological application of CML derived rainfall maps in alpine regions](https://opus.bibliothek.uni-augsburg.de/opus4/frontdoor/deliver/index/docId/38395/file/0107.pdf)
* Rain event detection methods
  * Rain event detection with CMLs and CNNs (soon)
  * 2
  * 3

  ### Projects
  * [DFG-RealPEP](https://www2.meteo.uni-bonn.de/realpep/doku.php)
  * [DFG-IMAP](https://www.imk-ifu.kit.edu/projects_2209.php)
  * [HGF-Digital Earth](https://www.digitalearth-hgf.de/de)
  * [BMBF-HoWa innovativ](https://www.howa-innovativ.sachsen.de/index.html)

  ### People
  * [Julius Polz](https://github.com/jpolz)
  * [Max Graf](https://github.com/maxmargraf)
  * [Christian Chwala](https://github.com/cchwala)
