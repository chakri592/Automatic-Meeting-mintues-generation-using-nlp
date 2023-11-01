# Meeting Minutes Generation with NLP

In recent years, online meetings have become a significant component of communication in a variety of organizations. To optimize the generation of meeting minutes, this project proposes a novel approach based on Natural Language Processing (NLP).

## Overview

This project aims to automate the process of speech recognition, key point extraction, meeting summarization, and action item extraction. The approach begins with extracting text from a meeting that is provided in transcript or audio format. It utilizes state-of-the-art summarization models such as BART (Bidirectional Auto-Regressive Transformers), T5 (Text-to-Text Transformer Model), and a Summarization Pipeline to create concise meeting minutes.

## Features

- Automated speech recognition from audio or transcript.
- Key point extraction for important topics discussed.
- Meeting summarization for a concise overview.
- Action item extraction for follow-up tasks.

## Usage

1. **Data Input**: Provide the meeting data in transcript or audio format.
2. **Run the NLP Models**: Utilize the included NLP models (BART, T5, Summarization Pipeline) to process the data.
3. **Output**: The project generates meeting minutes in the form of text.

## Installation

1. Clone the repository:

   ```bash
   git clone https://github.com/chakri592/Automatic-Meeting-mintues-generation-using-nlp.git
   cd meeting-minutes-nlp
