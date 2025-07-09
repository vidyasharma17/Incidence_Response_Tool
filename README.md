# Incident Response & Prioritization Tool
  
A data-driven incident response tool leveraging ServiceNow incident logs to automatically assign priority scores and rank active tickets—ensuring teams address the most critical issues first.

---

## 📖 Table of Contents
- [Problem Statement](#-problem-statement)  
- [Objectives](#-objectives)  
- [Tech Stack](#-tech-stack)  
- [Installation](#-installation)  
- [Usage](#-usage)  
- [Outputs](#-outputs)  
- [How It Works](#-how-it-works)  
- [Contributions](#-contributions)  
- [Next Steps](#-next-steps)  
- [License](#-license)  

---

## 📋 Problem Statement

Growing incident volumes can overwhelm response teams, risking high-impact issues being overlooked. Delays in resolution lead to extended downtime, customer frustration, and revenue impact.

---

## 🎯 Objectives

- **Score Assignment**: Calculate a priority score for each “New” or “Active” incident based on severity (Priority, Impact, Urgency), age, reassignments, reopenings, and resolution time.  
- **Automated Ranking**: Sort incidents by score so that the highest-priority tickets appear at the top of the queue.  
- **Improved Efficiency**: Enable data-informed triage decisions to accelerate response times and optimize resource usage.

---

## 🛠️ Tech Stack

- **Data Processing**: Python (pandas, NumPy, datetime)  
- **Visualizations**: matplotlib, seaborn  
- **Dashboards**: Power BI, Tableau  
- **Data Source**: CSV export of ServiceNow incident event logs

---

## 🚀 Installation

1. **Clone the repository**:  
   ```bash
   git clone https://github.com/your-org/incident-prioritizer.git
   cd incident-prioritizer
