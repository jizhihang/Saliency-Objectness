# Salient Object Detection via Objectess Measure
This demo shows how to use Saliency Objectness[1], as well as Saliency 
Optimization[2], Saliency Filter[3], Geodesic Saliency[4], 
and Manifold Ranking[5].

Code for [1] by Sai Srivatsa R  
Email : saisrivatsan12@gmail.com  
Date : 12/09/2015

Code for [2,3,4,5] by Wangjiang Zhu  
Email: wangjiang88119@gmail.com  
Date: 3/24/2014  

If you use this code, please cite both [1] and [2].

### Instructions

To run the demo for default images stored in `Data\SRC` and to perform evaluation run: `>>demo`.  
The saliency maps are stored in `Data\Res` .  

To obtain saliency maps for custom images using our approach and other methods:
(1) Add the required files to `Data\SRC` .  
(2) Add the Objectness Proposals generated by BING [6] to `BingBoxes\` .  
(3) Now run the demo: `>>demo`.    

To evaluate our approach and other methods: 
(1) add the ground truth images to `Data\GT`.
(2) Now run the demo: `>>demo`


### References


[1] Sai Srivatsa R, R Venkatesh Babu. Salient Object Detection via
Objectness Measure. In ICIP, 2015.

[2] Wangjiang Zhu, Shuang Liang, Yichen Wei, and Jian Sun. Saliency
Optimization from Robust Background Detection. In CVPR, 2014.

[3] F. Perazzi, P. Krahenbuhl, Y. Pritch, and A. Hornung. Saliency
filters: Contrast based filtering for salient region detection.
In CVPR, 2012.

[4] Y.Wei, F.Wen,W. Zhu, and J. Sun. Geodesic saliency using
background priors. In ECCV, 2012.

[5] C. Yang, L. Zhang, H. Lu, X. Ruan, and M.-H. Yang. Saliency
detection via graph-based manifold ranking. In CVPR, 2013.

[6] M.M Cheng and Z. Zhang and W. Y. Lin and P. H. S. Torr. Binarized 
Normed Gradients for Objectness Estimation at 300fps. In CVPR, 2014.



