# 📊 AI Data Analysis Agent

### 🎓 FREE Step-by-Step Tutorial 
**👉 [Click here to follow our complete step-by-step tutorial](https://www.theunwindai.com/p/build-an-ai-data-analysis-agent) and learn how to build this from scratch with detailed code walkthroughs, explanations, and best practices.**

An AI data analysis Agent built using the Agno Agent framework and Openai's gpt-4o model. This agent helps users analyze their data - csv, excel files through natural language queries, powered by OpenAI's language models and DuckDB for efficient data processing - making data analysis accessible to users regardless of their SQL expertise.

## Features

- 📤 **File Upload Support**: 
  - Upload CSV and Excel files
  - Automatic data type detection and schema inference
  - Support for multiple file formats

- 💬 **Natural Language Queries**: 
  - Convert natural language questions into SQL queries
  - Get instant answers about your data
  - No SQL knowledge required

- 🔍 **Advanced Analysis**:
  - Perform complex data aggregations
  - Filter and sort data
  - Generate statistical summaries
  - Create data visualizations

- 🎯 **Interactive UI**:
  - User-friendly Streamlit interface
  - Real-time query processing
  - Clear result presentation

## How to Run

1. **Setup Environment**
   ```bash
   # Clone the repository
   git clone https://github.com/Shubhamsaboo/awesome-llm-apps.git
   cd awesome-llm-apps/starter_ai_agents/ai_data_analysis_agent

   # 在项目目录下创建虚拟环境
    python -m venv .venv
    
    # 激活虚拟环境
    .\.venv\Scripts\Activate.ps1
    
    # 在虚拟环境中安装依赖
    pip install -r requirements.txt
    
    python.exe -m pip install --upgrade pip
   
    # 使用阿里云镜像源
    pip config set global.index-url https://mirrors.aliyun.com/pypi/simple/
    pip config set global.trusted-host mirrors.aliyun.com
   ```

2. **Configure API Keys**
   - Get OpenAI API key from [OpenAI Platform](https://platform.openai.com)

3. **Run the Application**
   ```bash
   streamlit run ai_data_analyst.py
   ```

## Usage

1. Launch the application using the command above
2. Provide your OpenAI API key in the sidebar of Streamlit
3. Upload your CSV or Excel file through the Streamlit interface
4. Ask questions about your data in natural language
5. View the results and generated visualizations

