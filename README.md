# agro-sage-official
# AgriSage — Smart Farmer Assistant

*Summary:* AgriSage is a multi-agent AI assistant to help smallholder farmers detect crop stress/disease from images and soil inputs, give fertilizer & irrigation recommendations, and fetch relevant government support schemes and weather-aware advice.

## What’s included
- AgriSage.ipynb — runnable Kaggle Notebook (core demo)
- data/soil_lookup.csv — soil guidance table
- data/govt_schemes.csv — curated sample scheme entries
- Demo images in data/images/
- submission_metadata.json — submission metadata

## How to reproduce (Kaggle)
1. Open this Notebook on Kaggle.  
2. Run cells top-to-bottom. (No external API key required for demo.)  
3. Replace the sample datasets with richer datasets if desired (PlantVillage, local govt CSVs).  
4. To use live weather: set get_weather_for_demo to call your weather API and set the key.

## Capabilities demonstrated
- Vision-based crop health classification
- Rule-based agro-planning combining soil and weather
- Tool use for retrieving government scheme information
- Memory (farm profile) and feedback logging
- Explainability via short textual reasons & confidence

## Evaluation
- Vision accuracy vs label baseline (toy dataset)
- Farmer usefulness score (1–5) from human evaluators
- Reproducibility: Notebook runs end-to-end without external keys

## Demo video
- 2-minute highlight (link) and 4-minute detailed walkthrough included in submission.

## Ethical considerations
- Not a medical/pesticide prescription. All recommendations are advisory; farmer must consult extension officer. We avoid recommending specific pesticide brand names to reduce risk. Data privacy: farm profiles are stored locally in the Notebook; for production, secure storage & consent required.

## Authors
Harsh Rajput — contact: (provide email)
