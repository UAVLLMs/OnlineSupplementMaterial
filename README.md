# UAV-LLM Survey Dataset

This repository contains the dataset and analysis results for our study on the integration of Large Language Models (LLMs) in Unmanned Aerial Vehicle (UAV) systems. The dataset is organized to support reproducibility and further research on UAV-LLM applications.

**List_Papers.xlsx：** This file contains the information of selected 74 papers.

**List_GitHub_Repository.xlsx：** This file contains information for 56 GitHub repositories relevant to UAV-LLM integration.

**Survey-English.pdf and Survey-Chinese.pdf：** Survey-English.pdf and survey-Chinese.pdf are the survey of English and Chinese versions, respectively.

**Result_Open_Card_Sorting_Papers.xlsx：** This file documents the in-depth analysis of the 74 selected papers and the systematic categorization of the functions described in them, addressing **RQ1: Research status of large language models in the field of UAVs.** Two researchers independently reviewed each paper and extracted specific applications of LLMs in UAV systems. During the data extraction process, the raw functional expressions were first identified, such as “natural language parsing of flight commands” and “dialog-based multi-round path replanning.” These were then condensed into standardized functional intents with unified naming, such as “task parsing” and “path reasoning and planning.” Subsequently, similar functions were grouped into higher-level categories based on their semantic relevance and technical implementation logic, and were numbered (1–9), ultimately resulting in nine distinct functional types.

**Result_Open_Card_Sorting_GitHub_Repository.xlsx：** This file reports the open card–sorting results for 56 real-world GitHub repositories. Building on the functional taxonomy established in **RQ1: Research status of large language models in the field of UAVs.**, two researchers independently annotated each repository with its LLM task type(s) and application area(s) (with integration mode and interaction form added when applicable), then reconciled disagreements to produce the final labels. The dataset supports **RQ2: What is the difference between academia and industry in the UAV-LLM integration?** with reproducible evidence.

## Usage Notes
- All files are provided in accessible formats (PDF, or Excel) to facilitate analysis.  
- Researchers can use the provided datasets to replicate our analysis, explore UAV-LLM functionalities, or extend the study with additional repositories or papers.  
- For questions or suggestions regarding the dataset, please open an issue in this repository.
