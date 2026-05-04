# Scraper Platform

## Run
docker-compose up --build

## Trigger Job
POST http://localhost:8000/scrape
{
  "target": "miniapps",
  "base_url": "https://miniapps.ai"
}
