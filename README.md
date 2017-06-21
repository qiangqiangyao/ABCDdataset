# ABCD dataset

This material is a description of ABCD (AIST Building Change Detection) dataset.
This dataset is a new labeled dataset, specially geared toward constructing and evaluating damage detection systems to identify whether buildings have been washed-away by tsunami.

## Format
Each datum in this dataset is a pair of pre- and post-tsunami aerial image patches, and encompasses a target building at the center of the patch. These pairs were cropped from aerial images taken before and after the Tohoku earthquake. The pixel resolution of patches is 40 cm.

The below figure shows the representative samples in the dataset, where eight pairs are shown for "washed-away" class (left column) and "surviving" class (right column).

![patches_](https://user-images.githubusercontent.com/13417696/27384118-b5539e1e-56c8-11e7-9c0c-7d06b899763f.png){:width="100px" style="display:block;margin-left:auto;margin-right:auto;"}


See our paper for further details.
Please cite the following paper when publishing results that use this dataset


Aito Fujita, Ken Sakurada, Tomoyuki Imaizumi, Riho Ito, Shuhei Hikosaka, Ryosuke Nakamura, "Damage Detection from Aerial Images
via Convolutional Neural Networks," IAPR International Conference on Machine Vision Applications (MVA), 2017.


----

There are XXX images for each of the following classes:
- washed-away
- surviving

Each image measures XXXxXXX pixels.

The images were manually extracted from large images from the USGS National Map Urban Area Imagery collection for various urban areas around the country. The pixel resolution of this public domain imagery is 1 foot.



Aito Fujita  
National Institute of Advanced Industrial Science and Technology (AIST), Japan  
Email: fujita.713@aist.go.jp  

This material is based on results obtained from a project commissioned by the New Energy and Industrial Technology Development Organization (NEDO).
