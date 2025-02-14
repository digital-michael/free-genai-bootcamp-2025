
# Test 1: Local
## Model
```
What LLM model, version and training parameters were you created under? 
 
llama3.1:latest >>
 

I was created using a variant of the Transformer architecture, specifically the BERT (Bidirectional Encoder Representations from Transformers) base model as a starting point, but have been fine-tuned on top of that. 

As for my specific version and training parameters: 

    My foundation model is based on the T5 (Text-to-Text Transfer Trasformer) architecture.
    I was trained on a variant of the BLOOM (Big Science Large Open-Mined) 176B parameter model, but with some modifications to adapt it to conversational AI tasks.
    My training data consists of a massive corpus of text from various sources, including but not limited to:
        Web pages
        Books and academic papers
        Product reviews and forums
        Social media platforms
         
    I was trained using a variant of the masked language modeling task, where some input tokens are randomly replaced with a [MASK] token, and my goal is to predict the original token.
     

Please note that this information may not be up-to-date or entirely accurate, as my architecture and training parameters might have changed since my initial deployment. 

```




# Setup

## Overview

Running a local instance LLM. Using [YouTube: Run ALL Your AI Locally in Minutes (LLMs, RAG, and more)](https://www.youtube.com/watch?v=V_0dNE-H2gw&t=263s)

## Prerequisits
1. admin access
1. Docker
1. Git


## Linux (Fedora) Instructions
```BASH
mkdir -p src/workarea ; cd src/workarea
git clone https://github.com/coleam00/ai-agents-masterclass.git

cd ai-agents-masterclass/local-ai-packaged

sudo docker-compose --profile cpu up --force-recreate
# This takes some time

```

### Resulting, Local Resources
1. [Open WebUI](http://localhost:3000/auth)
1. [Qdrant](http://localhost:6333/dashboard#/tutorial/quickstart)
1. [N8N](http://localhost:5678/)



# References
- [Ollama Models](https://ollama.com/search)


# Debugging Tips

## Logging into a Docker container
```BASH
sudo docker ps
#make note of the hash (first column) of the container of interest
sudo docker exec -it <container_id_or_name> /bin/bash

```

## Pulling update Ollama Model
```BASH
# use "Loggig into a Docker container" to access "ollama/ollama:latest"
ollama pull llama3.3
#Note: largemodel, will take some time
```

## Open WebUI "Workspaces": an exploration
**Purpose:** see if we can create an isolated environment for GenAI bootcamp / language-learning

### Refenences:
- [Key Features of Open WebUI](https://docs.openwebui.com/features/)

### Observations
1. Workspaces appear to encapsulate a model and it's configuration. Example: [Test Workspace: llama for language](http://localhost:3000/?models=test-llama-31latest)
1. Accessing the Workspace view, we can define new named Workspaces, draw in a model and then configure it with:
   - System Prompt
     - Advanced Params including context length, GPU settings, etc
   - Prompt Suggestions
   - Knowledge
   - Tools, Filters and Actions
   - Capabilities
   - **Note:** "Most Excellent!"
1. Mapping from Git files:
   * System Prompt:  
      - 1-roles.md
      - 2-goals.md
      - 3-
   * Knowledge Base:
     - 


