---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: "Machine Learning Pipeline for microbiome data"
summary: "Create a reproducible, user-friendly and open-source ML pipeline."
authors: [Begüm D. Topçuoglu and Zena Lapp]
tags: [reproducible workflow]
categories: []
date: 2019-11-13T23:02:29-05:00

# Optional external URL for project (replaces project detail page).
external_link:

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
# Focal points: Smart, Center, TopLeft, Top, TopRight, Left, Right, BottomLeft, Bottom, BottomRight.
image:
  caption: ""
  focal_point: ""
  preview_only: false

# Custom links (optional).
#   Uncomment and edit lines below to show custom links.
# links:
# - name: Follow
#   url: https://twitter.com
#   icon_pack: fab
#   icon: twitter

url_code: "https://github.com/SchlossLab/Topcuoglu_ML_XXX_2019"
url_pdf: ""
url_slides: ""
url_video: ""

# Slides (optional).
#   Associate this project with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides = "example-slides"` references `content/slides/example-slides.md`.
#   Otherwise, set `slides = ""`.
slides: ""
---

Machine learning is a set of methods that allow computers to learn from existing data and make predictions on new data.

Machine learning models are programs learned by the computer. They predict which Amazon product you will buy next, how much value Bitcoin will lose in the coming month or when the cherry blossoms will peak in Washington DC.

__ML models are now being used to make high stake decisions by:__

- The judicial system to make parole decisions.
- Weather forecasts to predict air quality.
- The financial system to decide who gets a loan.
- Hospitals to automoate interpretation of the EKGs and detection of a lung nodules from chest X-rays.

__Can we use ML models in the microbiome field?__

Microbiome field is growing at an unprecedented rate.
There is an increasing demand for methods that identify associations between members of the microbiome and their ecosystem such as an animal host or a soil habitat.

It is unlikely that a single species can explain the change we see in an ecosystem. Instead, subsets of those communities, in relation to one another and to their environment account for that.

Machine learning (ML) methods are effective at recognizing and highlighting patterns in complex microbial datasets. Therefore, researchers have started to explore the utility of ML models that use microbiome associated biomarkers to predict changes in an ecosystem using ML such as:

- Modeling soil microbiome to predict crop productivity.
- Modeling muman microbiome to detect colorectal cancer or a Clostridium difficile infection.

__Problems with ML in the microbiome field__

- It is great that we are using new tools to understand microbial systems however, currentlythe field’s use of ML lacks clarity and consistency on which methods are used and how these methods are implemented.

- There is a trend towards using more complex ML models such as random or neural networks without a discussion on if this is necessary for the goals of a study.

- The lack of transparency on modeling methodology and model selection negatively impact model reproducibility and reliability.

__We need to strive toward better machine learning practices by:__

1. Implementing consistent, accessible and transparent machine learning methods.
2. Selecting ML models that reflect the goal of the study.

__Goals of this project__

Provide an open-source, reproducible and user-friendly ML pipeline for microbial ecologists to use.
