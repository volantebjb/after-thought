# After Thought

This project utilizes OpenAI to transcribe and analyze post-interview audio recordings. The provided script, written in Python, demonstrates how to leverage OpenAI's capabilities for speech recognition and further analysis of the transcribed text.

## Prerequisites

Before using the script, ensure you have the following prerequisites:

### 1. Microsoft Azure Speech API Key and Region

Obtain an API key and specify the region in the `recognize_speech_from_file` function.

```python
speech_api_key = "YOUR_AZURE_SPEECH_API_KEY"
speech_api_region = "YOUR_AZURE_REGION"
```

### 2. OpenAI API Key:

Obtain an API key from OpenAI and include it in the script for language generation.
```python
openai.api_key = "YOUR_OPENAI_API_KEY"
Azure and OpenAI Model Deployment:
```

### 3. OpenAI model deployment
Ensure that you have deployed the necessary models on Azure for speech recognition and OpenAI for language generation. Follow the respective documentation to deploy the models.
### 4. Dependencies:

Install the required Python libraries using:
```python
pip install azure-cognitiveservices-speech openai
```
