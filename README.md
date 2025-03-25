# 💼 Interactive Banking Campaign Dashboard  
**One Click, Full Insight: A Client-Level Marketing Breakdown**

An Interactive Tableau Dashboard to Explore Client Behavior & Subscription Trends in Bank Marketing Campaigns

---

📌 **Project Overview**  
This project visualizes client behavior, loan status, and campaign response trends in a bank marketing dataset using an interactive Tableau dashboard.

✅ The goal was to create a dynamic, cross-filtering experience where users can click **any chart element** to filter and explore insights across all sheets — using **select-based action filters** with full interactivity (no dropdowns, no filters to manually toggle).

What began as a raw CSV file became a full-stack data product: cleaned, structured in PostgreSQL, and designed visually in Tableau with a smooth user experience.

---

🎯 **Key Insights & Features**

📆 **Monthly Subscription Trends** → Area chart tracking when clients are more likely to say "yes"

🥧 **Previous Contact Breakdown** → Pie chart showing how prior outreach affects conversions

📚 **Education-Based Subscriptions** → Bar chart comparing subscription rates across education levels

📞 **Call Duration by Contact Type** → Bubble chart visualizing engagement by communication channel

🏠💳 **Loan Ownership Highlight Table** → Cross-tab of personal and housing loan combinations

🧠 **Cross-Sheet Filters** → Every sheet can be clicked to filter others, creating a fully connected story

---

🗂️ **Dataset Overview**

Source: Bank Marketing CSV Dataset  
Rows: 4,521 | Columns: 17

Columns include:

- Age, Job, Marital Status, Education
- Balance, Housing Loan, Personal Loan
- Contact Type, Call Duration, Campaign History
- Previous Contact, Last Campaign Outcome
- Target Variable: `y` (Subscribed: yes/no)

---

📊 **Technologies Used**

- **Python** → Data Cleaning & Preprocessing  
- **PostgreSQL** → Data Storage & Table Structuring  
- **Tableau** → Dashboard Design & Visual Analytics  
- **Tableau Public** → Hosting the live dashboard  
- **GitHub** → Project Code, SQL, & Documentation

---

🚀 **Features Implemented**

✅ Action Filters (Select-Based) → Click any chart to filter all others  
✅ Highlight Filters → Keep visual context across charts  
✅ Clean field renaming & column engineering (`previous_contact`)  
✅ Fully responsive dashboard layout  
✅ Clear visual types: Area, Pie, Bar, Bubble, Highlight Table  
✅ Bold styling and clean labeling for clarity

---

🔗 **Live Dashboard**

▶️ [View on Tableau Public](https://public.tableau.com/app/profile/mantej.singh.samra/viz/InteractiveBankingCampaignDashboard/Dashboard1)

---

📌 **Future Improvements**

- Add a toggle for viewing subscription **rates** vs **counts**
- Add annotations or tooltips to explain chart findings
- Explore clustering clients by behavior (ML ready!)
- Mobile-friendly dashboard layout version
- Sheet swapping using parameter navigation

---

🤝 **Let’s Connect**

- 🔗 [LinkedIn – Mantej Singh Samra](https://www.linkedin.com/in/mantej-singh-samra/)  
- 💻 GitHub: `samramantej`  
- 📧 Email: mantejsamra95@gmail.com

---

Thanks for checking out the project! If you liked it or want to collaborate, feel free to connect ✨
