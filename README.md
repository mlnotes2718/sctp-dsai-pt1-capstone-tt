# SCTP DSAI PT1 Capstone - Customized Sea-Lion Telegram Bot (Prototype)

## Introduction
This is an improved prototyped version of LLM app based on our capstone project. Our objective is to provide a customized LLM services focus on providing financial related answer and this service will be deployed to Telegram as a frontend.

## Executive Summary
**Objectives**: 

To provide a customized financial advisor that is suitable for Singapore context and deployed the service to telegram as a chatbot.


**Technology:**
- **LLM Service:** We use Sea-Lion as our preferred LLM as it has been fine tuned with local context. We use API instead of downloading pre-trained model as it more cost effective. 
- **Frontend:** Telegram Chatbot (via BotFather)
- **Backend:** Flask Framework to be run as a web services (gunicorn) on render.com
- **Full Stack:** Python + Flask (webhook) + Sea-Lion API + Gunicorn on render.com


**Limitation:**
- **API Rate Limit:** 10 requests per minute per user. Enough for prototyping and testing.
- **No Follow-up Question:** Currently, the chatbot is not able to answer followup questions as user question is not preserved.
- **No Web Search Capabilities:** Currently our chatbot is not able to conduct web search to get the mst updated information.
- **Not able to Handle User Files**: Currently, this chatbot is not able to handle filers user uploaded.


**Privacy Policy:**

As we are using Sea-Lion API, the privacy policy will be the same as Sea-Lion. More information can be obtained at https://sea-lion.ai/privacy-policy/

**Usage:**

This customized chatbot is designed to answer a narrow field, our instruction to the LLM service is as follows: 
> You are a specialised financial planning assistant, dedicated to serving residents of Singapore.  
> Your sole purpose is to answer financial questions with a focus on:  
> • Retirement planning (including CPF LIFE, Retirement Sum schemes, CPF Ordinary, Special and Medisave Accounts)  
> • Personal budgeting and cash-flow management  
> • Housing financial planning (e.g., HDB/private property purchase using CPF, mortgage structuring)  
> • Low-to-moderate-risk, passive investment strategies suitable for long-term retirement goals (e.g., broadly-diversified ETFs, index funds, robo-advisors)

Details of the system prompt can be found in `config.yaml`

**Future Enhancement:**
- **Preserved Chat History Follow-up Question:** Preserved chat history for 
- **No Web Search Capabilities:** Currently our chatbot is not able to conduct web search to get the mst updated information.
- **Not able to Handle User Files**: Currently, this chatbot is not able to handle filers user uploaded.

**Reference:**

- https://sea-lion.ai/
- https://docs.sea-lion.ai/guides/inferencing/api
- https://sea-lion.ai/privacy-policy/


## Analysis Report
...
