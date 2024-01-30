
## :money_with_wings: Friendly Fincancial Bot 

Inference Demo Here: 👉[https://huggingface.co/spaces/PlantBasedTen/Financial_Bot] \
_Please note: Waking from sleep state can take ~180 seconds_ \
\
This is an intermediate production-ready FTI feature-training-inference RAG-framework LLMOps course by \
Paul Iusztin, Pau Labarta Bajo, and Alexandru Razvant.

-----

![boeing](https://github.com/PlantBasedTendies/hands-on-llms/assets/86295293/3f0a98f2-6b88-4e8e-99aa-52a2419f335b)

-----

Reference article for output contextualization: \
\
![benzinga_boeing_jan-28-2024](https://github.com/PlantBasedTendies/hands-on-llms/assets/86295293/cd4ec1a6-3589-4f95-969d-f2c7fd494cd9) \
[https://www.benzinga.com/news/24/01/36678185/whats-going-on-with-boeing-stock]

-----
\
In this iteration, I've replaced Falcon 7B Instruct with the currently-SOTA (Jan '24) Mistral-7B-Instruct-v0.2, \
fine-tuned using Unsloth on an expanded dataset of financial questions and answers generated with the help of \
GPT-4, quantized and augmented with a 4bit QLoRa. \
\
Live Demo Here: 👉[https://huggingface.co/spaces/PlantBasedTen/Financial_Bot] \
\
Prompt analysis and model registry is handled by Comet LLM, and finance news is streamed via Bytewax using an \
Alpaca API, then parsed, cleaned, and chunked with unstructured, and finally sent as a vector embedding to \
Qdrant's serverless vector store. LangChain chains the prompt and most relevant news article with real-time \
finance information, contextualizing the output. \
\
#TODO: Add citations to output to show end-user which article has been used to generate the output. \
\
I have contributed to the original (MIT licensed, ka-ching!) course which can be found here: \
[https://medium.com/decoding-ml/the-llms-kit-build-a-production-ready-real-time-financial-advisor-system-using-streaming-ffdcb2b50714]

[![Contribution Stats](https://github-contribution-stats.vercel.app/api/?username=plantbasedtendies)]
