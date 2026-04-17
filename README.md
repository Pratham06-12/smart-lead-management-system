<div align="center">

# 🚀 AeroLead AI: Smart Lead Management System

[![PostgreSQL](https://img.shields.io/badge/PostgreSQL-316192?style=for-the-badge&logo=postgresql&logoColor=white)](https://www.postgresql.org/)
[![NodeJS](https://img.shields.io/badge/Node.js-43853D?style=for-the-badge&logo=node.js&logoColor=white)](https://nodejs.org/)
[![React](https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB)](https://reactjs.org/)
[![Power Bi](https://img.shields.io/badge/power_bi-F2C811?style=for-the-badge&logo=powerbi&logoColor=black)](https://powerbi.microsoft.com/)
[![License: MIT](https://img.shields.io/badge/License-MIT-blue.svg?style=for-the-badge)](https://opensource.org/licenses/MIT)

**An intelligent, data-driven CRM platform transforming legacy automotive lead tracking into a centralized analytics engine.**

[Report Bug](https://github.com/Pratham06-12/YOUR-REPO-NAME/issues) • [Request Feature](https://github.com/Pratham06-12/YOUR-REPO-NAME/issues)

</div>

---

## 📖 About The Project

In highly competitive retail sectors, sales teams frequently rely on decentralized, static spreadsheets for lead tracking. This approach leads to severe data silos, delayed customer engagement, dropped leads, and a lack of real-time multi-user collaboration. 

**AeroLead AI (Smart Lead Management System)** was engineered to solve this. It replaces manual, error-prone data entry with a streamlined, state-driven workflow model. 

By aggregating multi-channel lead data into a centralized hub, it provides sales representatives with high-speed interface tools while simultaneously feeding raw data into an analytical pipeline. This empowers business managers with a macroscopic view of organizational performance through real-time conversion metrics.

### ✨ Key Features

*   **Centralized Lead Pipeline:** Dynamic, structured PostgreSQL data grid for instantaneous scanning of demographics and lead priority.
*   **360-Degree Lead Profiles:** Unified view of individual prospects and their complete interaction history.
*   **State-Driven Orchestration:** Frictionless 'Quick Actions' to transition lead statuses, assign team members, and add follow-up notes.
*   **Immutable Activity Timeline:** Automated audit trails chronicling every touchpoint to ensure 100% operational transparency.
*   **Executive BI Dashboard:** Integrated analytical visualizations generating real-time computational KPIs (conversion velocity, pipeline density).

---

## 🛠️ Technical Architecture

The project is built on a scalable, modern MERN/PERN stack optimized for high-speed data flow and analytics capabilities.

<div align="center">
  
| Component | Technology | Description |
| :--- | :--- | :--- |
| **Frontend** | React, Tailwind CSS | High-performance, responsive UI optimized for micro-interactions |
| **Backend** | Node.js, Express.js | Asynchronous RESTful API for handling high-concurrency client requests |
| **Database** | PostgreSQL | Relational schema prioritizing ACID compliance and data integrity |
| **Data & BI** | Python, Power BI | Data wrangling pipeline feeding materialized views for KPI rendering |

</div>

---

## 📂 Repository Structure

```text
├── 📁 client/                # React.js Frontend
│   ├── 📁 src/               # React components, pages, context, and styles
│   └── 📄 package.json       # Frontend dependencies
├── 📁 server/                # Node.js/Express Backend
│   ├── 📁 controllers/       # API logic and query handlers
│   ├── 📁 models/            # Database schemas & SQL connections
│   ├── 📁 routes/            # REST endpoint configurations
│   └── 📄 server.js          # Express entry point
├── 📁 data_analytics/        # Analytics & BI resources
│   ├── 📁 scripts/           # Python ETL / Data cleansing scripts
│   └── 📁 dashboards/        # Power BI source files (.pbix)
├── 📁 docs/                  # Assorted documentation and diagrams
│   └── 📁 assets/            # Screenshots and banner images
├── 📄 .gitignore             # Ignored files (node_modules, .env, etc.)
└── 📄 README.md              # Project documentation
```

---

## 📸 Application Previews

*(Replace the placeholder URLs with actual screenshots once you push the code)*

| 📱 Executive Dashboard | 📋 Lead Listing Screen |
| :---: | :---: |
| <img src="https://via.placeholder.com/600x350.png?text=Dashboard+Preview" alt="Dashboard"/> | <img src="https://via.placeholder.com/600x350.png?text=Lead+Listing+Preview" alt="Listing"/> |

| 🔍 Lead Details 360-View | ⚙️ Quick Actions & Updates |
| :---: | :---: |
| <img src="https://via.placeholder.com/600x350.png?text=Details+Preview" alt="Details"/> | <img src="https://via.placeholder.com/600x350.png?text=Actions+Preview" alt="Actions"/> |

---

## 🚀 Installation & Setup

Want to run this project locally? Follow these steps:

### Prerequisites
*   [Node.js](https://nodejs.org/) (v16+)
*   [PostgreSQL](https://www.postgresql.org/) (Running locally or via cloud e.g., Supabase)

### 1. Clone the Repository
```bash
git clone https://github.com/Pratham06-12/YOUR-REPO-NAME.git
cd YOUR-REPO-NAME
```

### 2. Setup the Backend
```bash
cd server
npm install

# Create a .env file and add your database credentials
echo "DB_URL=postgres://user:password@localhost:5432/crm_db" > .env
echo "PORT=5000" >> .env

# Start the development server
npm run dev
```

### 3. Setup the Frontend
```bash
# Open a new terminal instance
cd client
npm install

# Start the React app
npm start
```
The application will launch automatically at `http://localhost:3000`.

---

## 🔮 Future Enhancements

*   **[ ] Machine Learning Triage:** Integrate Python-based Random Forest models to predict lead conversion probabilities automatically.
*   **[ ] Omnichannel API Hook:** Embed automation logic to trigger WhatsApp Business / Email follow-up actions directly from the CRM.
*   **[ ] SLA Breach Alerts:** Real-time slack/email notifications warning management of leads stagnant in the pipeline for >24 hours.

---

## 👨‍💻 About The Author

**Pratham Nagekar**  
*Data Analyst & aspiring BI Developer focused on translating raw data into business value.*

* **GitHub:** [Pratham06-12](https://github.com/Pratham06-12)
* **LinkedIn:** [Pratham Nagekar](https://www.linkedin.com/in/prathamnagekar06)

---
<div align="center">
  <b>⭐ If you like this project, please consider giving it a star! ⭐</b>
</div>
