---
title: "personality detection using bagged SVM over BERT word embedding ensembles"
authors:
- admin
- Samin Fatehi
- Yash Mehta
- Sauleh Eetemadi
- Erik Cambria
date: "2020-07-13T00:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2017-01-01T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: In *[Proceedings of the The Fourth Widening Natural Language Processing Workshop](www.winlp.org/winlp-2020-workshop/)*
publication_short: In *WiNLP 2020*

abstract: Recently, the automatic prediction of personality traits has received increasing attention and has emerged as a hot topic within the field of affective computing. In this work, we present a novel deep learning-based approach for automated personality detection from text. We leverage state of the art advances in natural language understanding, namely the BERT language model to extract contextualized word embeddings from textual data for automated author personality detection. Our primary goal is to develop a computationally efficient, high performance personality prediction model which can be easily used by a large number of people without access to huge computation resources. Our extensive experiments with this ideology in mind, led us to develop a novel model which feeds contextualized embeddings along with psycholinguistic features to a Bagged-SVM classifier for personality trait prediction. Our model outperforms the previous state of the art by 1.04% and, at the same time is significantly more computationally efficient to train. We report our results on the famous gold standard Essays dataset for personality detection.

# Summary. An optional shortened abstract.
summary: A novel model which feeds contextualized embeddings along with psycholinguistic features to a Bagged-SVM classifier for personality trait prediction. This model outperforms the previous state of the art by 1.04% and, at the same time is significantly more computationally efficient to train.

tags:
- Personality detection
- Deep learning
- Language model
- Computational psychology
- Natural language understanding
featured: true

links:
url_pdf: http://www.winlp.org/wp-content/uploads/2020/final_papers/40_Paper.pdf
url_code: 'https://github.com/amirmohammadkz/personality_detection'
url_dataset: 'https://github.com/amirmohammadkz/personality_detection/blob/main/essays_original_splitted.csv'
url_poster: ''
url_project: ''
url_slides: ''
url_source: ''
url_video: ''

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
image:
  caption: 'Accuracy of BB-SVM model with different BERT layer inputs compared to the accuracy of this model with the concatenation of the last four layers'
  focal_point: ""
  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
projects: []
---
