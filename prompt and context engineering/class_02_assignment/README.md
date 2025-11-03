# 🧩 **Class Assignment 02**
Understand the difference between Chain of Thought (CoT) and Tree of Thoughts (ToT) Prompting, and create a LinkedIn post summarizing your insights.


# 🧠 Chain of Thought (CoT) vs 🌳 Tree of Thoughts (ToT) Prompting

This file explains the difference between **Chain of Thought (CoT)** and **Tree of Thoughts (ToT)** prompting — two important reasoning techniques used in modern AI systems.

## 🧠 Chain of Thought (CoT) 

**Chain of Thought (CoT)** prompting means asking the llm to **think step-by-step** before giving the final answer.It's like solving a math problem by showing your work - step by step.

### 🧩 Example:
**Prompt:**  
> If Rohit has 5 apples and buys 3 more, how many does he have?
Let's think step by step:
1. Rohit starts with 5 apples
2. He buys 3 more apples
3. So total = 5 + 3 = 8 apples
Answer: 8 apples"

✅ **CoT helps the AI think in a straight line — one thought after another.**

## 🌳 Tree of Thoughts (ToT) — Definition

**Tree of Thoughts (ToT)** prompting is a more advanced version of CoT.  
Instead of thinking in a straight line, the AI explores **multiple possible reasoning paths** like branches of a tree — and then chooses the best one.

### 🧩 Example:
**Prompt:**  
> "Plan a birthday party with $100 budget:

Option 1: Big cake + small decorations
Option 2: Medium cake + good decorations  
Option 3: Cupcakes + great decorations + some games

Best option: Option 3 because it has variety and fits budget"

✅ **ToT helps the llm think like a decision-maker — exploring, comparing, and choosing.**

---

## ⚖️ Key Difference

| Feature | 🧠 Chain of Thought (CoT) | 🌳 Tree of Thoughts (ToT) |
|----------|--------------------------|---------------------------|
| **How it works** | Thinks step-by-step in one direction | Explores multiple possible ideas or paths |
| **Focus** | Linear reasoning | Multi-path reasoning |
| **Goal** | Solve one clear problem | Find the best solution from many options |
| **Output Type** | Single reasoning chain | Several reasoning chains (branches) |
| **Example** | Solving a math problem step-by-step | Planning the best trip by comparing different ideas |
| **Use Case** | Math problems, logic, and reasoning tasks | Decision-making, creative writing, complex planning |

---

## ✈️ Real-World Example – Travel Planner

Imagine an AI travel planner:

With CoT, it will create one travel plan step-by-step — book flight → find hotel → list tourist spots.

With ToT, it will generate multiple travel routes, compare flight timings, costs, and experiences, then choose the most enjoyable and efficient plan.

So, ToT gives you a well-balanced and optimized travel experience.

🛍️ Real-World Example – Shopping Assistant

Imagine an AI shopping assistant:

With CoT, it will pick one outfit by following a single line of thought — like “find a red dress under $50.”

With ToT, it will explore many outfit combinations (different colors, styles, and prices), compare them, and suggest the best match for your taste and budget.

So, ToT helps you get smarter and more personalized shopping suggestions.

---

### 🧾 Summary

➡️ **Chain of Thought (CoT)** Finds ONE solution by thinking step-by-step in a straight line. 
➡️ **Tree of Thoughts (ToT)** Explores MULTIPLE solutions by thinking step-by-step in different directions, then picks the best one.
Use CoT for straightforward problems, Use ToT for complex decisions! 🚀
Together, they make modern AI systems more **intelligent, logical, and creative**.

---

**Created by:** Kristina  
**Topic:** Chain of Thought vs Tree of Thoughts Prompting