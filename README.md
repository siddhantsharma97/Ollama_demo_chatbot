# Ollama based chatbot implementation using langsmith


# How to run?
### STEPS:

Clone the repository

```bash
Project repo: https://github.com/siddhantsharma97/Ollama_demo_chatbot.git
```
### STEP 01- Create a conda environment after opening the repository

```bash
conda create -n ollama python=3.9 -y
```

```bash
conda activate ollama
```


### STEP 02- install the requirements
```bash
pip install -r requirements.txt
```


### Download Ollama

```ini

https://ollama.com/download

```
### Run the model using the following command

```bash
ollama run llama2 
```
### Create a project name and add it in the .env file along with langchain API key.

```bash
LANGCHAIN_API_KEY="YOUR_API_KEY"
LANGCHAIN_PROJECT="YOUR_PROJECT_NAME"
```

### You can go to the langsmith dashboard and monitor the traces. Below is the link.
```ini

https://smith.langchain.com/

```
