---
layout: guideline
---

These guidelines provide the three different types of information that should be annotated for our gold standards. Our team members will review the annotations and use them to evaluate our automatic pipeline, mapKurator.
The three steps include 1) creating bounding boxes, 2) transcribing the text, and 3) linking to the corresponding entity in external knowledge bases. We encourage annotators to go through and follow our annotation guidelines for generating high-quality gold standards. 

## 1. Creating bounding boxes

A mix of bounding boxes and bounding polygons for annotation, always use the simpler form if appropriate.
- First choice: axis-aligned bounding box (horizontal/vertical text labels) 
- Second choice: rotated bounding box (rotated text labels)
- Third choice: bounding polygon (curved text labels, e.g. river name)

If spacing between words or characters is larger than the font size, then annotate each character instead of the whole word/phrase. Please use your own judgement in deciding bounding polygons. 


## 2. Transcribing the text

We rely on human intelligence.


## 3. Linking to corresponding entity in external knowledge bases
