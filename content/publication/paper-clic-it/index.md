---
title: "Constructing EPTIC: A Modular Pipeline and an Evaluation of ASR for Verbatim Transcription"
authors:
- admin
- Adriano Ferraresi
- Maja Miličević Petrović
- Alberto Barrón-Cedeño

#author_notes:
#- "Equal contribution"
#- "Equal contribution"

date: "2024-12-06T00:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).
# publishDate: "2017-01-01T00:00:00Z"

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ["paper-conference"]

# Publication name and optional abbreviated publication name.
publication: "In *CLiC-it 2024 – Tenth Italian Conference on Computational Linguistics*"
publication_short: "In *CLiC-it 2024 – Tenth Italian Conference on Computational Linguistics*"

abstract: This paper presents a novel pipeline for constructing multimodal and multilingual parallel corpora, with a focus on evaluating state-of-the-art automatic speech recognition tools for verbatim transcription. Our findings indicate that current technologies can streamline corpus construction, with fine-tuning showing promising results in terms of transcription quality compared to out-of-the-box Whisper models. 

# Summary. An optional shortened abstract.
summary: This paper presents a novel pipeline for constructing multimodal and multilingual parallel corpora, with a focus on evaluating state-of-the-art automatic speech recognition tools for verbatim transcription. Our findings indicate that current technologies can streamline corpus construction, with fine-tuning showing promising results in terms of transcription quality compared to out-of-the-box Whisper models. 

tags:
- Automatic Speech Recognition
featured: true

# links:
# - name: ""
#   url: ""
url_pdf: https://ceur-ws.org/Vol-3878/41_main_long.pdf
url_code: 'https://github.com/ffedox/eptic-pipeline-2025'
url_dataset: 'https://corpora.dipintra.it/eptic/'
url_poster: ''
url_project: ''
url_slides: ''
url_source: ''
url_video: ''

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
image:
  caption: 'Image credit: [**AILC**](https://clic2024.ilc.cnr.it/)'
  focal_point: ""
  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
projects: []

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
slides: example
---

### Constructing a Multimodal, Multilingual Translation and Interpreting Corpus: A Modular Pipeline and an Evaluation of ASR for Verbatim Transcription

**Alice Fedotova**  
Department of Interpreting and Translation
University of Bologna  

**Adriano Ferraresi**  
Department of Interpreting and Translation
University of Bologna 

**Maja Miličević Petrović**  
Department of Interpreting and Translation
University of Bologna 

**Alberto Barrón-Cedeño**  
Department of Interpreting and Translation
University of Bologna 

#### Abstract

This paper presents a novel pipeline for constructing multimodal and multilingual parallel corpora, with a focus on evaluating
state-of-the-art automatic speech recognition tools for verbatim transcription. The pipeline was developed during the process
of updating the European Parliament Translation and Interpreting Corpus (EPTIC), leveraging recent NLP advancements to
automate challenging tasks like multilingual alignment and speech recognition. Our findings indicate that current technologies
can streamline corpus construction, with fine-tuning showing promising results in terms of transcription quality compared to
out-of-the-box Whisper models. The lowest overall WER achieved for English was 0.180, using a fine-tuned Whisper-small
model. As for Italian, the lowest WER (0.152) was obtained by the Whisper Large-v2 model, with the fine-tuned Whisper-small
model still outperforming the baseline (0.201 vs. 0.219).

**Keywords:** multimodal corpora construction, translation and interpreting corpora, verbatim automatic speech recognition