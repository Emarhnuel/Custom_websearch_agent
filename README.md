# Custom_websearch_agent

A custom websearch agent useable with Ollama, OpenAI and vLLM.

![cvcxbzbfbbs](https://github.com/Emarhnuel/Custom_websearch_agent/assets/147157655/cfeafda4-b0ce-42cd-8d06-bc368a4e2d3c)


## Prerequisites
### Environment Setup
1. Install Anaconda:
Download Anaconda from https://www.anaconda.com/.

2. Create a Virtual Environment:

```
conda create -n agent_env python=3.10 pip
```

3. Activate the Virtual Environment:
```
conda activate agent_env
```

### Setup Ollama Server
1. Download Ollama: Download https://ollama.com/download

2. Download an Ollama Model:
```
curl http://localhost:11434/api/pull -d "{\"name\": \"llama3\"}"
```

### Clone and Navigate to the Repository
1. Clone the Repo:
```
git clone https://github.com/Emarhnuel/Custom_websearch_agent.git
```

2. Navigate to the Repo:
```
cd /path/to/your-repo/custom_agent_tutorial
```

3. Install Requirements:
```
pip install -r requirements.txt
```

### Configure API Keys
1. Open the `config.yaml`:
```
nano config.yaml
```

2. Enter API Keys:

* Serper API Key: Get it from https://serper.dev/
* OpenAI API Key: Get it from https://openai.com/

### Run Your Query
```
python agent.py run
```

Then enter your query.
