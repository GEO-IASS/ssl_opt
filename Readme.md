# Semi Supervised Learning optimized 
This matlab code provide a computational optimized version of the original version developed and distributed  [Fergus 2009](http://cs.nyu.edu/~fergus/). [Fregus 2009](http://cs.nyu.edu/~fergus/) provides a matlab code to approximate the laplacian eigenvector. He calculated the Laplace beltrami operator eigenfunction then interpolate it to compute laplacian eigenvector. This matlab code provides an optimized procedure for calculating the approximated Laplacian eigenvectors. The figure below show the time analysis for computing the Laplacian smoothness using three different procedure.

- Using exact Laplacian eigenvectors (EigVector)
- Using Laplace Beltrami operator eigen functions (Eigfunctions - Fergus)
- Using Optimized approach for Laplace Beltrami operator eigen functions (Eigfunctions - Taha)

!["Alt txt"](http://ahmed-taha.com/wp-content/uploads/2015/07/time_analysis.png)




##Motivation

We cast the interactive image segmentation problem as a semi-supervised learning problem. we used [Fergus 2009](http://cs.nyu.edu/~fergus/) matlab code to test the validity of our idea. Although the results was promising, the time needed to calculate laplacian smoothness for a small image was too big. So we optimized the matlab code to become adaquate for interactive image segmentation problem.


##Setup
1. Download
2. Run the demo.m file. In the output log you will be able to see the time consumed by each calculation procedure 

For help, please contact ahmed.taha [@] alexu dot edu dot eg

##Contributor list

1. [Ahmed Taha](http://www.ahmed-taha.com/) 
2. [Marwan Torki](http://www.eng.alexu.edu.eg/~mtorki/)

##Contribution guidelines

-  We plan to deliver multiple more themes for floating ads like floating balloons and floating clouds
-  We will improve to the library to make it more customizable to display app relevant graphics.
-  Support other games Ads networks. 

## Citation
@article{tahaseeded,
   author = "Taha, A. and Torki, M.",
   title = "Seeded Laplacian: An Interactive Image Segmentation Approach using Eigenfunctions",
   year = "2015"
  } 

##License
Copyright (c) 2015, Ahmed Taha (ahmed.taha@alexu.edu.com)
All rights reserved.

Redistribution and use in source and binary forms, with or without modification, are permitted provided that the following conditions are met:

- Re distributions of source code must retain the above copyright notice, this list of conditions and the following disclaimer.
- Re distributions in binary form must reproduce the above copyright notice, this list of conditions and the following disclaimer in the documentation and/or other materials provided with the distribution.