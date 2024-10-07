# hobi

## 1. Koleksi LoRA

Problem Statement

- July 2023 I need to work on AI Chatbot and deploy on Sep 2023 where it will be able to answer any info from a website. Most of the hardwork are depend on how reliable the chunk retrieval is based on user query. I think doing it like that easy to debug and finetune but the way it do retrieval still just based on luck because current similarity metric(cosine) is just something nlp researcher found nearly work instead of REALLY work. While many people working on RAG like different embedding model, different reranker, hybrid, router,  early chunking, late chunking etc which is engineering problem, I more interested working/dissect on the model itself.

Objective

- Use LoRA as a persona where it remember and know info by having raw text only.
- Smol model are more useful rather than having giant General AI then you prompt it to limit what they can answer 🤣
- Create smol domain specialist instead of generalist model because large model more suite for general AI
- Roleplay model where it will act and reply as certain persona. (Less important)

Plan

Make it work === remember 70% of the information from raw text

1. Make it work(smol dataset)
2. Make it work(large corpus)
3. Make it work while reducing forgetting
4. Make it work while reducing forgetting and persist original model capability(chat for example)
5. Fully impart knowledge(100% remember rate) with minimal effect to base model

Dataset(Still thinking)

1. Data already have right now
2. Text book??
3. Story book?
4. ...
5. If someone want me to train LoRA for their data feel free to share

Architecture so far(Too soon for data flywheel 😭)

1. Crawl then Scrape website
2. Finetune raw text for LoRA
3. Evaluate based on metric
4. Share LoRA weights

---

## 2. Coming Soon

Testing

---

Funds 💸

I allocate max RM1k for this project and will stop when don't have fund to see what i can do with RM1k.
1. Paid $50 for gpu credit(hoping for ringgit will be stronger) ~ RM205

remaining: RM795