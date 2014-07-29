# Scaling Up Fast: Real-time Image Processing and Analytics using Spark
__[The slides](https://rawgit.com/4Quant/spark-summit-2014-presentation/master/ssPresentation.html)__, __[The video](https://www.youtube.com/watch?v=I6qmEcGNgDo&feature=youtu.be)__
## Kevin Mader (ETH Zurich)
Imaging experiments involving complex specimens like full-animals, vascular structures in brain, or cellular material rheology are difficult or impossible to accurately characterize by eye and thus require computationally intensive algorithms to extract meaningful quantitative information from them. With improvements in flux, detector efficiency, and reconstruction algorithms, the rate at which image data is produced using Synchrotron-based X-ray Tomographic Microscopy is staggering. At the TOMCAT beamline of the Swiss Light Source, this rate reaches 8GB per second of image data[1], higher than even multinational companies with dedicated IT staff like Facebook or Instagram usually handle. We have developed a scalable framework based on Apache Spark and the Resilient Distributed Datasets proposed in [2] for parallel, distributed, real-time image processing and quantitative analysis. The cluster-/cloud-based evaluation tool performs filtering, segmentation and shape analysis enabling data exploration and hypothesis testing over millions of structures with the time frame of an experiment. The tools have been tested with clusters containing thousands of machines and images containing more than 100 billion voxels. The flexible infrastructure offers a full spectrum of shape, distribution, and connectivity metrics for cellular materials and networks and can be adapted to a wide variety of new studies requiring high sample counts ranging from long-term dynamics and evolution experiments to investigations of drug-gene interactions. Finally we examine the potential for real-time approximate analysis as compared with region of interest selection and down-sampling as a superior approach for speeding up post-processing.

Kevin Mader is a lecturer in the X-ray Microscopy Group within the Department for Information Technology and Electrical Engineering at ETH Zurich. His research focuses on turning big hairy 3D images into simple, robust, reproducible numbers without resorting to black boxes or magic. In particular, as part of several collaborations, he is currently working on automatically segmenting full animal zebrafish images, characterizing rheology in 3D flows, and measuring viral infection dynamics in cell lines.

### Learn more at 
- 4Quant: From Images to Statistics - http://www.4quant.com
- X-Ray Imaging Group at ETH Zurich - http://bit.ly/1gD8wKb
- Quantitative Big Imaging Course at ETH Zurich - http://bit.ly/1kj9mnq


