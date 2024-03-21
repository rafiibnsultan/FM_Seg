# Foundation Model-Based Image Segmentation
Hello.

I've developed this webpage that gathers various useful papers for my ongoing research on Foundation Model (FM) Based Segmentation. This compilation can be applied to diverse segmentation areas. I've curated papers that catch my interest or resonate with my research, serving as a reference point for me. Feel free to utilize them if they align with your interests. A survey focusing on FM-based approaches focusing on Geographical Images and Medical Images have been created for my recent PhD qualifying exam. You can find it <a href="Qual_Rafi.pdf">here as well. 

## Background:
Segment Anything Model (SAM) <a href="https://arxiv.org/abs/2304.02643">link</a> has been trained on an enormous dataset, of 11 million images and 1.1 billion masks, and it boasts impressive zero-shot performance on already a variety of segmentation tasks.
Foundation models such as this, which have shown promising advancements in NLP and, more recently, in computer vision, can carry out zero-shot learning. This means they can learn from new datasets and perform new tasks often by utilizing ’prompting’ techniques, even with little to no previous exposure to these tasks.
SAM’s ability to generalize across a wide range of objects and images makes it particularly appealing for Geographical Image applications.
<img src="Figs/SAM.png" alt="SAM">

# Table of Contents:
* <a href="#FM_Med">FM-Based Medical Image Segmentation
  * <a href="#Med">Medical Image Segmentation Related</a>
  * <a href="#VLM">VLM-Based Medical Image Segmentation Related</a>
  * <a href="#VLM_SAM">VLM SAM-Based Medical Image Segmentation Related</a>
* <a href="#FM_Geo">FM-Based Geographical Image Segmentation
  * <a href="#Geo">Geographical Image Segmentation Related</a>
  * <a href="#SAMGeo">SAM-based Geographical Segmentation Related</a>
  * <a href="#SAM">SAM-based approaches Related</a>
  * <a href="#techniques">Innovative Techniques</a>
* <a href="#Others">Others Related</a>

# FM-Based Medical Image Segmentation
## <div id="#Med"> </div>Medical Image Segmentation Related
The objective of medical image segmentation is to delineate anatomical or pathological structures within tissues, aiding in computer-assisted diagnostics and advanced surgical procedures.

* How to Efficiently Adapt Large Segmentation Model(SAM) to Medical Images <a href="https://arxiv.org/abs/2311.01908">paper</a>
* RO-LLaMA: Generalist LLM for Radiation Oncology via Noise Augmentation and Consistency Regularization <a href="https://arxiv.org/abs/2311.15876">paper</a>

## <div id="#VLM"> </div>VLM-Based Medical Image Segmentation Related
Traditionally, AI models have been tailored to process single data modalities, focusing either on visual or textual information. This singular approach stands in stark contrast to the inherently multi-modal method employed by medical practitioners, who rely on a combination of imaging studies and textual electronic medical records to make informed decisions.
* LLM-driven Multimodal Target Volume Contouring in Radiation Oncology <a href="https://arxiv.org/abs/2306.13731">paper</a>

## <div id="#VLM"> </div>VLM-Based Medical Image Segmentation Related
Using text prompts, SAM can adapt to VLM-based segmentation as well.
* Increasing SAM Zero-Shot Performance on Multimodal Medical Images Using GPT-4 Generated Descriptive Prompts Without Human Annotation <a href="https://arxiv.org/abs/2402.15759">paper</a>
* CLIP Surgery for Better Explainability with Enhancement in Open-Vocabulary Tasks <a href="https://arxiv.org/abs/2304.05653">paper</a>

# FM-Based Geographical Image Segmentation
## Problem:
<p class="justified-text">While extensive research has been dedicated to the segmentation of road infrastructure in geographical imagery like aerial and satellite pictures, there has been notably less emphasis on pedestrian infrastructure, such as sidewalks and crosswalks, despite its significant importance in our daily lives. Therefore, accurately segmenting both road and pedestrian infrastructures could yield valuable insights into accessible pedestrian pathways and trip destinations. This segmentation capability can effectively turned into creating a full-scalable pedestrian network.</p>
<img src="Figs/Segment.jpg" alt="Segment Pipeline">

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
* Learning Transferable Visual Models From Natural Language Supervision <a href="https://arxiv.org/pdf/2103.00020.pdf">link</a>
* Multi-Object Representation Learning via Feature Connectivity and Object-Centric Regularization <a href="https://openreview.net/pdf?id=BDno5qWEFh">link</a>

  
# <div id="#Others"></div>Others Related
These papers are other important works all related to our focus.
* An image is worth 16x16 words: Trans- 660 formers for image recognition at scale
* On the Opportunities and Risks of Foundation Models <a href="https://arxiv.org/abs/2108.07258">paper</a>
* On the effectiveness of parameter-efficient fine-tuning <a href="https://arxiv.org/abs/2211.15583">paper</a>
* Segment Everything Everywhere All at Once <a href="https://arxiv.org/abs/2304.06718">paper</a>
* Learning to Prompt Segment Anything Models <a href="https://arxiv.org/abs/2401.04651">paper</a>
* SurgicalSAM: Efficient Class Promptable Surgical Instrument Segmentation <a href="https://arxiv.org/abs/2308.08746">paper</a>


