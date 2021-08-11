---
title: "Semantic-aware Neural Style Transfer"
authors:
- Joo Hyun Park
- admin
author_notes:
- "Equal contribution"
- "Equal contribution"
date: "2019-02-01T00:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2017-01-01T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["2"]

# Publication name and optional abbreviated publication name.
publication: "**Image and Vision Computing**"
publication_short: "**IMAVIS 2019**"

abstract: This study proposes a semantic-aware style transfer method for resolving semantic mismatch problems in existing algorithms. As the primary focus of this study, the consideration of semantic matching is expected to improve the quality of artistic style transfer. Here, each image is partitioned into several semantic regions for both a target photograph and a source painting. All partitioned regions of the target are then associated with one of the partitioned regions in the source according to their semantic interpretation. Given a pair of target and source regions, style is learned from the source region whereas content is learned from the target region. By integrating both the style and content components, we can successfully generate a stylized output. Unlike previous approaches, we obtain the best semantic match between regions using word embeddings. Thus, we guarantee that semantic matching is always established between the target and source. Moreover, it is unreliable to partition a painting using existing algorithms because of statistical gaps between the real photographs and paintings. To bridge such gaps, we apply a domain adaptation technique on the source painting to extract its semantic regions. We evaluated the effectiveness of the proposed algorithm based on a thorough experimental analysis and comparison. Through a user study, it is confirmed that semantic information considerably influences the quality assessment of style transfer.

tags:
- Style Transfer
featured: false
---
