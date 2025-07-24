# -Excel-Sales-Dashboard-Project
An interactive and automated Excel dashboard that visualizes the performance of sales executives across different regions. This dashboard helps identify top performers, track target achievements, and compare sales figures in real-time using pivot tables, charts, and light macro automation.
📊 #ExcelDashboard | 📈 #SalesAnalytics | 🧮 #MISReporting | 🧠 #BusinessIntelligence | 💼 #PerformanceTracking | 💻 #ExcelVBA


🔍 Problem Statement
Sales managers struggle to gain quick insights from tabular data. Raw sales entries do not show:

Who is hitting their target?

Which regions are underperforming?

What’s the sales pattern over time?

This creates delays in decision-making, performance tracking, and incentive planning.



✅ Business Solution
This project presents a consolidated dashboard that:

Tracks Total Sales per executive

Calculates Target Hit % and Target Gap %

Identifies Top and Bottom Performers

Uses interactive visuals like:

Pie chart for contribution %

Bar chart for sales volume

Line chart for away-from-target trend

All this is done within Excel — no need for third-party tools or paid software.



📸 Dashboard Preview
Here's how your dashboard looks:
               <img width="709" height="278" alt="145340" src="https://github.com/user-attachments/assets/c4f56381-2469-479e-9009-a549a6fbd14f" />


🧾 Raw Data Structure
| Emp Code   | Sales Executive | Region | Day1 | Day2 | ... | Total Sales | Target | Target Hit % | Away From Target % |
| ---------- | --------------- | ------ | ---- | ---- | --- | ----------- | ------ | ------------ | ------------------ |
| MUM-TCL001 | Raj Verma       | Mumbai | 49   | 84   | ... | 339         | 500    | 67.8%        | 32.2%              |
 
                <img width="947" height="452" alt="144406" src="https://github.com/user-attachments/assets/84a96264-2c0a-44ba-a25d-43bcb19f95cd" />




🧰 Tools & Techniques Used

| Category         | Tools / Features                                 |
| ---------------- | ------------------------------------------------ |
| 📊 Dashboard     | Excel 2016+                                      |
| 🔢 Formulas      | `SUM`, `IF`, `% calculation`, `ROUND`, `AVERAGE` |
| 📉 Charts        | Bar, Pie, Line                                   |
| 📋 Pivot Table   | Dynamic data grouping                            |
| 🧠 Visual Design | Shape buttons, color-coded formatting            |
| ⚙️ Macros (VBA)  | Sheet navigation using shape buttons             |


⚙️ Macro/VBA Code Used
To navigate between dashboard tabs, shape buttons like "Dashboard 1", "Dashboard 2" use this simple VBA snippet:
             1. Prepare Your Dashboard Sheets
             2. Insert Shape Buttons
             3. Open VBA Editor (Alt + F11)
             4. Write Macros for Each Sheet Navigation

             Sub GoToDashboard1()
    Sheets("Dashboard 1").Activate
End Sub

Sub GoToDashboard2()
    Sheets("Dashboard 2").Activate
End Sub

Sub GoToDashboard3()
    Sheets("Dashboard 3").Activate
End Sub

Sub GoToDashboard4()
    Sheets("Dashboard 4").Activate
End Sub

            <img width="705" height="329" alt="144702" src="https://github.com/user-attachments/assets/7d9920a8-aab8-48d7-824e-8267a537774d" />

               5. Assign Macro to Each Shape
              <img width="957" height="467" alt="image" src="https://github.com/user-attachments/assets/d417eace-ed3b-4b18-b871-c80dd73d946e" />


📈 Key Metrics Tracked
📌 Total Sales per executive

🎯 Target Hit % → (Total Sales / Target) * 100

🚫 Away From Target % → 100% - Target Hit %

🏆 Top Performer → Highest sales and hit %

📉 Bottom Performer → Lowest sales and highest away-from-target %




🔄 Process of Building the Dashboard
| Step | Description                                                    |
| ---- | -------------------------------------------------------------- |
| 1️⃣  | Input raw daily sales data in the `RAW DATA` sheet             |
| 2️⃣  | Use formulas to compute `Total Sales`, `Target Hit %`, `Gap %` |
| 3️⃣  | Create named ranges for dynamic charts                         |
| 4️⃣  | Use `Pivot Tables` and `Slicers` (optional)                    |
| 5️⃣  | Design visuals using:                                          |
Clustered Bar Chart
Doughnut Chart
Line Chart |
| 6️⃣ | Insert shape buttons → Assign VBA Macros for dashboard navigation |
| 7️⃣ | Add formatting: borders, colors, and headers for visual clarity |
| 8️⃣ | Test filters and update charts automatically when data changes |


📥 How to Use
Open the .xlsm file in Microsoft Excel 2016 or later

Enable Macros if prompted

Go to RAW DATA → Add/update employee sales

Click on "Dashboard 1", "Dashboard 2", etc. to view insights

📎 Data auto-updates across charts and summary tables



🗂 Use Cases
✅ Team Performance Review

📊 Sales Report Automation

🧠 Business Decision Support

📅 Weekly or Monthly Tracking

🎓 Data Analytics Portfolio


🛠 Future Improvements
Add slicers to filter by region or executive

Use dynamic named ranges for real-time chart updates

Export dashboard to PDF for presentations

Integrate Excel Power Query for automation


🔐 Data Licensing
The dataset is simulated for educational and portfolio use.
To practice or expand it, you can use datasets from:

Kaggle – Sales Datasets

Mockaroo – Custom Data Generator

Data.gov.in – MSME Sales
