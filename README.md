# AgroSat Monitor

Satellite-powered crop health monitoring and irrigation advisory system using Sentinel-2 NDVI/moisture data, built for ISRO Bharatiya Antariksh Hackathon 2026 (Theme 6) by Team Vikrama, Sanjivani College of Engineering, Kopargaon.

## Live Dashboard
https://om2536l.github.io/agrosat-ai/

## Structure
- `docs/` — PWA dashboard (frontend)
- `pipeline/` — NDVI/NDWI satellite data processing scripts
- `ml/` — Random Forest + LSTM model training code
- `models/` — trained model files
- `advisory/` — irrigation/crop suitability advisory logic
- `alerts/` — WhatsApp/SMS alert integration (Twilio)
- `weather/` — weather API fusion
- `reports/` — government-ready PDF/CSV report generation
- `data/` — raw satellite data (gitignored, see pipeline scripts for download instructions)
