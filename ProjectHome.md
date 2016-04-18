# 1. Summary #

We freely distribute a software package <a href='http://mumoc.googlecode.com/files/Mumoc.tar.gz'>“Multiple Model Observer Calculator”(MUMOC)</a> as a tool to calculate the task based signal to noise-ratio (SNR) with different computational model observers evaluating signal detectability on noisy backgrounds. The attached <a href='http://mumoc.googlecode.com/files/User_Manual_v1.0.8.pdf'>user manual</a> shows the installation, the input/output data format and the basic usages. We also provided several datasets for testing purpose. Section 5 in the user manual explains how to use those datasets.

The task-based SNR is a figure-of-merit for the analysis of image quality. In this package, we provide implementations of the non-prewhitening model observer, the Hotelling model observer, a simplified Hotelling model observer for uncorrelated datasets, and a channelized Hotelling model observer with two families of channels --- Laguerre-Gauss and Gabor channels. The software enables users to calculate SNR values not only for the entire image, but also for a region of interest (ROI), which could be smaller than the size of the input images. After the ROI size is determined, the software will calculate a SNR map by scanning the ROI window throughout the entire image. The SNR values in the map can be displayed in an image or listed in a dialog popup. The software also allows the user to calculate and display the mean signal-present image, the mean signal-absent image and the covariance matrix. It can save or load the inverse covariance matrix and generate different channels from the two channel families with different parameters. In the user manual, we also describe a preliminary validation study.


MUMOC was developed at FDA/CDRH/Office of Science and Engineering Laboratories/Division of Imaging and Applied Mathematics. Since this software is developed solely for research purposes, it is not guaranteed to be bug-free. You can download the source code, the user manual, the video clip and some test datasets from the download page in this website.  The license is described in Section 1.1. The source code is free to download for use or modification.

An interface is demonstrated as follows:

http://mumoc.googlecode.com/files/Mumoc.JPG

## 1.1 Disclaimer ##
This software and documentation (the "Software") were developed at the Food and Drug Administration (FDA) by employees of the Federal Government in the course of their official duties. Pursuant to Title 17, Section 105 of the United States Code, this work is not subject to copyright protection and is in the public domain. Permission is hereby granted, free of charge, to any person obtaining a copy of the Software, to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, or sell copies of the Software or derivatives, and to permit persons to whom the Software is furnished to do so. FDA assumes no responsibility whatsoever for use by other parties of the Software, its source code, documentation or compiled executables, and makes no guarantees, expressed or implied, about its quality, reliability, or any other characteristic.   Further, use of this code in no way implies endorsement by the FDA or confers any advantage in regulatory decisions.  Although this software can be redistributed and/or modified freely, we ask that any derivative works bear some notice that they are derived from it, and any modified versions bear some notice that they have been modified.

<a href='Hidden comment: 

If you have any questions, please contact the author at songxiang.gu@gmail.com. If you publish papers with using this software, we would appreciate (but not necessary) if you would cite the work as follows:

*S. Gu and et al., TBD*

'></a>
