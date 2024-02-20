# LLM Project
<h2 align="center">
Documents Summarization APP using LaMini LLM from MBZUAI<br/>
</h2>
<hr>

## Table of Contents
1. [General Info](#general-information)
2. [Creator Info](#creator-information)
3. [Features](#features)
4. [Technologies Used](#technologies-used)
5. [Setup](#setup)
6. [Usage](#usage)
7. [Video Capture](#videocapture)
8. [Screenshots](#screenshots)
9. [Structure](#structure)
10. [Project Status](#project-status)
11. [Room for Improvement](#room-for-improvement)
12. [Acknowledgements](#acknowledgements)
13. [Contact](#contact)

<a name="general-information"></a>

## General Information
A summarization app that build with streamlit and write in python. I used a [LLM from MBZUAI](https://huggingface.co/MBZUAI/LaMini-Flan-T5-248M/tree/main). This app will accept a document in PDF format and summarize it using the model. Hopefully, this project could help all of your college tasks 🤣.

<a name="creator-information"></a>

## Creator Information
| Nama                        | NIM      | E-Mail                      |
| --------------------------- | -------- | --------------------------- |
| Mohammad Rifqi Farhansyah   | 13521166 | 13521166@std.stei.itb.ac.id |

<a name="features"></a>

## Features
- Read `document` in PDF format
- User could `summarize` their document by clicking the `summary` button

<a name="technologies-used"></a>

## Technologies Used
- langchain: v0.0.284
- sentence_transformers: v2.2.2
- torch: v2.2.0
- sentencepiece: v0.1.99
- transformers: v4.37.2
- accelerate: v0.27.2
- chromadb: v0.4.22
- pypdf2: vnot installed
- tiktoken: v0.4.0
- streamlit: v1.22.0
- fastapi: v0.109.2
- uvicorn: v0.27.1
- python-multipart: v0.0.9
- aiofiles: v23.2.1

> Note: The version of the libraries above is the version that we used in this project. You can use the latest version of the libraries.

<a name="setup"></a>

## Setup
1. Install all of the requirements above. You can use this command:
```bash
pip install -r requirements.txt
```
2. Clone this repository using command below:
```bash
git clone https://github.com/rifqifarhansyah/LaMiniLLMSummarization.git
```
3. Clone the `LaMini` repository inside this repo's directory.
4. Make an `offload folder`.

<a name="usage"></a>

## Usage
1. Run the program using the command below:
```bash
streamlit app.py
```
2. If the program was loaded with errors, just tried to refresh the browser multiple times.
    
<a name="videocapture"></a>

## Video Capture
<nl>

![LaMiniLLMSummarization Gif](https://github.com/rifqifarhansyah/LaMiniLLMSummarization/blob/main/img/LaMiniLLMSummarization.gif?raw=true)

<a name="screenshots"></a>

## Screenshots
<p>
  <img src="/img/SS1.png/">
  <p>Figure 1. Landing Page</p>
  <nl>
  <img src="/img/SS2.png/">
  <p>Figure 2. Upload PDF</p>
  <nl>
  <img src="/img/SS3.png/">
  <p>Figure 3. Read PDF and Summarization Process</p>
  <nl>
  <img src="/img/SS4.png/">
  <p>Figure 4. Result</p>
  <nl>
</p>

<a name="structure"></a>

## Structure
```bash
│   app.py
│   README.md
│   requirements.txt
│
├───.venv
├───data
│       AI_blog.pdf
│       Document1.pdf
│
├───img
│       SS1.png
│       SS2.png
│       SS3.png
│       SS4.png
│
└───LaMiniFlan-T5-248M
        .gitattributes
        .gitignore
        config.json
        generation_config.json
        pytorch_model.bin
        README.md
        special_tokens_map.json
        spiece.model
        tokenizer.json
        tokenizer_config.json
        training_args.bin
```

<a name="project-status">

## Project Status
Project is: _complete_

<a name="room-for-improvement">

## Room for Improvement
Room for Improvement:
- Optimizing the accuracy of the model by doing a fine tune process
- Beautify the UI

<a name="acknowledgements">

## Acknowledgements
- Thanks To Allah SWT

<a name="contact"></a>

## Contact
<h4 align="center">
  Contact Us : mrifki193@gmail.com<br/>
  2024
</h4>
<hr>
