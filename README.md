
# Agile Meeting Assistant

**Agile Meeting Assistant** is an AI-powered tool designed to provide **agile project planning recommendations** during **Zoom meetings**. By leveraging **OpenAI GPT** and **LangChain**, the system listens to ongoing conversations and offers **real-time suggestions** to help teams align with agile methodologies.

---

## 🚀 Features

- **Real-Time Agile Recommendations**: Get actionable insights and project planning suggestions based on live meeting discussions.
- **Zoom Call Integration**: Tailored for virtual meetings, enhancing productivity and alignment remotely.
- **LangChain Framework**: Chains AI components like LLMs and retrievers for a streamlined recommendation pipeline.
- **OpenAI GPT Integration**: Powers natural language understanding and generates recommendations aligned with agile best practices.
- **Interactive Jupyter Notebook**: Demonstrates the end-to-end workflow, from processing meeting transcripts to delivering insights.

---

## 🛠️ Tech Stack

- **Python**
- **Jupyter Notebooks**
- **LangChain**
- **OpenAI GPT**
- **Azure Cognitive Search (optional for document indexing)**
- **Pandas**

---

## 📂 Project Structure

```
.
├── README.md               # Project documentation
├── requirements.txt        # Required Python packages
└── notebook.ipynb          # Jupyter Notebook demonstrating agile recommendations pipeline
```

---

## 📈 How It Works

1. **Transcript Ingestion**: 
   - Meeting transcripts from **Zoom calls** are processed for analysis.

2. **Insight Generation**:
   - The **LangChain** framework retrieves context or integrates additional knowledge (if configured).
   - **OpenAI GPT** generates agile recommendations based on the meeting discussions.

3. **Notebook Demonstration**:
   - The Jupyter Notebook walks you through ingesting transcripts, generating insights, and iterating recommendations for project planning.

---

## 🧰 Setup Instructions

1. **Clone the Repository**:
   ```bash
   git clone <repo-link>
   cd <repo-folder>
   ```

2. **Install Dependencies**:
   ```bash
   pip install -r requirements.txt
   ```

3. **Configure Environment Variables**:
   - Create a `.env` file with:
     ```
     OPENAI_API_KEY=your_openai_api_key
     ```

4. **Run the Notebook**:
   - Open `notebook.ipynb` in Jupyter and follow the steps!
