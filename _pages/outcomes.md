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

- **Final Synthesis Paper** (2024)
    - https://docs.google.com/document/d/15aTr_WXYRnajtCgIcs8IMolW8tqh6Uip4TQh1vHzy2Q/edit?tab=t.0
- **Final Oral Presentation** 
    - (October 2023) Hypothesis presentation https://docs.google.com/presentation/d/1CDsA55o8sFG02upBSAxzTq8aTlUtTrOFWSS5--TUj94/edit?slide=id.g2931c4b04e5_0_3#slide=id.g2931c4b04e5_0_3
    - (Dec 2023–Jan 2024) https://docs.google.com/presentation/d/150d1rJTTvJBxkPsQ9s8d1vj8IAyOJkxbSaodsle5UJY/edit?slide=id.g2ab8278b649_0_0#slide=id.g2ab8278b649_0_0
    - ISEF Afilliated Slides (3/15/2025) https://docs.google.com/presentation/d/1Q8Kc9PYuzVGudYrvPVaLp3pVNDcbuplonfc6pOoZAZY/edit#slide=id.gb25f3add1a_0_0
    - SLC Presentation (4/25/2025)
    https://docs.google.com/presentation/d/1-4zc2FVmIlAkWDRvYIHd8Y-C7iRto0HuyhlvxI0rweA/edit#slide=id.g34fba627805_7_0
        
- **Final Product** (2024) 
    - https://advikmrai.github.io/algoarias/
    - https://sites.google.com/view/algorithmicarias/home


The process of creating the paper has been a changing one, which starting with an earlier draft based on the survey conducted in 10th grade, which included a literature review and survey data but did not cover the current methodology and code. My focus then shifted to a more advanced paper, initially envisioned as a methods paper, describing the method of creating the algorithm and application. This newer paper details the facial recognition app prototype, including methods sections and different data, specifically describing a novel application for music generation. It's considered an original research article because it describes data that has been generated. 

Significant effort has gone into revising and editing the paper based on feedback. This included restructuring the Methods section according to protocol paper guidelines, adding new diagrams and images, and rewriting the review of literature. Dr. Pantelyat and Dr. Kang provided extensive edits, suggesting adding a supplementary materials section and links to shared folders for the data files. There was also work on revising the abstract with minor wording edits, ensuring statements are supported by sources, and reformatting citations to follow guidelines like Vancouver style. Identifying potential target journals and their author guidelines, including word counts and reference limits, was part of the dissemination plan development. The goal of the paper is to set the table for future study and contribute to enhancing mental health and patient care. 

Giving presentations has been an important part of sharing the research progress. This has included preparing presentations for the Center for Music and Medicine (CMM) directors, preparing a separate slideshow for class presentations, practicing demonstrations of the application, and preparing media and slides for live presentations. These presentations are meant to summarize research progress and findings and explore potential collaborations and feedback.
Generating and presenting the final product, a prototype system integrating Affective Algorithmic Composition (AAC) with Facial Expression Recognition (FER) technology, has involved significant development work. For me, it involved first working with Angular and then transitioning to React code, hosted on platforms like GitHub Pages and Google's Project IDX. Key development tasks involved working on the real-time data tracking system within the web app to continuously monitor and visualize emotional data, fixing and expanding the music player functionality, and addressing challenges like getting emotional readings to work on the main site. The prototype is intended to be capable of generating music based on the user's emotional state. As part of making the application usable for others, an instruction manual was created and made available online. Presenting the final product involves demonstrations of its functioning. The process has involved tackling significant technological challenges, but getting components functioning independently and then working towards pairing them has been a key step. 

Data collection and analysis are central to the project. The system uses the MorphCast Software Development Kit (SDK) to capture and analyze facial expressions, translating them into quantifiable emotional data. Data is captured frame-by-frame, and a highlight has been obtaining this frame-by-frame data in usable .json files. These files include timestamps, dominant emotion, and numeric values for various emotions, as well as information on gender, age, physical features, and crucially, track arousal, valence, and attention levels over time. Further analysis is performed offline to correlate emotional responses with the music. This involves using the .pyplot capability from the Python matplotlib library to generate charts. A major step forward was getting the PyTorch music analyzer working to output results for music files, allowing for the quantifiable analysis of the relationship between facial expressions and music. This also involved hard-coding musical components and incorporating more musical components like timbre, chords, and melodies. A significant challenge was figuring out how to synchronize the audio data from music with the facial expression data at corresponding timestamps. While the current approach uses facial recognition, there is a consideration for incorporating objective physiological measures like EEG or fMRI in future research to compare findings.


**2024 Final Synthesis Paper**
<iframe src="https://advikmrai.github.io/ir-portfolio/assets/pdf/2024Paper.pdf" width="100%" height="500px" style="border:none;"></iframe>


**Hypothesis Presentation Slides**
<iframe src="https://advikmrai.github.io/ir-portfolio/assets/pdf/HypSlides.pdf" width="100%" height="500px" style="border:none;"></iframe>

**Research Progress Slides**
<iframe src="https://advikmrai.github.io/ir-portfolio/assets/pdf/ProgressSlides.pdf" width="100%" height="500px" style="border:none;"></iframe>

**ISEF Fair Slides**
<iframe src="https://advikmrai.github.io/ir-portfolio/assets/pdf/ISEFSlides.pdf" width="100%" height="500px" style="border:none;"></iframe>

**SLC Conference Slides**
<iframe src="https://advikmrai.github.io/ir-portfolio/assets/pdf/SLCSlides.pdf" width="100%" height="500px" style="border:none;"></iframe>