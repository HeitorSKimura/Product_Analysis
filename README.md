# 📊 Product Analysis

This project is a learning exercise focused on integrating and using the following tools and libraries:

- [`CrewAI`](https://pypi.org/project/crewai/)
- [`pdfkit`](https://pypi.org/project/pdfkit/)
- `Markdown`

---

## 🖥️ System Requirements

- **Operating System:** Windows 10 (tested)
- **Python Version:** 3.12.10
- **OpenAI API Key:** Required for AI features

---

## ⚙️ Setup Instructions (Windows 10)

To ensure everything runs smoothly, you’ll need to install the **Visual Studio C++ Build Tools**:

### 🔧 Installation Steps

1. Download and install [Visual Studio C++ Build Tools](https://visualstudio.microsoft.com/pt-br/visual-cpp-build-tools/)
2. Open the **Visual Studio Installer**
3. Click **Modify** on your existing installation (or install a new one)
4. Select the **"Desktop development with C++"** workload
5. Click **Install** or **Update**

---

## 🔑 Getting Started

1. **Create a Virtual Environment**  
   Run the following command:
    ```bash
    python -m venv .venv
    ```

2. **Activate the Virtual Environment**

   - On **Windows**:
     ```bash
     .venv\Scripts\activate
     ```

   - On **macOS/Linux**:
     ```bash
     source .venv/bin/activate
     ```

3. Install the required dependencies:
    ```bash
    pip install -r requirements.txt
    ```

---

## 🔐 API Configuration
This project uses the **OpenAI API**, which requires an API key with active credits.

1. Create a .env file in the root directory of the project.

2. Add your OpenAI API key in the following format:

```bash
OPENAI_API_KEY=(your_openai_api_key_here)
```

> ⚠️ **Warning:** Make sure you have billing enabled on your OpenAI account.