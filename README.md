
# Agentic RAG using CrewAI

This project leverages CrewAI to build an Agentic RAG that can search through your docs and fallbacks to web search in case it doesn't find the answer in the docs, have option to use either of deep-seek-r1 or llama 3.2 that runs locally. More details un Running the app section below!

Before that, make sure you grab your FireCrawl API keys to search the web.

**Get API Keys**:

-Serper API KEY
-LLM API KEY if required

## Installation and setup
```bash
conda create -n env_crewai python==3.12 -y
conda activate env_crewai
```


```bash
uv lock
uv sync
```

**Install Dependencies**:
   Ensure you have Python 3.11 or later installed.
   ```bash
   pip install crewai crewai-tools markitdown qdrant-client fastembed
   ```

**Running the app**:

To use deep-seek-rq use command ``` streamlit run app_deep_seek.py ```, for llama 3.2 use command ``` streamlit run app_llama3.2.py ```

---

