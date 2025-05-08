## 🔐 TTPFShot: Few-Shot TTP Classification from CTI Reports

Cyber Threat Intelligence (CTI) reports are essential for understanding adversarial behavior—but they are often unstructured and lack sufficient labeled data, making automated extraction of Tactics, Techniques, and Procedures (TTPs) a significant challenge.

**TTPFShot** is a retrieval-based few-shot learning framework designed to address this problem. It enables accurate TTP classification from CTI texts with minimal labeled data.

### 🚀 Key Features

- **Few-Shot Learning**: Constructs few-shot prompts using semantically similar examples retrieved from a vector database.
- **MITRE ATT&CK Integration**: Uses a sentence-based dataset derived from the MITRE ATT&CK framework to guide classification.
- **LLM-Powered**: Leverages large language models to map CTI sentences to appropriate TTP categories.
- **Strong Performance**: Outperforms existing methods like TTPXHunter in both sentence- and document-level evaluations.
- **Real-World Ready**: Delivers higher precision, recall, and F1 scores, helping to mitigate data scarcity in real-world CTI applications.
