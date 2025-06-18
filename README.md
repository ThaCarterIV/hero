# Hero Comic Generator

A Streamlit app that lets you create unique superheroes, generate comic-style images, and write an ongoing story.

## Installation

```bash
pip install streamlit openai pillow requests
```

## Environment Setup

Set your OpenAI API key so the app can access OpenAI's services:

```bash
export OPENAI_API_KEY=YOUR_KEY
```

## Run the App

```bash
streamlit run main_code
```

## How It Works

- **Hero generation** uses GPT to craft a new hero profile.
- **Story continuation** expands the narrative using previous summaries.
- All data is stored in `comic_data/`:
  - `heroes.json` for hero info
  - `images/` for generated portraits
  - `summaries/` for chapter summaries
