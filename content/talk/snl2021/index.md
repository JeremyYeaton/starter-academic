---
title: Error detection and correction among adults with aphasia in a naming task
event: Thirteenth Annual Society for the Neurobiology of Language Meeting (2021)
event_url: https://www.neurolang.org/2021-meeting-information/

location: Virtual
#address:
#  street: 450 Serra Mall
#  city: Stanford
#  region: CA
#  postcode: '94305'
#  country: United States
projects: []
summary: Slide slam talk about picture naming deficits in adults with aphasia at SNL21.
abstract: "**Introduction.** Picture naming deficits are a common symptom of stroke-induced aphasia. The Philadelphia Naming Test (PNT; Roach et al. 1996) is a commonly used tool in assessment of such deficits. The test comprises 175 line-drawings of concrete imageable nouns, which a participant is asked to name out loud. The first and last (if more than one was made) naming attempt are recorded. A clinician codes the responses by type (e.g.: correct, semantically related, neologism). While previous research has primarily focused on the first complete response, by taking a closer look at secondary attempts to correct errors, we can gain insight into error detection and correction abilities in aphasia. In this work we examine what variables impact error detection (operationalized as whether an attempt to correct was made), and correction attempt outcomes in two cohorts of participants with aphasia. We find that rather than demographic variables, cognitive psychometric model parameters can best predict naming error detection and correction.\\

**Participants.** Our population includes a total of 156 participants across two cohorts for whom we had complete datasets (n=70 [31F, mean age=60.73 (11.7)] & n=86 [35F, mean age=60.79 (11.1)] respectively).\\

**Method.** For both groups, we had demographic variables (age at test, months post stroke, gender, ethnicity), clinical variables (aphasia type diagnosis, Western Aphasia Battery (WAB; Kertesz, 2006) aphasia quotient (AQ)) and modeled variables derived from a cognitive psychometric Multinomial Processing Tree (MPT; Walker et al. 2018) model of naming. For each participant, the MPT-Naming model outputs estimates of latent abilities critical to successful naming (Semantic, Lexical-Semantic, Lexical-Phonological, Lexical Selection, Phonological), estimated from the set of first complete attempts.
We fit a random forest classifier to identify which variables are useful in predicting a) whether a correction attempt was made after an error, and b) whether such an attempt was successful. Using a Boruta test on the classifier, we identified which variables contribute to classification accuracy (Kursa et al., 2010). We used a p-threshold of 0.01, and Gini impurity as our importance metric (D’Ambrosi & Tutore, 2011).\\

**Results.** We found that the Lexical-Semantic MPT parameter was the only significant predictor of whether a second attempt would be made, and, using only this predictor, 75.5% of out-of-bag items could be classified successfully (including all variables resulted in a 0.6% gain in accuracy). We found that the Semantic, Lexical-Phonological, and Phonological MPT parameters as well as the WAB AQ were significant predictors of second attempt success. This set of variables achieved 78.9% accuracy. Including the rest of the variables resulted in a 0.7% gain in accuracy.\\

**Discussion.** Different naming abilities, operating at different psycholinguistic levels of representation (lexical versus sublexical), were predictive of whether secondary naming attempts were made and whether they were successful. Neurobiological mechanisms underlying this cognitive dissociation are considered with respect to lesion patterns associated with the relevant abilities identified in previous work (Walker, 2019). Lexical-semantic abilities were associated with temporal regions (ventral stream) while phonological abilities were associated with auditory-motor and primary motor regions (dorsal stream) (Hickok & Poeppel, 2000).
"

# Talk start and end times.
#   End time can optionally be hidden by prefixing the line with `#`.
date: "2021-10-07"
date_end: "2021-10-09"
all_day: true

# Schedule page publish date (NOT talk date).
publishDate: "2021-07-20T00:00:00Z"

authors: [Jeremy Yeaton, Grant Walker, Julius Fridriksson, Gregory Hickok]
tags: [aphasia, naming, language]

# Is this a featured talk? (true/false)
featured: false

image:
  caption: ''
  focal_point: Right

links:
- icon: twitter
  icon_pack: fab
  name: Follow
  url: https://twitter.com/jeremyyeaton
url_code: ""
url_pdf: ""
url_slides: ""
url_video: "https://youtu.be/7WBzjf5_6jw"

# Markdown Slides (optional).
#   Associate this talk with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides = "example-slides"` references `content/slides/example-slides.md`.
#   Otherwise, set `slides = ""`.
slides: ""

# Projects (optional).
#   Associate this post with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `projects = ["internal-project"]` references `content/project/deep-learning/index.md`.
#   Otherwise, set `projects = []`.
# projects: []

# Enable math on this page?
math: true
---
