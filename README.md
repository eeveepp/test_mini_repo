ChatGPT & langchain example for node.js
This repository contains containerized code from this tutorial modified to use the ChatGPT language model, trained by OpenAI, in a node.js project using LangChain.js, an API for language models. The prompt is also slightly modified from the original. 😉

Getting started To use this code, you will need to have a OpenAI API key. If you don't have one yet, you can get one by signing up at https://platform.openai.com

Once you have your API key, clone this repository and add the following with your key to config/env:

OPENAI_API_KEY={YOUR_API_KEY}
After this you can test it by building and running with:

docker build -t langchain_example . 
docker run -it langchain_example
