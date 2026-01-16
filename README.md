# DysarthricSpeechProject

Local project for dysarthric speech recognition experiments.

## Repo rules
- Do not commit datasets (UASpeech, LibriSpeech cache).
- Put UASpeech under: `data/raw/uaspeech/`
- Hugging Face cache under: `data/hf_cache/`

## Setup
- Create a virtual environment (recommended)
- Install requirements:
  - `pip install -r requirements.txt`

## Notebooks
- `notebooks/01_librispeech_explore.ipynb`
- `notebooks/02_uaspeech_explore.ipynb`
- `notebooks/03_audio_features_mfcc.ipynb`
