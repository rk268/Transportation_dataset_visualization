
# 🚚 Fleet Management Dashboard – Power BI

![Dashboard Overview](https://drive.google.com/uc?export=view&id=11aWYMlxf2m68swJ2wo_aY4-e2qdcNA0k)

## 📌 Overview

This Power BI dashboard is designed to help logistics and transportation organizations manage their fleet more effectively. The **Fleet Management Dashboard** allows real-time monitoring of vehicle usage, driver performance, cost metrics, and fuel consumption to support operational and strategic decisions.

Whether you’re tracking thousands of kilometers traveled, liters of fuel consumed, or driver-based performance metrics, this tool simplifies it all in one unified view.

---

## 📦 Project Highlights

- **Total Liters Consumed**: 42K+
- **Total Drivers Monitored**: 70
- **Total KM Traveled**: 232K
- **Fuel Cost Tracked**: $139K+
- **Maintenance Cost**: $59K
- **Total Fixed Cost**: $548K

---

## 📊 Key Metrics Tracked

- **Driver KPIs**: Distance traveled, fuel usage, maintenance & fixed cost
- **Vehicle Usage Patterns**: By driver, month, and category
- **Fuel Efficiency Trends**: Monitored over time for operational optimization
- **Maintenance Expenses**: Tracked by driver and time period
- **Dynamic Filtering**: Interact with data through customizable filters

---

## 🧠 Dashboard Features

![Advanced Filters](https://drive.google.com/uc?export=view&id=1PZVdMyHbIIvIgU4RZvYjIHMD0yLh323-)

- 🔎 **Open Filter Panel**: Filter by vehicle type, driver name, month, or region
- 📈 **Line Chart**: Shows fuel cost trend across months
- 📋 **Data Grid**: Shows KM traveled, liters consumed, fuel/maintenance/fixed costs per driver
- 🎯 **Summary Cards**: Total KM, drivers, fuel cost, and fixed cost indicators

---

## 🧮 DAX & Logic Used

```DAX
-- Total Fuel Cost
Fuel Cost = SUM('Fleet'[Fuel Consumption])

-- KM per Driver
KM Traveled = SUM('Fleet'[KM])

-- Fuel Efficiency
Fuel Efficiency = DIVIDE([KM Traveled], [Liters Consumed], 0)

-- Maintenance Summary
Maintenance Cost = SUM('Fleet'[Maintenance])
```

---

## 🧱 Data Model

![Data Model View](https://drive.google.com/uc?export=view&id=1BbDfrRUPtS47teXxZorVoJou-kZz_da5)

The model uses:

- One central fact table: `Fleet_Tracking`
- Lookup tables: `Drivers`, `Vehicles`, `Months`
- Relationships optimized for slicer performance

---

## 🖼️ More Screenshots

- 📊 [Alternate Dashboard View 1](https://drive.google.com/file/d/10gyjkU22wPX7ygY3uXfcfhAmQQB5y9LY/view?usp=sharing)
- 🎛️ [Filters View](https://drive.google.com/file/d/1PZVdMyHbIIvIgU4RZvYjIHMD0yLh323-/view?usp=sharing)

---

## 🎯 Business Use Case

This dashboard is ideal for:

- **Fleet Managers**: Track driver-wise KPIs and cost summaries
- **Operations Teams**: Optimize vehicle routes and fuel usage
- **Executives**: Visualize high-level trends and cost breakdowns
- **Maintenance Heads**: Monitor and minimize maintenance-related downtime

---

## 🔍 Insights Enabled

- 🧭 Identify high fuel consumers
- 🚫 Spot underperforming drivers or underused vehicles
- 🛠️ Predictive maintenance using past expense trends
- 📊 Report total cost of ownership over time

---

## 📥 Files & Resources

- 📄 [Main Dashboard Screenshot](https://drive.google.com/file/d/11aWYMlxf2m68swJ2wo_aY4-e2qdcNA0k/view?usp=sharing)
- 📄 [Alternate Dashboard View](https://drive.google.com/file/d/10gyjkU22wPX7ygY3uXfcfhAmQQB5y9LY/view?usp=sharing)
- 📄 [Filter Screenshot](https://drive.google.com/file/d/1PZVdMyHbIIvIgU4RZvYjIHMD0yLh323-/view?usp=sharing)
- 📄 [Model View](https://drive.google.com/file/d/1BbDfrRUPtS47teXxZorVoJou-kZz_da5/view?usp=sharing)

---

## 📬 Contact

For feedback, enhancements, or to collaborate on analytics projects, feel free to reach out:

- 💼 LinkedIn: [LinkedIn](https://www.linkedin.com/in/rupak-kulkarni/)
- 📧 Email: rupakkul97@gmail.com


