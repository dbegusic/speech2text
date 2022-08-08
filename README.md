# speech2text
<hr>
<a style="float:left;" href="https://www.neos.hr/news-neos/"><img src="https://img.shields.io/badge/Neos-32b5c4.svg?style=for-the-badge"/></a>
<a style="float:left;" href="https://hr.linkedin.com/company/neos-hr/"><img src="https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white"/></a>
<a style="float:left;" href="https://twitter.com/neos_hr"><img src="https://img.shields.io/badge/Twitter-1DA1F2?style=for-the-badge&logo=twitter&logoColor=white"/></a>
<a style="float:left;" href="https://www.facebook.com/neos.hr"><img src="https://img.shields.io/badge/Facebook-1877F2?style=for-the-badge&logo=facebook&logoColor=white"/></a>
<br>
<br>
<br>
A case study of automatic speech recognition (ASR) in Croatian using pretrained deep learning ASR model.

After demonstrating the approach to the problem of pre-processing the raw audio input and getting trascription, closed captioning and construction of word cloud use-cases are shown using most recent Croatian NLP support to date.

The abovementioned and more is elaborated and described in the Neos Ltd. tech blog available at [Blog-post-TBA](https://neos.hr).

<br>

<img src="data/banner.png" width="600"/>

## Content
<hr>

    ├── data
    │   ├── chunks                    <- Directory where all the calculated audio chunks are located
    │   ├── chunks_normalized         <- Directory where all the normalized audio chunks are located
    │   ├── VRH-121 - 27.05.2022.wav  <- Audio input example
    │   ├── VRH-121 - 27.05.2022.srt  <- Output of closecaptioning.ipynb
    │   ├── banner.png                <- Banner for this project
    │   ├── cc_demo.gif               <- Demonstration of playing the audio example with the generated .srt
    │   ├── cc_tmp.wav                <- Temporary 2500 ms chunk of audio for closecaptioning.ipynb
    │   ├── cloud_mask.png            <- Image that represents the mask for generated WordCloud object
    │   └── neos_logo.png             <- Neos Ltd. logo image
    │
    ├── LICENSE
    ├── README.md
    │
    ├── audioprocessing.ipynb         <- Jupyter notebook for audio input processing and transcribing
    ├── closedcaptioning.ipynb        <- Jupyter notebook for audio input processing and generating .srt file
    ├── requirements.txt              <- All Python libraries that notebooks depend on
    ├── transcription.txt             <- Output of audioprocessing.ipynb, input for wordcloud.ipynb
    ├── transcription_normalized.txt  <- Output of audioprocessing.ipynb, after normalizing audio to -3dB 
    └── wordcloud.ipynb               <- Jupyter notebook for transcription processing using NLP methods and   
                                         generating word cloud image.

## Resources
<hr>

- [Blog-post-TBA](https://neos.hr)
- [CLASSLA Huggingface site](https://huggingface.co/classla)
- [CLASSLA Python package](https://github.com/clarinsi/classla)
- [WordCloud Python package](https://github.com/amueller/word_cloud)
- [Croatia Gov't sessions](https://vlada.gov.hr/sjednice/9)
