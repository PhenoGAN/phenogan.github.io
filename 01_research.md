---
layout: post
title: Research
image: assets/images/research_new.jpg
permalink: research/index.html
---

## PhenoGAN - Spatio-temporal generation of morphological Plant features for yield prediction before harvest from Visual Image input using Progressively Growing GANs

![header-research](https://user-images.githubusercontent.com/99654398/153884838-f6be4ba1-fe8d-4865-90a1-33bc3399b66c.png)



## Abstract

<span style="font-size:0.9em;">
Recent Innovations in Precision Agriculture (PA) are driven by Computer Vision and Data Processing systems to quantify plant parameters. Quantitative analysis of Plant Phenotyping in PA and monitoring morphological traits is a protracting process, precluding the objective and phenotyping pipeline. Computer
Vision and Generative Adversarial Networks (GAN)’s offer a catalytic approach to the time-consuming
process, providing a solution to the phenotyping bottleneck. This research proposes a concept of curating
data of plant growth over time to predict conditional growth and responsive stimuli of the plant under
different situations and how this can affect crop yield. The method proposed here is a non-invasive approach to the existing destructive biomass estimation methods and Frameworks. This methodology of the
research focuses on utilizing image parameters modelled using a time series Progressively Growing Generative Adversarial Networks PGGAN to map plant growth patterns and progressive variance in biomass of
plant in the Spatio-Temporal Domain. These Generative networks evaluate and predict based on merely
raw pixel input excluding dependence on further constraints, feature vectors or parameters influencing
data.
</span>
<p style="margin: 0 auto; font-size:0.9em; text-align:left ; " markdown="1">
  </p>

<br>

## Problem Statement

<span style="font-size:0.9em;">
Phenomics is the systematic study of phenotypes coined by
Steven A. Garan et al. as emerging transdisciplinarity dedi-
cated to the systematic study of phenotypes on a genome-wide
scale. From decades quantifiable phenotyping and assessing
parameters presented invasive methods and techniques. This
task to a lot extent, was manual and hindered accurate as well
as time-efficient measurement and assessment. All these ap-
proaches arguably present one common interdisciplinary goal,
i.e increasing phenotyping throughput and maximizing yield
quantitatively. However such approaches survey crops and
present data analysis delayed enough to not procure any room
for yield maximization. Multiple different approaches have
claimed to observe and analyze crop parameters over complete
growth period and establish a fine relation between temporal
and yield estimation patterns, but such proposed methods ob-
tain results over a large set of data points, generalized over a
specific factor.
</span>
<p style="margin: 0 auto; font-size:0.9em; text-align:left ; " markdown="1">
  </p>

<br>



##  Importance and Relevance


<span style="font-size:0.9em;">
Greenhouses growing Genetically Modified (GM) crops need to
be maintained at constant environmental and simulated condi-
tions. Multiple parameters have to be controlled and regulated
inside a greenhouse for effective growth of crops and yield max-
imisation. Not at all times are these factors derived and so,
yield maximisation in greenhouse is an experimental approach
to new varieties. For deduced environmental parameters and
conditions for certain crops, few other biotic and abiotic factors
can hinder or affect growth in certain ways that are not always
factored in during calculating parameters conducive for plant
growth. Such factors may not always be affecting parametral
calculations, but transpose visual cues on plant growth environ-
ment such as spectral change in soil values, or minute changes
like leaf reflectance or visible changes in plant stimuli to biotic
factors. Plant growth is inclusive of multiple environmental
variables, and yield maximisation approaches are experimen-
tal to finding the optimum derived value for these variables.
Computer Vision provides a catalytic approach to predicting
optimum parameters for yield maximization in phenomics.
</span>
<p style="margin: 0 auto; font-size:0.9em; text-align:left ; " markdown="1">
  </p>

<br>



### GCE

<span style="font-size:1em;"> GCE excites stereo cost volume using weights extracted from image features. </span>

<!-- <div class="row">
    <div class="col-sm mt-4 mt-md-0">
        <img class="img-fluid rounded z-depth-0" src="{{ '/assets/img/publications/CoEx/exc_0_2b.png' | relative_url }}" alt="" title="example image"/>
    </div>
    <div class="col-sm mt-4 mt-md-0">
        <img class="img-fluid rounded z-depth-0" src="{{ '/assets/img/publications/CoEx/exc_1_2b.png' | relative_url }}" alt="" title="example image"/>
    </div>
    <div class="col-sm mt-4 mt-md-0">
        <img class="img-fluid rounded z-depth-0" src="{{ '/assets/img/publications/CoEx/exc_2_2b.png' | relative_url }}" alt="" title="example image"/>
    </div>
    <div class="col-sm mt-4 mt-md-0">
        <img class="img-fluid rounded z-depth-0" src="{{ '/assets/img/publications/CoEx/exc_3_2b.png' | relative_url }}" alt="" title="example image"/>
    </div>
</div>  -->

<!-- <div class="row">
    <div class="col-sm mt-1 mt-md-0" align="center" >
        <img class="img-fluid rounded z-depth-0" width="467" height="562"  src="{{ '/assets/img/publications/CoEx/exc.jpg' | relative_url }}" alt="" title="gce"/>
    </div>
</div>   -->

<p align="center">
  <img width="467" height="562" src="/assets/img/publications/CoEx/exc.jpg" title="GCE excitation weights" data-zoomable>
  <p style="margin: 0 auto; font-size:0.8em; text-align:center ; max-width: 70%;" markdown="1">
Computed excitation weights in one of the GCE layers. 
  </p>
</p>

<br>

### Top-k soft-argmin disparity regression

<span style="font-size:1em;"> Instead of computing disparity by soft-argmin using the whole cost volume, only the top-k relevant values are used. </span>

<p align="center">
  <img width="747" height="182" src="/assets/img/publications/CoEx/topk_chart.png" title="top-k charts">
  <p style="margin: 0 auto; font-size:0.8em; text-align:center ; max-width: 70%;" markdown="1">
Ground truth disparity is represented by vertical solid green line. Predicted disparity is vertical dashed red line. *k=2* makes the closest regression estimates to the ground truth.
  </p>
</p>


<div class="row mt-2">
    <div class="col-sm mt-2 mt-md-0">
    <p align="right">
        Top-48
        <img class="img-fluid rounded z-depth-0" src="{{ '/assets/img/publications/CoEx/cost_top48_compress.gif' | relative_url }}" alt="" title="cost top-48" data-zoomable/>
    </p>
    </div>
    <div class="col-sm mt-2 mt-md-0">
    <p align="left">
        <img class="img-fluid rounded z-depth-0" src="{{ '/assets/img/publications/CoEx/cost_top2_compress.gif' | relative_url }}" alt="" title="cost top-2" data-zoomable/>Top-2
    </p>
    </div>
</div> 
<div class="caption">
    Activation strengths at fronto-parallel slices of the cost volume for top-48 and top-2 soft-argmax regression. Red represents stronger activation and blue is weak. Notice how the activations with top-2 regression is stronger and sharper.
</div>
## Demo

### Real-time stereo matching

<div class="row mt-3">
    <div class="col-sm mt-3 mt-md-0">
        <img class="img-fluid rounded z-depth-0" src="{{ '/assets/img/publications/CoEx/coex_compress3.gif' | relative_url }}" alt="" title="CoEx" data-zoomable/>
    </div>
    <div class="col-sm mt-3 mt-md-0">
        <img class="img-fluid rounded z-depth-0" src="{{ '/assets/img/publications/CoEx/psm_compress3.gif' | relative_url }}" alt="" title="PSMNet" data-zoomable/>
    </div>
    <div class="col-sm mt-3 mt-md-0">
        <img class="img-fluid rounded z-depth-0" src="{{ '/assets/img/publications/CoEx/ganet_compress3.gif' | relative_url }}" alt="" title="GANet" data-zoomable/>
    </div>
</div> 
<div class="row mt-3">
    <div class="col-sm mt-3 mt-md-0" align="center">
        <p>CoEx (Ours)</p>
    </div>
    <div class="col-sm mt-3 mt-md-0" align="center">
        <a href="https://openaccess.thecvf.com/content_cvpr_2018/papers/Chang_Pyramid_Stereo_Matching_CVPR_2018_paper.pdf">
            <span style="color:blue">PSMNet</span>
        </a>
        [1]
    </div>
    <div class="col-sm mt-3 mt-md-0" align="center">
        <a href="https://openaccess.thecvf.com/content_CVPR_2019/papers/Zhang_GA-Net_Guided_Aggregation_Net_for_End-To-End_Stereo_Matching_CVPR_2019_paper.pdf">
            <span style="color:blue">GANet</span>
        </a>
        [2]
    </div>
</div> 
<div class="caption">
    Speed comparison with previous works. *The images shown are compressed, so image quality may not reflect the real output of the models.
</div>

### Stereo 3D reconstruction

<p align="center">
  <img width="640" height="336" src="/assets/img/publications/CoEx/recons_compress3.gif" title="3d reconstruction" data-zoomable>
  <p style="margin: 0 auto; font-size:0.8em; text-align:center ; max-width: 70%;" markdown="1">
Reconstructed 3d point cloud computed from the predicted stereo disparity map.
  </p>
</p>

### Application - visual odometry and point cloud mapping

<p align="center">
  <img width="640" height="336" src="/assets/img/publications/CoEx/vo+map_compress3.gif" title="vo+map" data-zoomable>
  <p style="margin: 0 auto; font-size:0.8em; text-align:center ; max-width: 70%;" markdown="1">
Application test using the computed stereo depth to perform visual odometry and point cloud mapping.
  </p>
</p>

### Related works
[\[1\] J.-R. Chang and Y.-S. Chen, “Pyramid stereo matching network,” in
CVPR, 2018](https://openaccess.thecvf.com/content_cvpr_2018/papers/Chang_Pyramid_Stereo_Matching_CVPR_2018_paper.pdf)  
[\[2\] F. Zhang, V. Prisacariu, R. Yang, and P. H. Torr, “Ga-net: Guided
aggregation net for end-to-end stereo matching,” in CVPR, 2019.](https://openaccess.thecvf.com/content_CVPR_2019/papers/Zhang_GA-Net_Guided_Aggregation_Net_for_End-To-End_Stereo_Matching_CVPR_2019_paper.pdf)

