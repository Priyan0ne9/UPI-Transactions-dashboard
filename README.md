# UPI-Dashboard

## Recommended Structure and Order

### 1. Project Title / Headline

💸 UPI Insights: Analyzing 20,000 Digital Transactions Across India  
An interactive Power BI dashboard that visualizes 20,000+ UPI-based transactions across major Indian banks, revealing patterns based on city, age group, gender, and payment method.

---

### 2. Short Description / Purpose

The UPI Transactions Dashboard is a comprehensive Power BI report that analyzes digital payment behavior from ICICI, HDFC, SBI, and Axis banks. The dashboard uncovers user trends based on demographics, payment methods (QR code, phone number, UPI ID), and transaction value to support financial decision-making and strategy development.

---

### 3. Tech Stack

The dashboard was built using the following tools and technologies:<br>
• 📊 **Power BI Desktop** – For building interactive visualizations and report design.<br>
• 🔍 **Power Query** – For data cleansing, transformation, and structuring of raw Excel files.<br>
• 🧠 **DAX (Data Analysis Expressions)** – Used to create calculated columns such as age groups and perform dynamic filtering.<br>
• 🔗 **Data Modeling** – Relationships established between dimensions (gender, city, payment method) to allow cross-filtering.<br>
• 🧭 **Bookmarks & Navigators** – Used to create smooth navigation across report pages.<br>
• 🎯 **Conditional Formatting** – Applied to highlight key performance metrics and trends.<br>
• 📁 **File Format** – .pbix for report design and .png for preview snapshots.

---

### 4. Data Source

**Source**: Custom Excel dataset containing 20,000+ anonymized UPI transactions from major Indian banks (ICICI, HDFC, SBI, Axis).  

**Structure**:  
Columns include:  
- `Amount`  
- `Currency`  
- `City`  
- `Gender`  
- `Payment Method` (QR, UPI, Phone Number)  
- `Bank`  
- `Transaction Timestamp`  

Derived column:  
- `Age Group` (based on user profile data)

---

### 5. Features / Highlights

#### • Business Problem  
As UPI adoption grows rapidly in India, there is limited visibility into transaction trends based on user behavior, bank distribution, and preferred payment methods. Financial analysts, banks, and policymakers need an intuitive tool to uncover insights.

#### • Goal of the Dashboard  
To create an interactive, visually compelling report that helps:  
- Understand transaction trends by city, gender, and age group.  
- Evaluate the popularity of different payment methods.  
- Compare performance across banks.  
- Enable users to drill down and explore transaction dynamics.

#### • Walkthrough of Key Visuals  

- **Key KPIs (Top Overview Panel)**  
  - Total Transactions  
  - Total Amount  
  - Most Popular Bank  
  - Most Used Payment Method  
  - Top Transaction City

- **Line Chart – Monthly Trends**  
  Visualizes transaction volume over time, useful to spot seasonal trends or spikes.

- **Matrix Table – Bank vs Payment Method**  
  Compares number of transactions by bank and payment type.

- **Stacked Column Chart – Age Group Analysis**  
  Shows how different age groups (e.g., 18–25, 26–35, etc.) prefer certain payment methods.

- **Conditional Formatting in Tables**  
  Highlights high-value transactions and key behavior shifts.

- **Navigator Buttons & Bookmarks**  
  Seamless navigation between pages with reset filters and contextual views.

- **Synchronized Slicers**  
  Filters applied (e.g., by bank, gender, city) stay consistent across visuals for better user experience.

#### • Business Impact & Insights  
- **Banking Strategy**: Identify regions or demographics underserved by specific banks.  
- **Marketing Focus**: Understand the preferred payment channels by different customer segments.  
- **UX Design**: Determine which age groups lean toward QR codes vs. phone number payments.  
- **Policy Planning**: Support decisions related to digital inclusion and UPI infrastructure rollouts.

---

### 6. Screenshots / Demos

![Dashboard Preview](https://github.com/Priyan0ne9/UPI-Transactions-dashboard/blob/main/Page%201.PNG)
![Dashboard Preview](https://github.com/Priyan0ne9/UPI-Transactions-dashboard/blob/main/Page%202.PNG)  
_Above: Home page of the UPI Transactions Dashboard showing slicers, KPIs, and major charts._

---
