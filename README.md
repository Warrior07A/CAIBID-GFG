# Conversational AI for Instant Business Intelligence Dashboards

## Background & Context

In today’s fast-paced environment, data is a company's most valuable asset. However, accessing insights often requires technical skills like SQL or navigating complex Business Intelligence (BI) tools.

This creates a bottleneck where data teams are overwhelmed with basic reporting requests, and business users are left waiting days for simple dashboards.

---

## Business Problem Statement

Build an intelligent system that allows **non-technical users** to generate fully functional, interactive **data dashboards using only natural language prompts**.

The solution must take a plain-English request such as:

> "Show me the monthly sales revenue for Q3 broken down by region and highlight the top-performing product category"

The system should:

1. Query the underlying data  
2. Select the most appropriate chart types  
3. Render a cohesive, interactive dashboard in **real-time**

---

## Target Persona

### The Non-Technical Executive (CXO)

They know what business questions they want to ask but do not know how to:

- Write database queries
- Configure BI visualization settings

---

## Expected Deliverables

- A **working prototype (Web App)** that converts a natural language query into an assortment of charts and insights presented in a dashboard.
- A **public GitHub repository link**.
- A **10-minute presentation** showcasing the tool answering at least **three distinct, progressively complex text queries**.

---

# Recommended Tech Stack

### Frontend
- React
- Next.js
- Vue
- Rapid prototyping frameworks like **Streamlit** or **Gradio**

### Charting & Visualization Libraries
- Recharts
- Chart.js
- D3.js
- Plotly

### Backend & API
- Python (FastAPI, Flask)
- Node.js (Express)

### LLM Integration
- Google Gemini API (via Google AI Studio)

### Database / Storage
- CSV files
- SQLite
- PostgreSQL

---

# Evaluation Framework

## Accuracy (40)

### Data Retrieval
Did the LLM generate the correct SQL/query to fetch the right data based on the prompt?

### Contextual Chart Selection
Did the system choose the correct visual representation?

Examples:
- Line chart → Time-series data
- Pie chart → Parts-of-a-whole

### Error Handling
How gracefully does the application handle:
- Vague prompts
- Ambiguous prompts
- Highly complex user prompts

---

## Aesthetics & UX (30)

### Design
Is the dashboard visually appealing, clean, and modern?

### Interactivity
Can the user interact with generated charts?

Examples:
- Hover tooltips
- Zoom
- Filters

### User Flow
- Is the text-input interface intuitive?
- Is there a loading state or progress indicator while the dashboard is generating?

---

## Approach & Innovation (30)

### Architecture
How robust is the pipeline?

