# Smurfit Westrock ESG Performance Dashboard

A Streamlit dashboard visualizing Smurfit Westrock's ESG environmental performance data for 2024.

## 📊 Dashboard Sections

- **KPI Cards** — Key metrics across climate, water, forest/fiber, and energy
- **Climate Progress** — Scope 1 & 2 trend (legacy Smurfit Kappa, 2020–2024)
- **Materiality Matrix** — Business impact vs. stakeholder importance scatter
- **Water Withdrawal** — 5-year trend in Mm³
- **Waste Pathways** — Stacked view of landfill, recovery, and other waste
- **Scope 3 Hotspots** — WestRock 2024 value-chain emissions by category
- **Forest/Fiber Trends** — Certified wood sourcing and recycled fiber rates
- **Energy Mix** — WestRock renewable vs. non-renewable donut

## 🚀 Deploy on Streamlit Community Cloud

### 1. Push to GitHub
```bash
git init
git add .
git commit -m "Initial commit: SW ESG Dashboard"
git branch -M main
git remote add origin https://github.com/<your-username>/sw-esg-dashboard.git
git push -u origin main
```

### 2. Deploy on Streamlit Cloud
1. Go to [share.streamlit.io](https://share.streamlit.io)
2. Sign in with GitHub
3. Click **"New app"**
4. Select your repository, branch (`main`), and set **Main file path** to `app.py`
5. Click **Deploy**

Your dashboard will be live at `https://<your-app-name>.streamlit.app`

## 🛠 Run Locally

```bash
# Clone the repo
git clone https://github.com/<your-username>/sw-esg-dashboard.git
cd sw-esg-dashboard

# (Optional) create a virtual environment
python -m venv venv
source venv/bin/activate   # Windows: venv\Scripts\activate

# Install dependencies
pip install -r requirements.txt

# Run the app
streamlit run app.py
```

## 📁 File Structure

```
sw-esg-dashboard/
├── app.py              # Main Streamlit application
├── requirements.txt    # Python dependencies
└── README.md           # This file
```

## 📋 Data Notes

- **Legacy reporting:** Smurfit WestRock was formed mid-2024. Trend data is legacy Smurfit Kappa (SK); 2024 snapshot KPIs for WestRock (WRK) are reported separately.
- **No consolidated targets** have been published yet as of 2025.
- All data sourced from official Smurfit WestRock 2024 sustainability disclosures.

## 🔗 Official Sources

| Document | URL |
|---|---|
| Sustainability Report 2024 | [Link](https://www.smurfitwestrock.com/-/m/files/publications---global/sr-2024-downloads/smurfit_westrock_sustainability_report_2024.pdf) |
| Supporting Data | [Link](https://www.smurfitwestrock.com/-/m/files/publications---global/sr-2024-downloads/swsr_2024_supporting_data.pdf) |
| Supplementary Information | [Link](https://www.smurfitwestrock.com/-/m/files/publications---global/sr-2024-downloads/swsr_2024_supplementary_data.pdf) |
| Annual Report | [Link](https://www.smurfitwestrock.com/-/m/files/publications---global/financial-reports/sw-2024-annual-report.pdf) |
| Planet Section | [Link](https://www.smurfitwestrock.com/-/m/files/publications---global/sr-2024-downloads/swsr_2024_planet.pdf) |
