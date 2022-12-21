This notebook aims to demonstrate my bridge knowledge between Ophthalmology and Computer Vision.  The software sample apply filters to improve ophthalmological images, and another code analyzes medical texts. The codes are mere prototypes without clinical validation.

# Imaging Filters
An image filter is a technique through which size, colors, shading and other characteristics of an image are altered.

## Imaging Filters applied to Medical images
Image filtering techniques have numerous potential applications in biomedical imaging and image processing. The design of filters largely depends on the a priori, knowledge about the type of noise corrupting the image. This makes the standard filters application specific.

## Imaging Filters and Ophthalmology
Ophthalmology has used image filters since its inception.
From the cobalt blue filter in slit lamps to the modern noise reduction techniques in OCT.
The need to observe the ocular anatomy through structures that are not always transparent makes these techniques essential.

## This notebook
In this notebook, the CLAHE and RED FREE filters are demonstrated, as well as a brightness optimization filter with Deep Learning.

https://github.com/rschererstm/wisconsin_opht/blob/main/retina_filters.ipynb



# Text Processing
Natural Language Processing (NLP) is a very important component for its vast applications in various industries/sectors. NLP is the technique that enables the machines to interpret and to understand the way humans communicate.
Natural languages are a free form of text which means it is very much unstructured in nature. So, cleaning and preparing the data to extract the features are very important for the NLP journey.

## Medical Text processing
Clinical NLP is a specialization of NLP that allows computers to understand the rich meaning that lies behind a doctor's written analysis of a patient. Normal NLP engines use large corpora of text, usually books or other written documents, to determine how language is structured and how grammar is formed.

## Ophthalmology and NLP
In ophthalmology, several documents are produced, from medical records and prescriptions to descriptive reports of medical images. We use our terminology.
Thus custom tools are needed for this.

## This notebook
This notebook takes a first step in that direction. It prepares the text for deeper semantic analysis.

https://github.com/rschererstm/wisconsin_opht/blob/main/text_pipeline.ipynb
