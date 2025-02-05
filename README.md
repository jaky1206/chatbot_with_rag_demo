# Chatbot With RAG Demo

## Overview


## Conda Environment Setup

### Create a new conda environment
```shell
conda create -n chatbot_with_rag_demo
```

### Activate the environment
```shell
conda activate chatbot_with_rag_demo
```

### Export configuration to a file
```shell
conda env export > requirements.yml
```

### Create a new conda environment from the config file
```shell
conda env create -f requirements.yml
```

## Pip Environment Setup

### Create a new virtual environment
```shell
python -m venv chatbot_with_rag_demo_env
```

### Activate the environment
- On Windows:
  ```shell
  chatbot_with_rag_demo_env\Scripts\activate
  ```
- On macOS/Linux:
  ```shell
  source chatbot_with_rag_demo_env/bin/activate
  ```

### Install dependencies from a requirements file
1. Create a `requirements.txt` file with your dependencies.
2. Run:
   ```shell
   pip install -r requirements.txt
   ```

### Export the environment configuration to a file
```shell
pip freeze > requirements.txt
```
for pip packages from a conda environment
```
pip list --format=freeze > requirements.txt
```

### Create a new virtual environment and install dependencies from the `requirements.txt` file
1. Create a new virtual environment as shown above.
2. Activate the environment.
3. Run:
   ```shell
   pip install -r requirements.txt
   ```


## Repository Structure


## Languages
- Python

## Acknowledgments
- https://tomstechacademy.com/build-a-chatbot-with-rag-retrieval-augmented-generation/
