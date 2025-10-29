# Cartify Customer & Marketing Analytics
**Data-driven insights to optimise marketing ROI, enhance customer retention, and boost repeat purchases using SQL, Python, and analytics.**

---

![SQLite](https://img.shields.io/badge/SQLite-339933?style=flat&logo=sqlite&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=flat&logo=python&logoColor=white)
![SQL](https://img.shields.io/badge/SQL-000000?style=flat&logo=postgresql&logoColor=white)
![Data Analysis](https://img.shields.io/badge/Data%20Analysis-F5A623?style=flat)
![Visualization](https://img.shields.io/badge/Visualization-FF6F61?style=flat)
![Faker](https://img.shields.io/badge/Faker-007ACC?style=flat)

## Objective
Designed and implemented a comprehensive data solution for **Cartify**, an online retailer, to track marketing campaigns, customer behavior, and sales.  
The goal was to **optimise marketing ROI, enhance customer retention, and increase repeat purchases** using data-driven strategies.

## Methodology
- Developed a **relational database in SQLite** covering customers, orders, products, discounts, campaigns, and website activity.  
- Generated realistic **synthetic datasets** using Python, Faker, and Generative AI.  
- Ensured **data integrity** with primary/foreign keys, unique constraints, composite keys, and cascading deletions.  
- **Normalised data** to reduce redundancy and improve scalability.

### Data Generation
Synthetic datasets for Cartify were generated using Python's Faker library, simulating realistic customer, product, and transaction data. The full code and methodology are detailed in the project report (Appendix), and the generated CSVs are loaded into the database for analysis.

## Execution & Technical Skills
- Engineered **ER diagrams** and implemented a structured database to capture customer interactions, campaign engagement, and sales.  
- Applied **SQL queries** to calculate:
  - **Customer retention:** 78%  
  - **Order abandonment:** 45%  
  - **Average orders per customer:** 3.07  
  - **Campaign ROI:** 6.83%  
  - **Revenue per campaign:** £83,724  
  - **Cost per click:** £3.60  
- Analysed **relationships between discounts, campaigns, and repeat purchases** to guide marketing strategies.  
- Designed **dashboards and visualizations** to communicate trends in sales, marketing effectiveness, and customer engagement.

## Key Business Insights & Impact
- **Personalised campaigns and targeted promotions** improved repeat purchases and reduced churn.  
- Identified **high-performing campaigns**, enabling better marketing budget allocation for higher ROI.  
- Seasonal discount campaigns drove spikes in sales, while non-discount sales remained stable, guiding **pricing strategies**.  
- Insights enhanced **customer engagement, optimised inventory, and contributed to long-term revenue growth**.

## Recommendations
1. Implement **targeted loyalty programs** to boost repeat purchases and reduce churn.  
2. Redirect budget to **high-performing campaigns**, improving marketing ROI.  
3. Adjust pricing and stock levels based on **sales trends and campaign insights**.  
4. Use **customer engagement metrics** to refine campaigns for personalized targeting.  

## Challenges
- **Data Integration:** Combining multiple data sources with different formats.  
- **Privacy & Compliance:** Navigating GDPR and marketing laws.  
- **Real-Time Insights:** Limited ability to adjust campaigns instantly.  
- **Scalability:** Processing unstructured and diverse data efficiently.  

## Business Impact & Future Growth
- **Enhanced Retention:** Personalized campaigns increase loyalty.  
- **Maximized ROI:** Optimized ad spend and campaign effectiveness.  
- **Revenue Growth:** Data-driven campaigns increase sales and customer lifetime value.  
- **Future Expansion:** AI-powered personalization and omnichannel strategies support long-term success. 

## Tools & Technologies
- **Database:** SQLite  
- **SQL:** DDL, queries, analytics  
- **Python:** Data generation with Faker & AI  
- **Visualization:** Excel/Tableau  
- **Analytics:** KPI calculation, retention, ROI, and campaign insights

## How to Use
1. Clone the repository  
2. Run `cartify_analysis.py` to create the database, insert data and view the business analysis and the corresponding outputs  
3. Review `Reports` folder and `ER_Diagram.png` for detailed analysis
4. Review the `Presentation` folder to go through the pitch deck for business heads.
