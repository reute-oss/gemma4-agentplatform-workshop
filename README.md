# Gemma 4 on Agent Platform — deploy & personalize

A hands-on notebook: deploy an open **Gemma 4** model as your own private endpoint on
Google Cloud's Agent Platform, then personalize it two ways — **RAG**
(give it your facts) and **fine-tuning with LoRA** (change its behavior).

**▶ Open in Colab:**
https://colab.research.google.com/github/reute-oss/gemma4-agentplatform-workshop/blob/main/gemma4_vertex_ai_workshop.ipynb

## What you'll do
1. Deploy Gemma 4 from **Agent Platform Model Garden** and copy the endpoint id.
2. Fill in `PROJECT` and `ENDPOINT_ID` in the notebook's Setup cell.
3. Run it: connect, generate, **RAG with citations**, and real **LoRA fine-tuning** code.

No API keys required — the notebook uses your Google credentials. The fine-tuning
section is real training code; run it in a **GPU** runtime with your own dataset.

## Requirements
A Google Cloud project with Agent Platform enabled and permission to deploy from Model
Garden. Fine-tuning additionally needs a GPU and a Hugging Face account that has
accepted the Gemma license.

---

> **Disclaimer:** This code is provided "as-is" as a demonstration only to illustrate a potential solution. The code does not constitute a Google product or service of any kind, and Google offers no support, warranties, or liability of any kind with its regard. Whoever chooses to use this code accepts all responsibility related to it, including for its implementation, use, and ongoing maintenance. For the avoidance of doubt, this code is not eligible for the Google Open Source Software Vulnerability Rewards Program.
