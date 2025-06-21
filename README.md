# Amazon prime dashboard
Streaming-Style Dashboard (Amazon‑Prime Inspired) I built this interactive Power BI dashboard entirely from scratch. It leverages clean data pipelines and effective visualization techniques to provide intuitive insights into streaming service content.
![amazon prime dashboard](https://github.com/user-attachments/assets/a0396ccb-421d-46fc-83d7-44749778a935)

# Data model-
![Screenshot 2025-06-21 170233](https://github.com/user-attachments/assets/23fed57d-5a45-4a39-80d0-62ac66bd7784)

# Data Sample-
![Screenshot 2025-06-21 170435](https://github.com/user-attachments/assets/4642062d-374c-41a2-a4ed-c698117f887d)

# 🔨 How I Built It
1. Data Ingestion & Power Query Pipeline
I imported raw .csv files and cleaned the data by removing duplicates, handling missing values, and converting data types. I also added calculated columns (e.g., year, runtime buckets, genre flags) in Power Query. I document every step in transformations.md.

2. Modeling & Relationships
I created lookup tables for categorical data (such as genres and years), set up one-to-many relationships, and optimized the model for faster filtering and drill-through capabilities.

3. Visualizations
Overview Page: cards for total titles, average ratings, and a year-wise bar chart.

Interactive Slicers: year, genre, and rating filters.

Drill-Through Detail Page: shows title details, description, images, and metadata.
Everything is built using built-in Power BI visuals—no external or custom visuals used.

4. Design & UX
I applied a unified theme (fonts, colors, backgrounds), formatted visuals for clarity, and arranged pages to guide the user journey logically—from overview to details.

5. Templates & Reusability
Dashboard.pbix: the fully functional dashboard.


# 🌟 Key Highlights
Self-authored end-to-end ETL using Power Query.

Interactive drill-through enabling deep dives into individual titles.

Clean, professional design consistent with dashboard best practices



Modular template format for easy reuse and customization.


# 🚀 Get Started
Clone the repository


Add your data
Place your .csv in data/ and rename it to dataset.csv.

Launch Power BI Desktop


Or open Dashboard.pbix to explore the completed report.

Refresh & Explore
Reload the data and interact with slicers, visuals, and drill-through pages.

Customize
Swap datasets, add new visuals, create additional measures, or tweak the theme.

# 🧠 What You’ll Learn
Building an ETL pipeline using Power Query

Structuring interactive dashboards with drill-through

Designing clear, user-friendly layouts

Creating reusable dashboard templates

# 💬 Inspiration Note
While I looked at concise dashboard tutorials for inspiration, all ETL logic and visuals were independently designed, written, and implemented by me.

# 🤝 Contributing
Found a bug? Please open an issue or submit a pull request.

Want to extend it? I welcome additions like more filters, visuals, or alternate datasets.

# 📄 License
This project is shared under the MIT License—use it freely and adapt it to your needs!
















