# AI Translator App Using OpenRouter API
AI-powered Translator web application utilizing the OpenRouter API and freely available AI models, integrated with Python and Streamlit frameworks.

### Prerequisites
Before we begin, make sure you have the following:
*   **Python 3.6+** installed on your machine.
*   Basic knowledge of Python programming.
*   Familiarity with Streamlit for building web applications.
*   An API key from OpenRouter. You can sign up and get one [here](https://openrouter.ai/).

### Setting Up the Environment
First, let’s install the necessary Python packages. Open your terminal and run:

`pip install streamlit requests python-dotenv`

### Environment Variables
To keep your API key secure, we’ll use a .env file. In your project directory, create a `.env` file:

`touch .env`

`OPENROUTER_API_KEY=your_openrouter_api_key`

### Defining Available AI Models
As of the time of writing this readme file, these are the list of free AI models available on OpenRouter:

```ini
# Free AI models
AI_MODELS = [
    "google/gemini-2.5-pro-exp-03-25:free",
    "google/gemma-3-1b-it:free",
    "google/gemma-3-4b-it:free",
    "google/gemma-3-12b-it:free",
    "google/gemma-3-27b-it:free",
    "google/gemini-2.0-flash-lite-preview-02-05:free",
    "google/gemini-2.0-pro-exp-02-05:free",
    "google/gemini-2.0-flash-thinking-exp:free",
    "google/gemini-2.0-flash-thinking-exp-1219:free",
    "google/gemini-2.0-flash-exp:free",
    "google/learnlm-1.5-pro-experimental:free",
    "google/gemini-flash-1.5-8b-exp",
    "google/gemma-2-9b-it:free",
    "deepseek/deepseek-chat-v3-0324:free",
    "deepseek/deepseek-r1-zero:free",
    "deepseek/deepseek-r1-distill-llama-70b:free",
    "deepseek/deepseek-r1:free",
    "deepseek/deepseek-chat:free",
    "meta-llama/llama-3.3-70b-instruct:free",
    "meta-llama/llama-3.2-3b-instruct:free",
    "meta-llama/llama-3.2-1b-instruct:free",
    "meta-llama/llama-3.2-11b-vision-instruct:free",
    "meta-llama/llama-3.1-8b-instruct:free",
    "meta-llama/llama-3-8b-instruct:free",
    "qwen/qwen2.5-vl-3b-instruct:free",
    "qwen/qwen2.5-vl-32b-instruct:free",
    "qwen/qwq-32b:free",
    "qwen/qwen2.5-vl-72b-instruct:free",
    "deepseek/deepseek-r1-distill-qwen-32b:free",
    "deepseek/deepseek-r1-distill-qwen-14b:free",
    "qwen/qwq-32b-preview:free",
    "qwen/qwen-2.5-coder-32b-instruct:free",
    "qwen/qwen-2.5-72b-instruct:free",
    "qwen/qwen-2.5-vl-7b-instruct:free",
    "qwen/qwen-2-7b-instruct:free",
    "allenai/molmo-7b-d:free",
    "bytedance-research/ui-tars-72b:free",
    "featherless/qwerky-72b:free",
    "mistralai/mistral-small-3.1-24b-instruct:free",
    "open-r1/olympiccoder-7b:free",
    "open-r1/olympiccoder-32b:free",
    "rekaai/reka-flash-3:free",
    "moonshotai/moonlight-16b-a3b-instruct:free",
    "nousresearch/deephermes-3-llama-3-8b-preview:free",
    "cognitivecomputations/dolphin3.0-r1-mistral-24b:free",
    "cognitivecomputations/dolphin3.0-mistral-24b:free",
    "mistralai/mistral-small-24b-instruct-2501:free",
    "sophosympatheia/rogue-rose-103b-v0.2:free",
    "nvidia/llama-3.1-nemotron-70b-instruct:free",
    "mistralai/mistral-nemo:free",
    "mistralai/mistral-7b-instruct:free",
    "microsoft/phi-3-mini-128k-instruct:free",
    "microsoft/phi-3-medium-128k-instruct:free",
    "openchat/openchat-7b:free",
    "undi95/toppy-m-7b:free",
    "huggingfaceh4/zephyr-7b-beta:free",
    "gryphe/mythomax-l2-13b:free"
]
```

The list of freely available AI models will update regularly, so check on [OpenRouter](https://openrouter.ai/models?max_price=0) for more updates.

### Running the Streamlit App
`streamlit run app.py`

For more explanation on part by part of the script, please refer to [Create an AI Translator App with OpenRouter API, Python, and Streamlit](https://walterpinem.com/ai-translator-app-openrouter-api/).
