# PyTorch Image Classifier

## Updates

As for many users request, I released a new version of standard pytorch image classification example at here: http://codes.strangeai.pro/aicodes_detail.html?id=30

It works better with **pytorch 1.0** support. It contains those features which are really useful to write a standard AI application or bild an image classifier:
<ul>
  <li> Loading Data using DataLoaders </li>
  <li> Network or model is less coupled with training and testing code (less couple). </li>
  <li> catch keyboard interrupt and resume training. </li>
  </ul>

## Less Than 200 Line Train Codes and 25 Epochs, Got 98% Accuracy!

In this repo, I managed classify images into 2 Categories which are ants and
bees, but it's also very straightforward to train on more classes images.
The amazing thing is, using PyTorch, we can use less than 200 line code to get
a very highy accuracy of classificatio on images!

## Usage

To using this repo, some things you should to know:
<ul>
 <li> Compatible both of CPU and GPU, this code can automatically train on CPU or GPU </li>
 <li> Models trained on GPU can also predict on CPU using predict.py . </li>
<li> First run please run `bash download_datasets.sh` to obtain datasets. <.li>
<li> Model will be save after epochs. </li>
 <li> Image Size can be set in `global_config.py`. </li>

## Future Work

This network could be used for other image dataset and by using transfer learning, data augmentation and fine tunning , you can get best results.

## Copyright

This repo implement by Jin Fagang, and ofcourse PyTorch authors.
if you have any question, you can find me on wechat: `jintianiloveu`
