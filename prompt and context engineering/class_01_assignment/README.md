# **Class Assignment 01**

Make a presentation explaining the difference between Prompt Engineering and Context Engineering.

# **PORMPT AND CONTEXT ENGINEERING**

Difference between **Prompt Engineering** and **Context Engineering**, two key concepts in working with Large Language Models (LLMs).

## Prompt Engineering

**Prompt Engineering**  
It tells the LLM **what to do** and **how to do it**, helping the model understand your prompt and generate accurate results.

### Example:
**Prompt:**  
> "Write a poem."

Here, the llm only knows it has to create *any* poem.  
There’s no detail about style, tone, or topic — os its generate unpredictable or random results..


## Context Engineering 

**Context Engineering** giving  **additional information** along with the prompt to get better results.It's like telling someone not just what to do, but also giving them background information so they understand the situation better.— such as topic details, user data, or documents — so it can generate more relevant and meaningful responses.

### Example:
**Context + Prompt:**  
> "Write a short, rhyming poem about the moon for nursery class students."

Now the llm knows **what the topic is** (moon), **who the audience is** (nursery students), and **what style to use** (simple rhyming).  
The result will be more accurate, creative, and aligned with your intent.

## **Key Difference Between Prompt Engineering and Context Engineering**

Both Prompt Engineering and Context Engineering are important when working with llm, but they work differently and change how the llm response. 

| Feature | 🧠 Prompt Engineering | 📚 Context Engineering |
|----------|----------------------|------------------------|
| **Definition** | Writing clear, well-structured prompts to tell the LLM what to do and how to do it. |Giving the LLM extra background information or context together with the prompt. |
| **Focus** | On crafting effective instructions. | On providing the right information for the model to understand before answering. |
| **Output Quality** | Produces good results for simple queries or tasks. | Produces **more accurate, context-aware, and meaningful results**, especially for advanced AI systems. |
| **Which Gives Better Output?** | Works well for basic responses. | ✅ **Context Engineering gives better results** because it allows the model to use real data and past knowledge. |
| **Advantages** | Easy to use and fast to implement. | Enhances accuracy, reduces hallucination, and helps the model understand real-world information. |
| **Example** | **Prompt:** “Explain what RAG means.” | **Context + Prompt:** “Using this document about RAG systems, explain what RAG means in simple terms.” |
| **Practical Use Case** | Writing code snippets, translations, summaries, or creative writing. | Building chatbots, search assistants, and enterprise-level AI systems that need to recall facts. |

---
### 🧾 Summary 

➡️ Modern chatbots mostly use Context Engineering because it helps them find the right information from databases or documents.
This makes their answers more accurate, helpful, and personalized.

**Created by:** Kristina  
**Topic:** Key Difference – Prompt vs Context Engineering (Quarter 4 – Saturday 2 to 5)