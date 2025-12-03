# 🐘 Ecoexist Wildlife Tracking Dashboard

Elephant tracking dashboard for Botswana - monitoring wildlife movement for conservation.

## 🗺️ View the Dashboard

**Two dashboard versions available:**

- **`dashboard_public.html`** - Public dashboard with privacy-protected data (7-day averages)
- **`dashboard.html`** - Full dashboard with login (requires authentication)

## 📊 Data

The `data/` folder contains:
- **`awt_tracking_data_averaged.json`** - Privacy-protected elephant location data (7-day averages)
- GeoJSON files for populated places and roads
- Ecoexist logo and images
- Map overlay data

Data is automatically updated daily from the backend repository.

## 🔒 Privacy Protection

Public dashboard shows 7-day rolling averages of GPS locations to protect elephants from poaching.

## 🚀 Hosting

Enable GitHub Pages to host this dashboard:
1. Go to Settings → Pages
2. Source: Deploy from branch `main`
3. Save

Dashboard will be live at: `https://ecoexist.github.io/ecoexist/dashboard_public.html`

## 📞 Contact

**Ecoexist Trust**
- Website: https://www.ecoexisttrust.org/
- Email: info@ecoexisttrust.org
- Tel: +267 6865083

---

*Last updated: Automatically via GitHub Actions from backend repository*
