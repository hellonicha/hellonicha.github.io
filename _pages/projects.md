---
layout: archive
title: "Projects"
permalink: /projects/
author_profile: true
---

WIP

# Current Projects

## Identification of Autism from fMRI
<img src="/images/classification_network.png" alt="Classification Network" width="400"/>

## Prediction of Autism Treatment Outcome

## Classification of Breathers

---

# Past Projects

## Fast Single Particle Reconstruction for Cryo-Electron Microscopy

Cryo-electron Microscopy (cryo-EM) has emerged as a key tool for studying protein structure. The 2D cryo-EM projection images of frozen protein samples, i.e. *particles*, are used to infer the protein's 3D structure through a process called *single particle reconstruction*. Single particle reconstruction methods based on the maximum-likelihood principle are popular because of their ability to produce high resolution structures. However, these algorithms are computationally very expensive, requiring a network of servers. To address this problem, we developed a new algorithm called [SubspaceEM](https://www.sciencedirect.com/science/article/pii/S1047847715000714) for accelerating maximum-likelihood reconstructions by utilizing subspace approximations of the cryo-EM images and the structure projections. The speedup is by orders of magnitude, and the new algorithm produces similar quality reconstructions compared to the traditional maximum-likelihood formulation. 

## Image Registration with Missing Correspondences

Medical image registration is used to align patient images from different treatment time points to a single reference frame. This process of establishing correspondences between images is important for making meaningful comparisons across scans. Traditional registration algorithms assume a one-to-one correspondence between features in the images to be aligned. However, this assumption is clearly violated when the images are *missing correspondences*, which often occurs when dealing with patient data due to treatment effects or disease progression. Standard registration methods, therefore, will likely fail to align actual corresponding features, especially near locations with missing data, i.e. the regions of interest. [My PhD dissertation](https://search.proquest.com/docview/1269517129) focused on the development of an automated image registration algorithm to deal with the missing correspondence problem. The key idea is to incorporate the estimation of a label map segmenting the valid and missing correspondence voxels during the registration. We pose the registration problem in a maximum a posteriori framework and jointly solve for the transformation parameters and label map. The developed algorithmic framework is general and can be adapted to many missing correspondence problems, including [alignment of preoperative and postresection brain images](https://link.springer.com/content/pdf/10.1007/978-3-642-15705-9_45.pdf) and [tracking brain metastases over time](https://link.springer.com/content/pdf/10.1007%2F978-3-642-33555-6_11.pdf).

<!---
{% include base_path %}


{% for post in site.projects %}
  {% include archive-single.html %}
{% endfor %}
--->

