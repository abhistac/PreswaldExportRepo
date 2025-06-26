# Zara Sales Dashboard

**Live demo:** https://abhistac.github.io/PreswaldExportRepo/

This interactive dashboard was built with Preswald to explore Zara’s scraped sales data.  
Use the sidebar sliders to filter by minimum **price** and **sales volume**, then inspect:

- 📈 **Weekly Sales Trend**  
- 💰 **Price vs. Sales Volume** scatter  
- 📊 **Average Price** by product category bar chart  
- 🥧 **Promotion Types** distribution pie chart  
- 🌳 **Brand → Category** sales treemap  

---

## Project Structure
├── assets/              # JS/CSS assets for the static site
├── index.html           # Entry point for the dashboard
├── project_fs.json      # Preswald export metadata
└── README.md            # This file

---

## How to Run Locally

1. **Install Preswald** (requires Python 3.7+):
   ```bash
   pip install preswald

2. Clone this repo and move into it:
   git clone git@github.com:abhistac/PreswaldExportRepo.git
   cd PreswaldExportRepo

3. Run the dashboard
   preswald run

4. Open your browser at localhost http://localhost:8501.
