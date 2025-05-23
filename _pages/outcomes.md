---
layout: default
permalink: /outcomes/
title: outcomes
nav: true
nav_order: 5
description: Research Outcomes
---  

Research Outcomes
=================

- [**(2024) Final Synthesis Paper **](https://docs.google.com/document/d/15aTr_WXYRnajtCgIcs8IMolW8tqh6Uip4TQh1vHzy2Q/edit?tab=t.0) 
- **Final Oral Presentation**
    - [(October 2023) Hypothesis presentation](https://docs.google.com/presentation/d/1CDsA55o8sFG02upBSAxzTq8aTlUtTrOFWSS5--TUj94/edit?slide=id.g2931c4b04e5_0_3#slide=id.g2931c4b04e5_0_3)
    - [(Dec 2023–Jan 2024) Research progress presentation](https://docs.google.com/presentation/d/150d1rJTTvJBxkPsQ9s8d1vj8IAyOJkxbSaodsle5UJY/edit?slide=id.g2ab8278b649_0_0#slide=id.g2ab8278b649_0_0)
    - [(June 2024) Oral presentation to experts](https://docs.google.com/presentation/d/1r4K5rqA5f_LMFJiEie5LrcPH7z1lfADZo-tSFt84w24/edit?usp=sharing)
        
- **Final Products** (2024) 
    - [https://advikmrai.github.io/algoarias/](https://advikmrai.github.io/algoarias/)
    - [https://sites.google.com/view/algorithmicarias/home](https://sites.google.com/view/algorithmicarias/home)

Reflections
===========

**Creating the Paper**

The process of creating the paper has been a changing one, which started with an earlier draft based on the survey conducted in 10th grade, which included a literature review and survey data but did not cover the current methodology and code. My focus then shifted to a more advanced paper, initially envisioned as a methods paper, describing the method of creating the algorithm and application. This newer paper details the facial recognition app prototype, including methods sections and different data, specifically describing a novel application for music generation. It's considered an original research article because it describes data that has been generated. 

Significant effort has gone into revising and editing the paper based on feedback. This included restructuring the Methods section according to protocol paper guidelines, adding new diagrams and images, and rewriting the review of literature. Dr. Pantelyat and Dr. Kang provided extensive edits, suggesting adding a supplementary materials section and links to shared folders for the data files. There was also work on revising the abstract with minor wording edits, ensuring statements are supported by sources, and reformatting citations to follow guidelines like Vancouver style. Identifying potential target journals and their author guidelines, including word counts and reference limits, was part of the dissemination plan development. The goal of the paper is to set the table for future study and contribute to enhancing mental health and patient care. 


**Giving Presentations**

Giving presentations has been an important part of sharing the research progress. This has included preparing presentations for the Center for Music and Medicine (CMM) directors, preparing a separate slideshow for class presentations, practicing demonstrations of the application, and preparing media and slides for live presentations. These presentations are meant to summarize research progress and findings and explore potential collaborations and feedback.

**Data Collection**

<div class="col-sm-4 mt-3 mt-md-0" style="float: left;">
        {% include figure.liquid path="assets/img/data1.png" title="matplotlib1" class="img-fluid rounded z-depth-1" %}
    </div>

Generating and presenting the final product, a prototype system integrating Affective Algorithmic Composition (AAC) with Facial Expression Recognition (FER) technology, has involved significant development work. For me, it involved first working with Angular and then transitioning to React code, hosted on platforms like GitHub Pages and Google's Project IDX. Key development tasks involved working on the real-time data tracking system within the web app to continuously monitor and visualize emotional data, fixing and expanding the music player functionality, and addressing challenges like getting emotional readings to work on the main site. The prototype is intended to be capable of generating music based on the user's emotional state. As part of making the application usable for others, an instruction manual was created and made available online. Presenting the final product involves demonstrations of its functioning. The process has involved tackling significant technological challenges, but getting components functioning independently and then working towards pairing them has been a key step.  

<div class="col-sm-4 mt-3 mt-md-0" style="float: right;">
    {% include figure.liquid path="assets/img/code1.png" title="matplotlib1" class="img-fluid rounded z-depth-1" %}
</div>

Data collection and analysis are central to the project. The system uses the MorphCast Software Development Kit (SDK) to capture and analyze facial expressions, translating them into quantifiable emotional data. Data is captured frame-by-frame, and a highlight has been obtaining this frame-by-frame data in usable .json files. These files include timestamps, dominant emotion, and numeric values for various emotions, as well as information on gender, age, physical features, and crucially, track arousal, valence, and attention levels over time. Further analysis is performed offline to correlate emotional responses with the music. This involves using the .pyplot capability from the Python matplotlib library to generate charts. A major step forward was getting the PyTorch music analyzer working to output results for music files, allowing for the quantifiable analysis of the relationship between facial expressions and music. This also involved hard-coding musical components and incorporating more musical components like timbre, chords, and melodies. A significant challenge was figuring out how to synchronize the audio data from music with the facial expression data at corresponding timestamps. While the current approach uses facial recognition, there is a consideration for incorporating objective physiological measures like EEG or fMRI in future research to compare findings.


**2024 Final Synthesis Paper**
<iframe src="https://advikmrai.github.io/ir-portfolio/assets/pdf/2024Paper.pdf" width="100%" height="500px" style="border:none;"></iframe>

<br>

**Hypothesis Presentation Slides**
<iframe src="https://advikmrai.github.io/ir-portfolio/assets/pdf/HypSlides.pdf" width="100%" height="500px" style="border:none;"></iframe>

<br>

**Research Progress Slides**
<iframe src="https://advikmrai.github.io/ir-portfolio/assets/pdf/ProgressSlides.pdf" width="100%" height="500px" style="border:none;"></iframe>

<br>

**June 2024 Slides**
<iframe src="https://advikmrai.github.io/ir-portfolio/assets/pdf/Juneslides.pdf" width="100%" height="500px" style="border:none;"></iframe>
