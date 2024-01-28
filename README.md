
## :money_with_wings: Friendly Fincancial Bot 

Inference Demo Here: 👉[https://huggingface.co/spaces/PlantBasedTen/Financial_Bot] \
\
![financial_bot_01-28-24](https://github.com/PlantBasedTendies/hands-on-llms/assets/86295293/2abc56c1-94cd-47fa-b6ec-a7472bb3ad58)
\
![cnn_boeing_jan_18_2024](https://github.com/PlantBasedTendies/hands-on-llms/assets/86295293/edd55e5b-79f7-4c46-9e5a-c51f553a8351)
[https://www.cnn.com/2024/01/18/business/akasa-air-boeing-737-max-india-intl-hnk/index.html]

This is an invaluable 3-part production-ready FTI feature-training-inference RAG-framework LLMOps course by \
Paul Iusztin, Pau Labarta Bajo, and Alexandru Razvant. \
\
In this iteration, I've replaced Falcon 7B Instruct with the currently-SoTa (Jan'24) Mistral-7B-Instruct-v0.2, \
fine-tuned using Unsloth on an expanded dataset of financial questions and answers generated with the help of GPT-4, \
quantized and augmented with a 4bit QLoRa. \
\
Prompt analysis and model registry is handled by Comet LLM, and finance news is streamed via Bytewax using an \
Alpaca API, then parsed, cleaned, and chunked with unstructured, and finally sent as a vector embedding to \
Qdrant's serverless vector store. LangChain chains the prompt and most relevant news article with real-time \
finance information, contextualizing the output. \
\
#TODO: Add citations to output to show end-user which article has been used to generate the output. \
\
I have contributed to the original MIT licensed (ka-ching!) course which can be found here: \
[https://medium.com/decoding-ml/the-llms-kit-build-a-production-ready-real-time-financial-advisor-system-using-streaming-ffdcb2b50714]
