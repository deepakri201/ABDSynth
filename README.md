# ABDSynth

This repository accompanies the journal submission of **"Benchmarking of AI Algorithms for MRI Abdominal Segmentation"**, with authors Deepa Krishnaswamy*, Cosmin Ciausu*, Benjamin Billot, Steve Pieper, Ron Kikinis, Andrey Fedorov. (*shared first author)

---

**In this repository, we:**
1) Provide the model weights for *ABDSynth*, which is a model based on SynthSeg (https://github.com/BBillot/SynthSeg) trained using abdominal data, and
2) Provide a demo notebook to run inference on a sample dataset using *ABDSynth*

Further instructions for the demo notebook: 
1) Please install SynthSeg (https://github.com/BBillot/SynthSeg) for python 3.8
2) Additionally, install Simple ITK

---

**In this publication, we:**
- Perform a benchmarking study of four state-of-the-art algorithms for segmentation of abdominal structures in MR images, including three pre-trained models, and another that we train, termed *ABDSynth*
- Perform an analysis on three different datasets containing both normal and pathological cases of a variety of MR sequence types 

Example figure from our publication: 

*Examples of segmentation performance for AMOS MR, with ground truths in green, and methods' segmentations in blue. (a) Pancreas slice, where all of the automated methods do not fully segment the region. (b) 3D renderings 
for a sample patient. Arrows indicate some examples of over and under-segmentation by multiple methods.*

![](https://github.com/user-attachments/assets/f69ee0d8-389c-40a9-b804-0d981d14f4a3)

For further information, please see a previous version of an arXiv paper: 

> Ciausu C, Krishnaswamy D, Billot B, Pieper S, Kikinis R, Fedorov A. Towards Automatic Abdominal MRI Organ Segmentation: Leveraging Synthesized Data Generated From CT Labels. arXiv preprint arXiv:2403.15609. 2024 Mar 22. https://arxiv.org/abs/2403.15609 
