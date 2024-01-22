# After Thought

This project utilizes OpenAI to transcribe and analyze post-interview audio recordings. The provided script, written in Python, demonstrates how to leverage OpenAI's capabilities for speech recognition and further analysis of the transcribed text.

## Prerequisites

Before using the script, ensure you have the following prerequisites:

### 1. Microsoft Azure Speech API Key and Region

Obtain an API key from Azure Speech and include it in your ```.env``` file for language generation.

```python
SPEECH_API_KEY = "YOUR_SPEECH_API_KEY"
SPEECH_API_REGION = "YOUR_SPEECH_API_REGION"
```

### 2. OpenAI Credentials:

Obtain an API key from Azure OpenAI and include it in your ```.env``` file for language generation.
```python
OPENAI_API_TYPE = "YOUR_OPENAI_API_TYPE"
OPENAI_API_KEY = "YOUR_OPENAI_API_KEY"
OPENAI_API_BASE = "YOUR_OPENAI_API_BASE"
OPENAI_API_VERSION = "YOUR_OPENAI_API_VERSION"
```

### 3. Azure and OpenAI Model Deployment:
Ensure that you have deployed the necessary models on Azure for speech recognition and OpenAI for language generation. Follow the respective documentation to deploy the models. Obtain the model name and include it in your ```.env``` file. 

```python
COMPLETIONS_MODEL = "YOUR_COMPLETIONS_MODEL_NAME"
```

### 4. Dependencies:

Install the required Python libraries using:
```python
pip install azure-cognitiveservices-speech openai
```
