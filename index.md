# Tensor Computation for Data Processing

<img src="https://github.com/yipengliu/ijcai2022tutorial/blob/gh-pages/Yipeng_Liu.JPG" alt="raw" width="100"/>

drawing
## Description


&emsp;&emsp;Many classical data processing methods rely on representation and computation in the form of vectors and matrices, where multi-dimensional data are unfolded into matrix for processing. However, the multi-linear structure would be lost in such vectorization or matricization, which leads to sub-optimal performance in processing. In fact, a natural representation for multi-dimensional data is tensor. The tensor computation based processing methods can avoid multi-linear data structure loss in classical matrix based counterparts. The related advances in applied mathematics allow us to move from classical matrix based methods to tensor based methods for many applications, such as machine learning, signal processing, neuroscience, communication, psychometric, chemometrics, biometric, quantum physics, quantum chemistry, etc. As typical kinds of multi-dimensional data, multimedia data could be more efficiently and effectively processed by tensor computations based data processing techniques.


&emsp;&emsp;This tutorial will first provide a basic coverage of tensor notations, preliminary operations, main tensor decompositions and their properties. Based on them, a series of tensor processing methods are presented, as the multi-linear extensions of classical sparse learning, missing component analysis, principal component analysis, subspace cluster, linear regression, support vector machine, deep neural network, etc. The experimental results for a number of data processing applications are given, such as image reconstruction, image quality enhancement, multimedia data fusion, background extraction, weather forecasting, pose estimation, source separation in speech, etc. Finally, some acceleration strategies are discussed for some more possible applications.


## Tutorial Outline
### 1.	Introduction to tensor
####   &emsp;a)	Tensor Computation (20 minutes)
####   &emsp;b)	Tensor Decomposition (30 minutes)


&emsp;&emsp;As a generalization of array with three or more indices, a higher-order tensor has a series of new notations and operations for computation, such as matricization, tensor inner product, tensor outer product, mode-n product of tensor, tensor product, etc. Based on these tensor operations, the main tensor decompositions, as the higher-order extensions of the matrix singular value decomposition, are presented, such as CANDECOMP/PARAFAC (CP) decomposition, Tucker decomposition, block term decomposition, tensor singular value decomposition (t-SVD), tensor train, tensor tree, tensor ring, etc. we will compare these decompositions, and discuss both their advantages and disadvantages.


### 2.	Tensor for Multimedia Signal Processing 
#### &emsp;a)	Sparse Learning (15 minutes)
#### &emsp;b)	Missing Component Analysis (15 minutes)
#### &emsp;c)	Coupled Tensor Analysis (10 minutes)
#### &emsp;d)	Principal Component Analysis (15 minutes)
#### &emsp;e)	Tensor Subspace Cluster (10 minutes)
#### &emsp;f)	Tensor Regression (15 minutes) 
#### &emsp;g)	Tensor Hyperplane for Classification (10 minutes)
#### &emsp;h)	Tensor Neural Networks (15 minutes)

&emsp;&emsp;This section covers all the popular tensor processing techniques based on different multi-linear structures, ranging from sparse tensor, tensor dictionary learning, low rank tensor completion, coupled tensor, robust tensor principal component analysis, tensor subspace cluster, non-negative tensor component analysis, tensor regression, support tensor machine, tensor neural network, and their applications in image reconstruction, denoising, superresolution, background extraction, multi-view image clustering, weather forecasting, human pose capture, blind source separation in speech, etc. 


### 3.	Selected Discussion
#### &emsp;a)	Efficient Tensor Computations (15 minutes)

&emsp;&emsp;In this section, recent results on main strategies to improve computation performance will be briefly discussed, such as random tensor subsampling, online tensor learning, distributed tensor processing. These advanced topics and in-depth discussions may enhance the participants’ learning experience and stimulate their own R&D work in the relevant areas.


### 4.Potential audience

&emsp;&emsp;It is intended for researchers, developers, engineers, students and people interested in gaining an overall understanding of Tensor methods and its applications in data processing.

&emsp;&emsp;Prerequisite knowledge includes: a basic understanding of linear algebra, matrix computation, optimization. Preliminary knowledge of machine learning can be helpful.


### 5.Objectives

&emsp;&emsp;Tenor is a natural representation for multi-dimensional data, and tensor computation based data processing can avoid multi-linear data structure loss in classical matrix based data processing methods. 

&emsp;&emsp;The recent advances in tensor computations bring the improvement of a number of classical data processing techniques by their tensor extensions. As kinds of typical multi-way data, multimedia related applications can be effectively benefited. This tutorial will provide a systematic introduction to recent advances in tensor data processing, such as tensor regression, tensor dictionary learning, low rank tensor completion, tensor principal component analysis, tensor subspace clustering, support tensor machine, tensor neural network, etc. These techniques can be used to image reconstruction, image quality enhancement, background extraction, multi-view image clustering, weather forecasting, pose estimation, speech source separation, image and speech classification, etc.

&emsp;&emsp;This tutorial serves to introduce expert non-specialists to an AI subarea, motivate and explain a topic of emerging importance for AI.

### 6.Ethical concerns

&emsp;&emsp;There is no ethical concern.


