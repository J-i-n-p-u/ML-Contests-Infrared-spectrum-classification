# ML-Contests-Infrared-spectrum-classification
Classify solid samples according to their diffuse reflectance infrared spectra

The Near Infrared Spectroscopy Branch of the China Instrument Society holds the [data modeling contest](https://www.instrument.com.cn/news/20220725/625062.shtml). The organizer provides [a set of near-infrared spectral data](https://img1.17img.cn/17img/files/202207/attachment/d3666a14-5a77-4d56-b183-49d07239349f.rar) from the actual application scenario. Different data preprocessing technologies (e.g. PCA, normalization) and machine learning models (AutoML) were tried for the classification problem. [ExtraTreesClassifier](https://scikit-learn.org/stable/modules/generated/sklearn.ensemble.ExtraTreesClassifier.html) was used as the final model. Our work won an [excellent award](https://www.instrument.com.cn/news/20220824/629168.shtml) in this competition.

## Dataset introduction:
| Left-Aligned  | Center Aligned  | Right Aligned |
| :------------ |:---------------:| -----:|
| col 3 is      | some wordy text | $1600 |
| col 2 is      | centered        |   $12 |
| zebra stripes | are neat        |    $1 |
