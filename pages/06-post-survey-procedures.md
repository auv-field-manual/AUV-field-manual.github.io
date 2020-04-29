---
layout: home
permalink: /post-survey-procedures
title: "Post-survey procedures"
excerpt: "<br>"
image:
  feature: /banners/06_banner.jpg
---
{% include toc.html class="toc-left" h_min=2 h_max=2 %}

## Data processing

A general workflow for data processing methodology can be found in Williams et al. (2012). Key requirements for raw image processing and positional data are as follows:

* It is recommended that at least one of the stereo images is in colour and enhanced following similar procedures as outlined by Bryson et al. (2016). 

* All stereo images should be georectified following Williams et al. (2012). If not stereo then processing routines can be found in Morris et al. (2014).

* Positional data should be post-processed using Simultaneous Localisation and Mapping (SLAM) as demonstrated in Barkby et al. (2009) and Palomer et al. (2013)

## Data annotation

Scoring of individual images can be done using a number of annotation software tools. Examples include, Transect measure, Coral Point Count, CoralNet and Squidle+. For national consistency Squidle+ ([http://squidle.org](http://squidle.org)) is recommended as it is free and allows for different approaches in image subsampling, which appears to influence inferences from data (Monk[ et](https://paperpile.com/c/ymogqX/fFa8)[ al.](https://paperpile.com/c/ymogqX/fFa8)[ ](https://paperpile.com/c/ymogqX/fFa8)unpublished data), as well as stratified and random point count distribution on images. It also automatically imports the collected AUV data once it is uploaded to the AODN making it ready for analysis, and has tools for exploring survey data as well as analysis. In addition, it supports multiple annotation schemes, and will provide consistency through translation between schemes, which is an important point that differentiates Squidle+.

There are three approaches recommended for annotating georeferenced imagery from AUVs:

* Annotation of individual images

* Annotation of photomosaics

* Extracting structural complexity from orthomosaics

Annotation of individual images or photomosaics can be undertaken using three methods:

* Full assemblage scoring of imagery across space and time. It is important to note that this is a time-consuming process, requiring a lot of replicate images to be scored to enable sufficient power to detect biologically meaningful change as most morphospecies are < 10 % cover within images. This approach appears to be good for delineating bioregional and cross-shelf patterns at a morphospecies (Monk,[ et](https://paperpile.com/c/ymogqX/PLIP)[ al.](https://paperpile.com/c/ymogqX/PLIP)[ ](https://paperpile.com/c/ymogqX/PLIP)unpublished data) and CATAMI (Althaus et al. 2015) level (James[ et](https://paperpile.com/c/ymogqX/o2IH+wL1G)[ al.](https://paperpile.com/c/ymogqX/o2IH+wL1G)[ 2017;](https://paperpile.com/c/ymogqX/o2IH+wL1G)[ ](https://paperpile.com/c/ymogqX/o2IH+wL1G)Monk[ et](https://paperpile.com/c/ymogqX/o2IH+wL1G)[ al.](https://paperpile.com/c/ymogqX/o2IH+wL1G)[ 2016)](https://paperpile.com/c/ymogqX/o2IH+wL1G). This approach will no doubt be effective in choosing initial suite of indicators for national level monitoring and reporting. 

As a general guideline, and dependant on the survey question, we recommend that 25 random points per image from at least 50 images per transect leg are a good starting point for recording most morphospecies present within images (based on Perkins et al. 2016). It is important to note that the properties of the organism themselves will also influence the number of points/images to score. Obviously morphospecies that are less abundant require more effort, but also the 'clumpiness' of species will affect the scoring effort needed (Perkins et al. 2016). Van Rein et al. (2011) and Perkins et al.  (2016) suggest that, while a higher number of points per image can increase the detection rate of more organisms within an image, increasing the number of scored images using fewer points is likely have a similar (or greater) effect. Ideally, increasing both the number of images scored and the number of points scored within an image would result in greater power (Roelfsema et al. 2006), but preference is usually for increasing the number of images (Perkins et al. 2016). Unfortunately, the adoption of this approach is likely to result in substantial increases in processing time and thus cost. 

* Targeted scoring of indicators or proxies (such as grouping fine level morphospecies into broader level CATAMI classes; Monk et al. unpublished data). This approach has been shown to work very well at an indicator morphospecies level for detecting change at a regional level (Perkins[ et](https://paperpile.com/c/ymogqX/UPlK)[ al.](https://paperpile.com/c/ymogqX/UPlK)[ 2017)](https://paperpile.com/c/ymogqX/UPlK) as well as for detecting invasive species trends (Ling[ et](https://paperpile.com/c/ymogqX/qdrw+qfyJ)[ al.](https://paperpile.com/c/ymogqX/qdrw+qfyJ)[ 2016;](https://paperpile.com/c/ymogqX/qdrw+qfyJ)[ ](https://paperpile.com/c/ymogqX/qdrw+qfyJ)Perkins[ et](https://paperpile.com/c/ymogqX/qdrw+qfyJ)[ al.](https://paperpile.com/c/ymogqX/qdrw+qfyJ)[ 2015)](https://paperpile.com/c/ymogqX/qdrw+qfyJ). More recently this approach has been extended to mobile species, such as fish (Seiler[ et](https://paperpile.com/c/ymogqX/onCR)[ al.](https://paperpile.com/c/ymogqX/onCR)[ 2012)](https://paperpile.com/c/ymogqX/onCR) and lobster (Bessell[ et](https://paperpile.com/c/ymogqX/oYPe)[ al.](https://paperpile.com/c/ymogqX/oYPe)[ ](https://paperpile.com/c/ymogqX/oYPe)unpublished data). Care needs to be taken if length data (using photogrammetry or structure from motion) is extracted from stereo pairs from Sirius data as both Seiler et al. (2012) and Bessell et al. (unpublished data) found precision can be poor for mobile species if camera separation is inadequate [(see](https://paperpile.com/c/ymogqX/PWlr)[ Boutros](https://paperpile.com/c/ymogqX/PWlr)[ et](https://paperpile.com/c/ymogqX/PWlr)[ al.](https://paperpile.com/c/ymogqX/PWlr)[ ](https://paperpile.com/c/ymogqX/PWlr)2015)

Since this approach requires substantially less effort to score each image, more images (i.e. often all images) can be scored and, thus, increased statistical power. The drawback is that narrower understanding of the environment is produced.

* Automated analysis of imagery potentially provides a cost-effective alternative to annotating imagery from AUVs. It is important to note that automated imagery analysis is a relatively new, and largely developmental, way of annotating images. Despite this some studies suggest that coral and macroalgae can be reliably identified using automated image analysis (Table 7).

The last approach to annotating AUV imagery involves the extraction of 3D structural information from stereo images using structure from motion techniques outlined in Ferrari et al. (2016) and Pizarro et al. (2017). This approach works particularly well too for sessile species to track changes in growth form through time at a 25 x 25 m scale (Ferrari[ et](https://paperpile.com/c/ymogqX/rpiK)[ al.](https://paperpile.com/c/ymogqX/rpiK)[ 2016)](https://paperpile.com/c/ymogqX/rpiK). 

Table 4.1 A brief summary of methods for automated benthic image classification. The number of classes and the main taxa included in the respective studies are also shown.

<table>
  <tr>
    <td>Authors</td>
    <td>Classes</td>
    <td>Main Species</td>
  </tr>
  <tr>
    <td>Marcos et al. (2005)</td>
    <td>3</td>
    <td>Corals</td>
  </tr>
  <tr>
    <td>Stokes & Deane (2009)</td>
    <td>18</td>
    <td>Corals, Macroalgae</td>
  </tr>
  <tr>
    <td>Pizarro et al. (2008)</td>
    <td>8</td>
    <td>Corals, Macroalgae</td>
  </tr>
  <tr>
    <td>Beijbom et al. (2012)</td>
    <td>9</td>
    <td>Corals, Macroalgae</td>
  </tr>
  <tr>
    <td>Denuelle & Dunbabin (2010)</td>
    <td>2</td>
    <td>Kelp</td>
  </tr>
  <tr>
    <td>Bewley et al. (2012)</td>
    <td>19</td>
    <td>Corals, Algae and Kelp</td>
  </tr>
  <tr>
    <td>Bewley et al. (2014)</td>
    <td>19</td>
    <td>Corals, Algae and Kelp</td>
  </tr>
  <tr>
    <td>Beijbom et al. (2016)</td>
    <td>10</td>
    <td>Corals, Macroalgae</td>
  </tr>
  <tr>
    <td>Mahmood et al.(2016a)</td>
    <td>9</td>
    <td>Corals, Macroalgae</td>
  </tr>
  <tr>
    <td>Mahmood et al. (2016b)</td>
    <td>2</td>
    <td>Corals, Macroalgae</td>
  </tr>
</table>


## Data curation and quality control

A national AUV steering group has been set up to oversee a nationally coordinated AUV benthic monitoring program which is supported by the Integrated Marine Observing System (IMOS) (Table 4.2). Any new AUV deployments should be discussed with this steering group to ensure that, wherever possible, they can be integrated within the national program *[Recommended]*.

Table 4.2 Key contacts in national AUV steering group as of Jan 2018

<table>
  <tr>
    <td>Name</td>
    <td>State</td>
    <td>Organisation</td>
  </tr>
  <tr>
    <td>Neville Barrett*</td>
    <td>Tasmania</td>
    <td>IMAS</td>
  </tr>
  <tr>
    <td>Craig Johnson</td>
    <td>Tasmania</td>
    <td>IMAS</td>
  </tr>
  <tr>
    <td>Peter Steinberg</td>
    <td>New South Wales</td>
    <td>SIMS</td>
  </tr>
  <tr>
    <td>Alan Jordan</td>
    <td>New South Wales</td>
    <td>NSW DPI</td>
  </tr>
  <tr>
    <td>Stefan Williams</td>
    <td>New South Wales</td>
    <td>USyd</td>
  </tr>
  <tr>
    <td>Gary Kendrick</td>
    <td>Western Australia</td>
    <td>UWA</td>
  </tr>
  <tr>
    <td>Russ Babcock</td>
    <td>Western Australia</td>
    <td>CSIRO</td>
  </tr>
  <tr>
    <td>Paul Van Ruth</td>
    <td>South Australia</td>
    <td>SARDI</td>
  </tr>
  <tr>
    <td>Hugh Sweatman</td>
    <td>Queensland</td>
    <td>AIMS</td>
  </tr>
  <tr>
    <td>Tom Bridge</td>
    <td>Queensland</td>
    <td>JCU/QLD Museum</td>
  </tr>
  <tr>
    <td>Daniel Ierodiaconou</td>
    <td>Victoria</td>
    <td>Deakin</td>
  </tr>
</table>


* Chair

Data quality control at both the collection and annotation stage is critical. Most importantly, the annotation schema needs to be consistent between studies. Morphospecies and associated CATAMI parent classes be used *[Recommended]*. An initial morphospecies catalogue for southeastern shelf waters is currently held and maintained at the Institute for Marine and Antarctic Studies (IMAS) (contact Dr Neville Barrett or Dr Jacquomo Monk). 

Other annotation schema are available, and can be applied. In such situations where an alternative schema are used to annotate AUV imagery, it must be able to be mapped to CATAMI so that comparisons can be made with previous studies or between regions. Translations between schema can be readily applied within Squidle+. The quality control of all annotations undertaken by novice scores should be assessed against an experienced analyst (e.g. using confusion matrices; Figure 4.4). Logically, it is important to correct any discrepancies between annotators. This can be done by re-examining the images to ensure an agreement can be reached between annotators. Alternatively, if an agreement cannot be reached, then the miss-classified morphospecies could be potentially grouped into a higher level CATAMI class.

![image alt text](images/figures/image_3.png)

Figure 4.4 Confusion matrix showing the CATAMI classes scored by novice 1 (AW) and experienced (JH) for 30 co-scored images. Black outlined boxes indicate consistent classification between scorers, the percent of all points scored as any particular class are is shown in each box and colour coded. Blue outlined boxes indicate sponge, bryozoan/hydroid and substratum respectively moving from left to right across the image.

## Data release

[Squidle+](https://squidle.org/) is a centralised online platform for standardised analysis and annotation of georeferenced imagery and video. Many national marine observing programs (for example IMOS through the Australian Ocean Data Network (AODN) or the Marine Geoscience Data System (MGDS) in the USA) routinely store imagery data online in an openly accessible location. Squidle+ operates based on flexible distributed data storage facilities (i.e. imagery can be stored anywhere in an openly accessible online location) to reduce data duplication and inconsistencies, and provides a flexible annotation system with the capability to translate between different annotation schemes.

Following the steps listed below will ensure the timely release of imagery and associated annotation data in a standardised, highly discoverable format.

1. Create a metadata record describing the data collection. Provide as much detail as possible on the deployment (either directly in the metadata record itself, or in the form of attached field sheets as .csv, .txt or similar). Details of minimum metadata requirements are provided in Onboard Data Processing and Storage section above.

2. Publish metadata record(s) to the [Australian Ocean Data Network (AODN) catalogue](http://catalogue.aodn.org.au/geonetwork/srv/eng/main.home) as soon as possible after metadata has been QC-d. This can be done in one of two ways:

* If metadata from your agency is regularly harvested by the AODN, follow agency-specific protocols for metadata and data release. 

* Otherwise, metadata records can be created and submitted via the [AODN Data Submission Tool](https://metadataentry.aodn.org.au/submit). Note that user registration is required, but this is free and immediate.

Lodging metadata with AODN in advance of annotation data being available is an important step in documenting the methods and location of acquired imagery and enhancing future discoverability of the data.

3. Upload raw imagery from the survey to a secure, publicly accessible online repository ([contact AODN](mailto:info@aodn.org.au) if you require assistance in locating a suitable repository).

4. Create a Squidle + campaign as soon as possible after imagery is uploaded, choose the most appropriate annotation schema, and commence annotation of imagery.

5. Add links to the location of the Squidle+ campaign to the previously published metadata record. You may also wish to attach or link a copy of the annotation data directly to the record.

6. Produce a technical or post-survey report documenting the purpose of the survey, sampling design, sampling locations, sampling equipment specifications, annotation schema (e.g. morphospecies, CATAMI, etc.), whether the survey was assemblage-based or targeted towards key (morpho)species, number of points, interval between images (e.g. every 50th image), and any challenges or limitations encountered. Provide links to this report in all associated metadata. See Appendix C for a suitable template *[Recommended].* 

## Data analysis

The breadth of research questions precludes any detailed advice on the analysis of data from AUV transects. However, one common attribute of the image-based data that will have to be contented with for all analyses is spatial proximity. The closeness of images, within and sometimes between transects, means that image data are unlikely to be independent (due to spatial autocorrelation). Yet, this is an assumption that many statistical methods rely upon. The failure to meet this assumption means that the inferences from the statistical analysis may be: (i) over-confident, e.g. having a p-value that is too small; (ii) biased, i.e. the estimates do not reflect the truth; (iii) both, or; (iv) no effect. Obviously, the fourth category is what a researcher hopes for, but it is improbable and must be validated. However, if it is known that the study organism exhibit particularly low autocorrelation then the analysis need not consider it explicitly. 

Methods to analyse data, accounting for autocorrelation are available.  These include geostatistical models [(see](https://paperpile.com/c/ymogqX/gHzq)[ ](https://paperpile.com/c/ymogqX/gHzq)Foster[ et](https://paperpile.com/c/ymogqX/gHzq)[ al.](https://paperpile.com/c/ymogqX/gHzq)[ ](https://paperpile.com/c/ymogqX/gHzq)2014 [for](https://paperpile.com/c/ymogqX/gHzq)[ AUV-based](https://paperpile.com/c/ymogqX/gHzq)[ examples)](https://paperpile.com/c/ymogqX/gHzq). However, in certain situations subsampling images will help [(see](https://paperpile.com/c/ymogqX/snQQ)[ ](https://paperpile.com/c/ymogqX/snQQ)Mitchell[ et](https://paperpile.com/c/ymogqX/snQQ)[ al.](https://paperpile.com/c/ymogqX/snQQ)[ 2017](https://paperpile.com/c/ymogqX/snQQ)[ for](https://paperpile.com/c/ymogqX/snQQ)[ a](https://paperpile.com/c/ymogqX/snQQ)[ marine](https://paperpile.com/c/ymogqX/snQQ)[ based](https://paperpile.com/c/ymogqX/snQQ)[ example)](https://paperpile.com/c/ymogqX/snQQ), but not necessarily alleviate completely. Further, if the study is for a broad area, where transects are small and are well-separated, then amalgamating data to transect level may also be appropriate.

## Field Manual Maintenance

In accordance with the universal field manual maintenance protocol described in Chapter 1 of the Field Manual package, this manual will be updated in 2018 as Version 2. Updates will reflect user feedback and new developments (e.g. data discoverability and accessibility). Version 2 will also detail subsequent version control and maintenance.

 

The version control for Chapter 4 (field manual for AUVs) is below:

<table>
  <tr>
    <td>Version Number</td>
    <td>Description</td>
    <td>Date</td>
  </tr>
  <tr>
    <td>0</td>
    <td>Submitted for review (NESP Marine Hub, GA, external reviewers as listed Appendix A.</td>
    <td>22 Dec 2017</td>
  </tr>
  <tr>
    <td>1</td>
    <td>Publicly released on www.nespmarine.edu </td>
    <td>28 Feb 2018</td>
  </tr>
  <tr>
    <td>1.1</td>
    <td>Link to Squidle+ corrected</td>
    <td>March 2018</td>
  </tr>
  <tr>
    <td>2</td>
    <td>Relevant updates, including Data Release sections based on NESP, AODN, IMOS, GA, and CSIRO projects </td>
    <td>Mid 2019</td>
  </tr>
</table>
