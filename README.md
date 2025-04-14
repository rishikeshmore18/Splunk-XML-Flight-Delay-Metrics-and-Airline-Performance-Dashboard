# ✈️ Splunk-XML-Flight-Delay-Metrics-and-Airline-Performance-Dashboard

A Splunk-powered dual-dashboard solution that visualizes, analyzes, and monitors U.S. flight delay causes, airline KPIs, cancellations, and route-specific performance trends in real-time. Built with modular XML and SPL queries, this solution provides interactive exploration through geo-maps, pie charts, bar graphs, and dynamic tables.

---

## 📊 Features

- **Total Delay Trends:** Breakdown by delay cause (weather, aircraft, NAS, etc.)
- **Airline Delay Performance:** Departure vs. arrival delays per carrier
- **Route Metrics:** Avg. flight durations, air time, and distance visualizations
- **Geospatial Dashboard:** Map view of flight volumes by city
- **Cancellation & On-Time Rates:** Airline-level heatmaps and KPIs
- **Dropdown Filters:** Interactivity via origin and destination city selectors

---

## 🧰 Technologies Used

| Tool/Language | Usage |
|---------------|-------|
| Splunk XML | Dashboard authoring |
| SPL (Search Processing Language) | Queries and aggregations |
| Markdown | Documentation |
| HTML | Data dictionary formatting |

---

## 📂 Project Structure

| File | Description |
|------|-------------|
| `Dashboard_1.xml` | Delay Trends and Route Metrics |
| `Dashboard_2.xml` | Airline KPIs, Cancellations & Geo Maps |
| `dictionary.html` | Cleaned schema + field dictionary |

---

## 📸 Screenshots


### ✈️ Delay Trends and Performance

<img width="791" alt="Screenshot 2025-04-14 180721" src="https://github.com/user-attachments/assets/e926628a-4838-4aad-b2fd-afd3ea5edd51" />


### 🌍 Flight Volume & Route KPIs

<img width="792" alt="Screenshot 2025-04-14 180802" src="https://github.com/user-attachments/assets/f7c6a37e-628f-4a45-97e5-e48a0e617d6a" />


---

## 🧠 Dataset Overview

Data ingested via `sampled_flights_tattoine` index in Splunk includes fields like:

- `ARR_DELAY`, `DEP_DELAY`, `CANCELLED`, `DISTANCE`, `AIR_TIME`
- `ORIGIN_CITY`, `DEST_CITY`, `FlightDate`, `CarrierDelay`, etc.

Refer to [`dictionary.html`](dictionary.html) for schema mappings and full descriptions.

---

## 🚀 Usage

1. Import `Dashboard_1.xml` and `Dashboard_2.xml` into your Splunk environment.
2. Set your default index to: `sampled_flights_tattoine`.
3. Modify field tokens as needed if using custom field names.
4. Add CSV ingest or pipeline to index your FAA-format flight data.

---

## 📌 Author

**Rishikesh More**  
📫 more.rishikesh.18@gmail.com | 🎓 rmore@clarku.edu  
🔗 [LinkedIn](https://www.linkedin.com/in/more-rishikesh-p07) | 💻 [GitHub](https://github.com/rishikeshmore18)

---

## 🏷️ Tags
`Splunk` `Flight Analytics` `XML Dashboard` `Airline Performance` `Delay Metrics` `Interactive Visualization` `KPI Tracking`
