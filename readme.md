# 📌 Project Title: Promance – AI-Powered Prompt Enhancer  

## 🚀 Project Overview  
**Promance** is an AI-powered web application designed to improve and refine prompts for Large Language Models (LLMs). It helps users transform vague or unstructured prompts into optimized, well-structured ones that yield better, more accurate, and context-aware responses.  

The project explores advanced prompt engineering techniques such as zero-shot, one-shot, multi-shot, and chain-of-thought prompting. By integrating intelligent suggestions, real-time feedback, and context enrichment, **Promance** enables users to craft high-quality prompts that maximize the effectiveness of AI models.  

## 🔧 Features  
- **Prompt Optimization** – Enhances clarity, specificity, and structure of user prompts.  
- **Multiple Prompting Modes** – Supports zero-shot, one-shot, multi-shot, and chain-of-thought techniques.  
- **Real-time Suggestions** – Provides alternative rephrasings and improvements for better results.  
- **Contextual Enrichment** – Uses embeddings and vector databases to add relevant context.  
- **Evaluation Pipeline** – Tests improved prompts against sample queries for measurable performance.  
- **User-Friendly Interface** – Clean and interactive web app for easy experimentation.  

## 🎯 Tech Stack  
- **Frontend**: Next.js / React + Tailwind CSS  
- **Backend**: Node.js / Python  
- **LLM**: OpenAI / Hugging Face API  
- **Database**: Vector DB (Pinecone / FAISS)  
- **Evaluation**: Custom metrics to compare original vs. improved prompts  

## 📈 Future Scope  
- Multi-language prompt support  
- Prompt version history & analytics  
- Integration with chatbots and AI tools  
- Collaboration features for team-based prompt engineering 

---

## Prompting 


### Zero Shot Prompting 

  A zero shot prompting means giving a task of AI without providing examples or other information , it relies the pre-trained model to respond to your question

 * Translate "What is your name ?" in Russian - Text Transformation
 * How is the weather today in Delhi - Information Retrival 
 * Write a poem on nature - Creative Task
 * What is the answer to 147^89 ? - Reason & Problem Solving

 ### One Shot Prompting

One shot prompting means giving one example of task to AI in your prompt before asking it to perform the same task on a new input.

## 1) Sentiment Classification

* **Input-1:** This is some good food
* **Output-1:** Positive

Now classify:

* **Input-2:** The food didn't have the warmth
* **Output-2:** [To be completed by AI]

## 2) Summarization

* **Text:** "The sun rises in the east and sets in the west."
* **Summary:** "Sun moves east to west."

Now summarize:

* **Text:** "Water boils at 100°C under standard atmospheric pressure."
* **Summary:** [To be completed by AI]

## 3) Reasoning

* **Problem:** 12 + 8 = ?
* **Answer:** 20

Now solve:

* **Problem:** 25 - 9 = ?
* **Answer:** [To be completed by AI]

