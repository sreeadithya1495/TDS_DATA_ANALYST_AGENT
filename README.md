# TDS_DATA_ANALYST_AGENT
  
> Harness the power of **FastAPI**, **LangChain**, and **Google Generative AI** to analyze data like a pro.

---

## ✅ **Overview**  
**AI Data Analyst** is your intelligent assistant for **data-driven decisions**.  
Upload a dataset, ask questions in plain English, and instantly receive:  
✔ **Accurate answers**  
✔ **Visualizations (Charts, Graphs)**  
✔ **AI-driven insights**  

Ideal for:  
- Data Analysts & Researchers  
- Businesses looking for quick insights  
- Students & Educators  

---

## 🌟 **Features at a Glance**  

| Feature                        | Why It Matters |
|--------------------------------|---------------|
| 🤖 **Generative AI Core**      | Understands natural language queries |
| 📊 **Advanced Visuals**        | Plots via **Matplotlib & Seaborn** |
| 🔍 **Web Data Fetching**       | Scrape & analyze live data sources |
| 📂 **Flexible File Support**   | CSV, Excel, JSON, Parquet |
| ⚡ **Performance-Oriented**    | Built on **FastAPI** for speed |
| 🔒 **Secure & Local**          | No external storage |

---

## 🚀 **Quick Start Guide**  

### 1️⃣ **Clone the Repository**
\`\`\`bash
git clone https://github.com/your-username/ai-data-analyst.git
cd ai-data-analyst
\`\`\`

### 2️⃣ **Install Dependencies**
\`\`\`bash
pip install -r requirements.txt
\`\`\`

### 3️⃣ **Set Environment Variables**
Create a **\`.env\`** file in the root directory:  
\`\`\`
GEMINI_API_KEY=your_google_api_key
LLM_TIMEOUT_SECONDS=240
\`\`\`

### 4️⃣ **Launch the App**
\`\`\`bash
uvicorn app:app --reload
\`\`\`
Then open **[http://localhost:8000](http://localhost:8000)** in your browser.

---

## 🛠 **Architecture & Tech Stack**  
- **Backend**: FastAPI, LangChain, Google Generative AI  
- **Data Processing**: Pandas, NumPy  
- **Visualization**: Matplotlib, Seaborn  
- **Utilities**: BeautifulSoup, Pillow  
- **AI Agents**: LangChain tool-based execution  

---

## 📦 **Supported File Formats**  
- \`.csv\` – CSV Files  
- \`.xlsx\`, \`.xls\` – Excel Sheets  
- \`.json\` – JSON Data  
- \`.parquet\` – Parquet Files  
- \`.txt\` – Question Files  

---

## 📡 **API Endpoints**  

| Method | Endpoint   | Purpose |
|--------|-----------|----------|
| \`GET\`  | \`/\`        | Loads the UI |
| \`POST\` | \`/api\`     | Analyze data with questions |
| \`GET\`  | \`/summary\` | System diagnostics |

---

## 🔒 **Security Highlights**  
✔ API keys secured via \`.env\`  
✔ No external cloud storage  
✔ Configurable for production  

---

## 🎯 **Use Cases**  
- **Business**: Sales insights, trend analysis  
- **Research**: Quick hypothesis checks  
- **Academics**: Automating exploratory data analysis  

---

## 📜 **License**  
Distributed under the **MIT License**.  

---
