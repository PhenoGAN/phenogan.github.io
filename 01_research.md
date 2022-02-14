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


## Datasets

In the proposed paper, I use two phenotyping datasets differing in throughput and quantitatively using PGGAN’s to generate predicted crop yields for the frames. With the pandemic
widespread during research, it wasn’t favorable to collect data
from plant phenotyping specimens in the school laboratory under different controlled environments. Hence, choosing evaluated and properly curated datasets under monitored conditions
from Open Access research papers made available for academic
purposes was the best choice. The first dataset used in the research was of Arabidopsis Thaliana plants in a high throughput
environment. The second dataset, were of Beta vulgaris (sugar
beet plants) of the variety ’Samuela’ in KWS Suisse SA, Basel,
Switzerland under different stresses.


### A.1. Arabidopsis Thaliana Dataset

![ADPS4](https://user-images.githubusercontent.com/99654398/153907993-a0dd1d0c-3a73-4f66-9bd9-769d40620f9e.png)


Arabidopsis Thaliana is an annual weed which has been used
in multiple research methods for phenotyping over the past
decade and is an important plant model. One of the reasons for
the growing interest in Thale Cress, Arabidopsis thaliana is due
to the fact that it grows, reproduces and responds to external
environments or stresses similar to other commercial plants and
crops. This plant can easily be cultivated in a small confined
lab or greenhouse, and is inexpensive as well as allows simulating conditional growth as observed in multiple other crops.
With the ability to mutagenize easily and possessing a comparatively small genome, enables extensive genetic experiments and
covariance in genotype-phenotype correlations.
Despite being recognized as a non-commercial crop and having a low economic value, it has proven to be a sustainable plant
model to simulate phenotype and genotype growth patterns
across multiple crops. Arabidopsis contains a diploid genome
with under 30,000 protein encoding genes distributed over 5
chromosomes to enable scalable research over different genome
and phenotypical patterns[16]. For a a particular environmental condition and under different stresses, if the Arabidopsis
Thaliana phenotype performs effective under these conditions
and a corresponding genotype can be derived. With the high
covariance in genotypical similarity, a similar gene can be found
in other plant accelerating research in maximizing yield.
In this research paper, to accomplish the objective of proposed
method, I utilize the Arabidopsis Thaliana Dataset curated by
Hannah et al. [15] under the background of the EPSRC funded
project “Dynamic Modelling of Plant Growth with Computer
Vision”. The dataset is acquired in a top-down view format
in visual RGB imagery, in a high throughput growth environment. The dataset includes segmented area for the corresponding leaves and plant.
These Arabidopdis Thaliana plants, accession Columbia (Col0) were grown in 180ml compost (Levington F2 + 205 grit sand)
in PSI 6cm square pots, as described in Open Access Dataset.
These plants were grown to 75% field capacity (region extent
covering the field/pot) with gravimetric watering in a 10 hour
day in a glasshouse regime maintained at 15°C to 20°C on the PSI
platform. The seeds were sown and the plants were pricked after
10 days into weighted pots. 80 plants were grown, split between
4 trays. To lessen the probability of plants overlapping adjacent
plants in trays at a later stage of growth, certain neighbouring
plants were removed between 30 to 53 days after sowing and the
plants were harvested at 56 days after sowing. Imaging for each
plant started at 21 days after sowing and continued for a total of
35 days. The top-view image of the plant was captured each at
an interval of 15 minutes, which started at 9am and continued
till 8pm daily.
Since this dataset is curated such, and plants are grown in a
high throughput phenotyping environment, no environmental
constraints or stresses were introduced in growing the plant. The
plant was intended to grow in ideal conditions, and the intent of
the dataset used for the GAN model was to replicate growth in
high throughput environment while simultaneously also testing
the efficacy of another dataset under environmental and biotic
stresses to ensure Generated temporal and spatial sequences
maintain high accuracy even in biased, or continuously varying,
data with introduced anomalies as well as in ideal conditions.
Training GAN’s require an upwards of 100k images in general,
but this solution maintains generation of high resolution images
for training dataset under 700 and 500 images respectively for
each dataset. Acquisition of images for plant phenotyping is
usually limited for training of Neural Networks. Under this
constraint, developing a GAN Network capable of generating
similar images from small dataset has been one of the challenges,
but also one of the aims of the project.

### A.2. Sugar Beet plants (Beta vulgaris) Dataset

![DTST](https://user-images.githubusercontent.com/99654398/153907837-a2aebd21-90d2-4b87-b06e-db05c0e561a3.jpg)



Contrary to the initial Dataset of Arabidopsis Thaliana Col-0
Ecotype grown under high throughput conditions, this dataset
aims to replicate Real world multivariate environmental factors affecting crop growth in a controlled environment. The
plant cultivars grown in this dataset are grown under multiple
stress factors such as weeds, drought and nutrient deficiency,
and other multiple combinations of such constraints containing
weed induced nitrogen contraint or weed induced hydration
deficiency. Such multiple environmental constraints on crops
in controlled environment intend to simulate real conditions of
crops where certain environmental variables and parameters
aren’t conducive for crop growth or prevent maximization of
yield. This dataset also visually replicates the real world scenario
under multiple aspects with distorted varied geometry in each
image, varying illuminance, varying dimensions for Region of
Interest (ROI) and certain measured errors in distance of captured images, and a smaller dataset compared to the first one
with under 500 images. The dataset generated spatio-temporal
outputs can be used to predicted the optimum growth environment from visual traits as well as deriving the soil pattern with
optimum use of bio-fertilizers or other inputs to plants enabling
Variable Rate Application (VRA) methodology on plant cultivars. All such visual, and environmental constraints make this
a perfect dataset to replicate the Real world scenario and test
the efficacy of the model in adverse conditions claiming the robustness of the utilized novel Generative Adversarial Network
(GAN) architecture in training the model in a simulated setting.
The curated dataset consists of prevalent Spatio-temporal
visual, Infrared and Spectral data, each of the same set of plant
cultivar captured of sugarbeet growth under optimal conditions, high throughput singleton condition with surplus Nitrogen fertilization and abundantly under varying environmental
stresses, Nitrogen deficiency, low/medium/high weed stress
and also covarying weed stress with Nitrogen and Water deficiency. Compared to the previous approach consisting of two
trays and multiple plant arrays with images acquired every 15
minutes, this approach consists of 30 trays, with single plant
and image acquired biweekly, reducing the overall set of images twice to a total of 432 images of different plants captured
and 16 Spatio-temporal images of the same plant. The curated
dataset contains over two months of data, wherin visual, stereo

## A. Proposed Architecture
The most crucial part of this research was to understand the
Network Architectures most suitable to fulfill the aim of the
project. This research required the use of a Spatio-Temporal
3 Dimensional Generative Adversarial Network Architecture
suitable under multiple settings and generates accurate and realistic predictions of Visual RGB images with a small dataset
< 700 images. For this purpose the GAN constructed for the
research was adopted from one of the initially proposed Progressively Growing Spatio-Temporal GANs (PGGAN) for generating
Future Frames by Marco et al. [10]. Generative Adversarial Networks are an extension of Convolutional Neural Networks and
are composed of two diverse Networks, Generator and Discriminator. Given a training set, initial approaches to standard GANs
learn to generate new data with statistical reference from training set. GANs initially were proposed to generate new data in
unsupervised learning, however the rate of application of GANs
in different domains has evolved this network to be utilized
in supervised, semi-supervised and in reinforcement learning
approaches. Two networks in a GAN, the Generator,as the name
indicates Generates new, but statistically similar images as in
the training set and the Discriminator evaluates the Generations
in an unsupervised adversarial setting. These networks functions simultaneously, and the Generator maps data distributions
in the constrained interest from the latent space and the generations are evaluated to test the analogous similarities in the
generations to the training set in the latent space.
A developed approach to the same concept of GANs, a PGGAN was introduced in this research to effectuate the goal of
Spatio-Temporal 3 Dimensional data point generations. The proposed framework is based on the idea of training the Generator
in an adversarial setting to predict sequential video frames based
on input past frame. The discriminator is trained to distinguish
between the generated realistic and fake samples. The proposed
network employs discriminator in a way such that it is trained
to discriminate between the generated sequence by the generator as well as from training dataset alternatively for a given
set of temporal frames. Discriminator distinguishes between
samples with a score ranging from 0 to 1, with 0 representing
fake samples and 1 close to realistic. Based on the output score
feedback representing the generated samples as realistic or fake,
the Generator updates it’s model weights after a given set of
iterations to generate better samples with the feedback from the
sample scores

![NTWK128](https://user-images.githubusercontent.com/99654398/153908308-789456ec-3416-4dda-9ad1-c2b7c36cc194.png)

![NTWK32](https://user-images.githubusercontent.com/99654398/153908364-4ac2e0c9-873b-45af-9b72-71a204eda859.png)

![NTWK4](https://user-images.githubusercontent.com/99654398/153908421-86fb4942-863d-483e-9e53-ed6b78744ccd.png)


## Covariance Metrics for Beta Vulgaris Dataset
With increased complexity and number of features in the sample
and different visual traits contributing to growth modelling and
morphology, and different sample types with induced stresses,
this model had multiple complicated features in the latent space
to learn from as compared to the previous model. For the same
reason, this model was trained for 365 epochs rather than 230 in
the first model. The latter 135 epochs took significantly larger
amount of time than the initial epochs because of the larger
weight size scaled up to 128x128 resolution. The lr decay helped
in increasing entropy and decreasing noise while acting as a
caveat which increases the number of epochs required for training. Irrespective of all these flaws, the model showed high
correlation between Ground Truth and Generated frame Vegetation Indices from Visual Area, ExG, ExGR to even ExR indicating
that soil features show high correlation as well (An improvement from the first dataset). Overall Correlation for ExG, ExR,
ExGR and Segmented Area for the Beta Vulgaris Generated samples with the ground truth samples maintained high consistency
throughout the different samples in the dataset. The Ground
Truth and Generated Samples observed near-stellar covariance
illustrating that the Generated samples show high similarity
with the Ground Truth Samples.
Speaking about the ExR, a measure of Excessive Red typically
for the soil, the soil features generated in this model showed
great similarity of r-value 1.00 -The p-value of 0 indicating that
all samples in the dataset are statistically significant in the model.
These Vegetation Indices are not a measure of pixel-level similarity (SSIM measures Structural Similarity) - instead these Vegetation Indices are a measure of the gradient of features present
in the Generated samples. Talking about plant vegetation, the
mean ExG measures distributed trend of Excessive Green observed throughout the plant sample and the density of leaf in a
unit measured, correlating with the Excessive Green in Generated Samples. These Vegetation Indices help in better identifying
the responsive and morphological overall growth and generation of feature type, rather than pixel level similarity. This helps
in a holistic measurement of the plant visual traits generated
rather than just understanding how similar was the Generation
to the Ground Truth Image. Taking an example, if a weed is
observed in the input samples and the Generated images similarly generate the weed samples carried over further frames,
the Vegetation Indices would measure the density of the Generated weed or the features of the Weed in the samples rather
than similarity measure as of identifying the exact position of
the weed generation and correlating efficacy. This extensively
helps in identifying if a model is Robust in it’s true sense in
real world samples or if they are conditional to outliers. The
model performing well in Correlation of Generated Samples
in Vegetation Indices as well as SSIM,PSNR,MSE proves that
not only is the model objectively capable of understanding
outliers, but is also proved to generating similar and accurate real world samples, demystifying prediction of harvest
through conditional visual features which extensively affect
growth where existing methods fail upon.
With the ideology being carried to evaluating the Vegetation
Indices in Generated samples, the model is objectively as well as
subjectively capable of generating frames till harvest with each
of these frames (till 8th) contributing to pearson’s coefficient (r)
in evaluation. Mean ExR shows a r-value of 1.00, the highest in
all Vegetation Indices with the Soil feature samples learning diversely all features from the visual input and outliers. Mean ExG
and ExGR of r-value 0.99 dynamically indicate that leaf features
throughout the sample covary in terms of leaf reflectance, density, venation features and color gradient in response to external
sunlight or internal nutritional factors, under stresses. Cumulatively, the segmented Area from Visual ExGR with r-value of
0.99, illustrating leaf generation (in terms of generative morphology, from high leaf area generated for control plant cultivars
to low leaf area generated for stressed cultivars), dynamically
morphing over all samples.

![ADPS-eg](https://user-images.githubusercontent.com/99654398/153909378-26ccea67-aee1-4b21-949b-2c105d39ab80.jpg)


For a detailed overview, read the paper here - https://www.essoar.org/cms/asset/6a9d775a-4a00-4daf-9814-ebd6128e69f8/dhruv-sheth-iris-research_compressed.pdf
