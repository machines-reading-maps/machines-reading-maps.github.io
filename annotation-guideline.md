---
layout: guideline
---

These guidelines provide the three different types of information that should be annotated for our gold standards. We will use gold standards to test and evaluate our machine learning pipeline, mapKurator, which aims to detect and recognize texts on map images automatically, and link entities in external knowledge bases.

The annotation procedure includes the following three steps: 1) creating bounding boxes, 2) transcribing the text, and 3) linking to external knowledge bases. We encourage annotators to go through and follow our annotation guidelines for generating high-quality gold standards. 


## 1. Creating bounding boxes

You can use a mix of bounding boxes and bounding polygons for annotation by following the straightforward form.
- First choice: axis-aligned bounding box (horizontal/vertical text labels) 
- Second choice: rotated bounding box (rotated text labels)
- Third choice: bounding polygon (curved text labels, e.g., river name)

(GIF image of Recogito interface)

If the spacing between words or characters is larger than the font size, annotate each character instead of the whole word/phrase and group them. Please use your judgment for determining appropriate choice. 

(Sample images in incorrect or correct way)

## 2. Transcribing the text

Transcribe the exact text in bounding boxes or bounding polygons. Please follow the same form as it appears either in lower or upper cases.

(GIF image of Recogito interface)

## 3. Linking to external knowledge bases
