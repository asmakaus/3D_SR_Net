### 3D_SR_Net
##### 3D Shallow Residual Network

Knowledge of the underlying anatomy of the left atrium can promote improved diagnostic protocols and clinical interventions. Hence, an automatic segmentation of the left atrium on magnetic resonance imaging (MRI) can support diagnosis, treatment and surgery planning of heart. However, due to the small size of left atrium with respect to the whole MRI volume, accurate segmentation of left atrium is challenging. Most of the existing deep learning approaches are based on cropping or cascading networks.


In this work, we present a novel deep learning architecture for the segmentation of left atrium from MRI volume which incorporates the residual learning based encoder-decoder network. We introduce a loss function and parameter adjustments to deal with the issue of class imbalance and unavailability of large medical imaging dataset. To facilitate the high quality segmentation, we present a three-dimensional multi-scale residual learning based architecture that maintains coarse and fine level features throughout the network. A considerable improvement can be acheived in segmentation performance with fewer parameters compared to the state-of-the-art approaches, thus potentially supporting cardiac diagnosis and surgery without adding any extensive pre-processing of input volumes or any post-processing on the base network's output.


Major developement in this repository is based on NiftyNet which is a TensorFlow-based open-source convolutional neural networks (CNN) platform for research in medical image analysis. Installation instructions and working guidelines can be obtained from [NiftyNet](https://pypi.org/project/NiftyNet) website


After installation, copy the provided files in respective directories e.g.

##### *  network/3d_sr_net.py
##### *  engine/application_factory.py _(replace)


configuration file for training can be found in the main directory. 








#### References


E. Gibson*, W. Li*, C. Sudre, L. Fidon, D. I. Shakir, G. Wang, Z. Eaton-Rosen, R. Gray, T. Doel, Y. Hu, T. Whyntie, P. Nachev, M. Modat, D. C. Barratt, S. Ourselin, M. J. Cardoso† and T. Vercauteren† (2018) NiftyNet: a deep-learning platform for medical imaging, Computer Methods and Programs in Biomedicine. DOI: 10.1016/j.cmpb.2018.01.025

