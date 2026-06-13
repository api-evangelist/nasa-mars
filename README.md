## NASA Mars Rovers

NASA Mars Rover Photos REST API providing images captured by Curiosity, Opportunity, Spirit, and Perseverance Mars rovers, filterable by sol (Martian day), camera type, and Earth date.

### API Endpoints

- **Rover Photos by Sol:** `GET https://api.nasa.gov/mars-photos/api/v1/rovers/{rover}/photos?sol={sol}&api_key=YOUR_KEY`
- **Rover Photos by Earth Date:** `GET https://api.nasa.gov/mars-photos/api/v1/rovers/{rover}/photos?earth_date={yyyy-mm-dd}&api_key=YOUR_KEY`
- **Latest Photos:** `GET https://api.nasa.gov/mars-photos/api/v1/rovers/{rover}/latest_photos?api_key=YOUR_KEY`
- **Mission Manifest:** `GET https://api.nasa.gov/mars-photos/api/v1/manifests/{rover}?api_key=YOUR_KEY`

### Supported Rovers

| Rover | Status |
|-------|--------|
| Perseverance | Active |
| Curiosity | Active |
| Opportunity | Complete |
| Spirit | Complete |

### Authentication

All requests require an `api_key` query parameter. Use `DEMO_KEY` for testing (30 req/hour). Register for a free key at [api.nasa.gov](https://api.nasa.gov/) for higher limits (1000 req/hour).

### Links

- **Portal:** https://api.nasa.gov/
- **Documentation:** https://api.nasa.gov/#MarsPhotos
- **GitHub (Source):** https://github.com/chrisccerami/mars-photo-api
- **NASA GitHub Org:** https://github.com/nasa
