# Korean Business Directory AI Extractor 📋🤖

An advanced, AI-powered document intelligence tool that transforms scanned images or photos of physical business directories into perfectly structured, multi-tab Excel spreadsheets. 

Built using **Streamlit**, **Pandas**, **Pydantic**, and the native **Google GenAI SDK**, it leverages visual language models to extract complex, bilingual data points with structured JSON schemas.

---

## 📋 System Requirements

### 1. Functional Requirements
* **Multi-File Processing Engine:** Allow users to drag-and-drop multiple directory pages (JPG/PNG) simultaneously for parallel batch processing.
* **Structured Vision Intelligence:** Use the `gemini-3-flash-preview` model to visually parse Korean and English business information accurately.
* **Address Parsing Engine:** Intelligently isolate physical addresses into four components: Street Number, Street Name (with suite), City, State, and Zip Code.
* **Dynamic Excel Generator:** Dynamically categorize entries into Excel worksheets (tabs) based on detected industry classifications, featuring professional styling, auto-fitted columns, and custom headers.

### 2. Technical Dependencies & Prerequisites
* **Python Runtime:** Python 3.9 to 3.11 recommended.
* **Google Gemini API Key:** An active API key with access to experimental flash preview models.
* **Streamlit Secrets Configuration:** The API key must be injected securely via a local secrets file (`.streamlit/secrets.toml`).

---

## 🚀 Installation & Setup

1. **Clone or Download this Repository** to your local machine.
2. **Install Python dependencies** using pip:
   ```bash
   pip install -r requirements.txt# LA_business_directory_extract
