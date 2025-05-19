# AI Translator Web App
This repository provides a server-side implementation of a simple speech-enabled translation assistant powered by IBM Watson services. It transcribes English ( Or spanish ) audio, translates the text to Spanish ( Or English ) using a foundation model via IBM watsonx, and returns both the translated text and TTS speech.

## Overview
This application allows users to:

Speak an English/Spanish sentence.

Have it transcribed to text using Watson Speech-to-Text.

Translated to Spanish/English using the FLAN-UL2 foundation model from watsonx.

Returned both as written text and spoken Spanish/English audio using Watson Text-to-Speech.

The server exposes two main endpoints and supports interaction with a fullstack frontend (included as a .tar archive).

## Features
Speech Input: Users can speak directly to the interface using a microphone.

Natural Language Translation: Leveraging watsonx FLAN-UL2 foundation model for translating English sentences to Spanish.

Multimodal Output: Provides both textual and synthesized audio output of the translation.

API Integration: Interfaces with Watson's Speech-to-Text, Text-to-Speech, and foundation model APIs via IBM Cloud.

## 🧑‍💻 Full Stack Bot Interface
If you're looking for the full chatbot application (UI, server, deployment, etc.), please check the included zipped archive

It contains everything you need to run the complete bot interface on top of this worker engine. Credits for the fullstack: [https://github.com/sinanazeri/build_own_chatbot_without_open_ai](https://github.com/ibm-developer-skills-network/translator-with-voice-and-watsonx)

## 🛠 Requirements
See requirements.txt in this repo.

## 🧾 License
This project is licensed under the GNU General Public License v3.0 (GPL-3.0). See the LICENSE file for more details.

## 🤝 Acknowledgments

Special thanks for IBM's courses that taught me all these fascinating technologies and how to implement them in meaningful projects

Thanks to the developers of LangChain, IBM Watsonx, HuggingFace, ChromaDB, and PyPDFLoader for their open tools and models.

Fullstack: [https://github.com/sinanazeri/build_own_chatbot_without_open_ai](https://github.com/ibm-developer-skills-network/translator-with-voice-and-watsonx)
