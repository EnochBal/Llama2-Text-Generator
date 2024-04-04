# Llama2-Text-Generator
This project aims to showcase the utilization of large language models (LLMs) like Llama2 on Google Colab, demonstrating how to adjust prompts to achieve desired text generation outcomes.

Necessary Installs:
To run the project, ensure the following packages are installed:

!pip install huggingface_hub
!pip install llama-cpp-python==0.1.78
!pip install numpy==1.23.4
For detailed installation instructions of llama-cpp-python, refer to the installation guide: https://pypi.org/project/llama-cpp-python/

Necessary Imports:
Make sure to include the following imports in your Python code:

from huggingface_hub import hf_hub_download
from llama_cpp import Llama

Model Used:
The project utilizes the Llama-2-13B-chat-GGML model, which can be accessed from the Hugging Face Model Hub:

https://huggingface.co/TheBloke/Llama-2-13B-chat-GGML
