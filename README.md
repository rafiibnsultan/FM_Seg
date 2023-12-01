# Geo_Segmentation_SAM
Hello.

I've developed this webpage that gathers various useful papers for my ongoing research on Infrastructure Segmentation in Geographical Images. This compilation can be applied to diverse segmentation areas. I've curated papers that catch my interest or resonate with my research, serving as a reference point for me. Feel free to utilize them if they align with your interests.

# Background:

## Problem:
<p class="justified-text">While extensive research has been dedicated to the segmentation of road infrastructure in geographical imagery like aerial and satellite pictures, there has been notably less emphasis on pedestrian infrastructure, such as sidewalks and crosswalks, despite its significant importance in our daily lives. Therefore, accurately segmenting both road and pedestrian infrastructures could yield valuable insights into accessible pedestrian pathways and trip destinations. This segmentation capability can effectively turned into creating a full-scalable pedestrian network.</p>
<img src="Figs/Segment.jpg" alt="Segment Pipeline">

## Foundation Model (SAM):
Segment Anything Model (SAM) <a href="https://arxiv.org/abs/2304.02643">link</a> has been trained on an enormous dataset, of 11 million images and 1.1 billion masks, and it boasts impressive zero-shot performance on already a variety of segmentation tasks.
Foundation models such as this, which have shown promising advancements in NLP and, more recently, in computer vision, can carry out zero-shot learning. This means they can learn from new datasets and perform new tasks often by utilizing ’prompting’ techniques, even with little to no previous exposure to these tasks.
SAM’s ability to generalize across a wide range of objects and images makes it particularly appealing for Geographical Image applications.

<img src="Figs/SAM.png" alt="SAM">

# Table of Contents:
* <a href="#Geo">Geographical Image Segmentation Related</a>
* <a href="#SAMGeo">SAM-based Geographical Segmentation Related</a>
* <a href="#SAM">SAM-based approaches Related</a>
* <a href="#techniques">Innovative Techniques</a>
* <a href="#Others">Others Related</a>

## <div id="#Geo"> </div>Geographical Image Segmentation Related
These papers are task-specific, focusing on geographical image segmentation.

* Mapping the Walk: A Scalable Computer Vision Approach for Generating Sidewalk Network Datasets from Aerial Imagery <a href="https://papers.ssrn.com/sol3/papers.cfm?abstract_id=4086624">paper</a>
* A Billion-scale Foundation Model for Remote Sensing Images <a href="https://arxiv.org/abs/2304.05215">paper</a>
* Towards Global-Scale Crowd+AI Techniques to Map and Assess Sidewalks for People with Disabilities <a href="https://arxiv.org/abs/2206.13677">paper</a>
* Geography-Aware Self-Supervised Learning <a href="https://arxiv.org/abs/2011.09980">paper</a>
* AutoML-Based Neural Architecture Search for Object Recognition in Satellite Imagery <a href="https://www.mdpi.com/2072-4292/15/1/91">paper</a>

## <div id="#SAMGeo"> </div>SAM-based Geographical Segmentation Related
These papers are SAM-based works that have been focusing on geographical segmentation on various tasks.
* The Segment Anything Model (SAM) for Remote Sensing Applications: From Zero to One Shot <a href="https://arxiv.org/abs/2306.16623">paper</a>
* Interactive segmentation in aerial images: a new benchmark and an open access web-based tool <a href="https://arxiv.org/abs/2308.13174">paper</a>

## <div id="#SAM"> </div>SAM-based approaches Related
These papers focus on various SAM-based approaches that are various segmentation domains that can be reproduced or upgraded in other segmentation-related tasks.
* Segment Anything <a href="https://arxiv.org/abs/2304.02643">paper</a>
* Personalize Segment Anything Model with One Shot <a href="https://arxiv.org/abs/2305.03048">paper</a>
* Segment Anything in Medical Images <a href="https://arxiv.org/abs/2304.12306">paper</a>
* SAM Fails to Segment Anything? -- SAM-Adapter: Adapting SAM in Underperformed Scenes: Camouflage, Shadow, Medical Image Segmentation, and More <a href="https://arxiv.org/abs/2304.09148">paper</a>
* SAM-Med2D <a href="https://arxiv.org/abs/2308.16184">paper</a>

## <div id="#techniques"></div>Innovative Techniques
* Multi-Object Representation Learning via Feature Connectivity and Object-Centric Regularization <a href="https://openreview.net/pdf?id=BDno5qWEFh">link</a>

  
## <div id="#Others"></div>Others Related
These papers are other important works all related to our focus.
* An image is worth 16x16 words: Trans- 660 formers for image recognition at scale
* On the Opportunities and Risks of Foundation Models <a href="https://arxiv.org/abs/2108.07258">paper</a>
* On the effectiveness of 664 parameter-efficient fine-tuning <a href="https://arxiv.org/abs/2211.15583">paper</a>
* How to Efficiently Adapt Large Segmentation Model(SAM) to Medical Images <a href="https://arxiv.org/abs/2306.13731">paper</a>


