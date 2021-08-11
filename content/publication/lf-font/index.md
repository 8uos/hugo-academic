---
title: "Few-shot Font Generation with Localized Style Representations and Factorization"
authors:
- admin
- Sanghyuk Chun
- Junbum Cha
- Bado Lee
- Hyunjung Shim
author_notes:
- "Equal contribution"
- "Equal contribution"
date: "2021-02-01T00:00:00Z"
doi: ""


# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: in **AAAI Conference on Artificial Intelligence**
publication_short: in **AAAI 2021**

abstract: "Automatic few-shot font generation is in high demand because manual designs are expensive and sensitive to the expertise of designers. Existing methods of few-shot font generation aims to learn to disentangle the style and content element from a few reference glyphs and mainly focus on a universal style representation for each font style. However, such approach limits the model in representing diverse local styles, and thus make it unsuitable to the most complicated letter system, e.g., Chinese, whose characters consist of a varying number of components (often called 'radical') with a highly complex structure. In this paper, we propose a novel font generation method by learning localized styles, namely component-wise style representations, instead of universal styles. The proposed style representations enable us to synthesize complex local details in text designs. However, learning component-wise styles solely from reference glyphs is infeasible in the few-shot font generation scenario, when a target script has a large number of components, e.g., over 200 for Chinese. To reduce the number of reference glyphs, we simplify component-wise styles by a product of component factor and style factor, inspired by low-rank matrix factorization. Thanks to the combination of strong representation and a compact factorization strategy, our method shows remarkably better few-shot font generation results (with only 8 reference glyph images) than other state-of-the-arts, without utilizing strong locality supervision, e.g., location of each component, skeleton, or strokes."

tags:
- Few-shot Font Generation 
- Image to Image Translation
featured: false

links:
url_pdf: https://arxiv.org/pdf/2009.11042.pdf
url_code: https://github.com/clovaai/lffont

---
