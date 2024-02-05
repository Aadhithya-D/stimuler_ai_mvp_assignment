# Stimuler AI Lip Sync MVP
Problem Statement: Create a conversational 3D model powered by AI that can lip sync.

[Notion Doc](https://aadhithya-d.notion.site/aadhithya-d/Stimuler-AI-Assignment-MVP-6e650f7354c04753ab9574fed2cbfd00)

## Setup
Create a `.env` file at the root of the repository to add your **OpenAI** and **ElevenLabs API Keys**. Refer to `.env.example` for the environment variable names.

Install ffmpeg in mac with `brew install ffmpeg`

Download the **RhubarbLibrary** binary for your **OS** [here](https://github.com/DanielSWolf/rhubarb-lip-sync/releases) and put it in your `bin` folder. `rhubarb` executable should be accessible through `bin/rhubarb`.

Start the development server with
```
yarn
yarn dev
```
