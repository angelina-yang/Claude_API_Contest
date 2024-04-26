# Claude API Contest Project - STORM: AI Agents for Long-Form Writing


**Project Author: TwoSetAI**
Angelina Yang: [Linkedin](https://www.linkedin.com/in/MeetAngelina/)
Mehdi Allahyari: [Linkedin](https://www.linkedin.com/in/mehdiallahyari/) [Github](https://github.com/mallahyari)

**YouTube Channel:** https://www.youtube.com/@TwoSetAI

**Blogpost about this topic:** https://open.substack.com/pub/mlnotes/p/storm-ai-agents-for-long-form-writing?r=164sm1&utm_campaign=post&utm_medium=web

# **Project Motivation:**

Writing a well-structured and organized piece of content is crucial for effectively conveying information to readers. One of the key elements in achieving this is the use of top-down approach for writing, i.e, nailing down the outline before writing a single word. They provide a framework that guides the writer in presenting information in a logical and coherent manner.

In this project, we will explore an agentic system called STORM, which stands for **Synthesis of Topic Outlines through Retrieval and Multi-perspective Question Asking**.

This method is proposed by Stanford researchers and fully described in this paper "*[Assisting in Writing Wikipedia-like Articles From Scratch with Large Language Models](https://arxiv.org/pdf/2402.14207.pdf)*"

STORM is designed to assist in writing long-form articles by creating topic outlines, discovering diverse perspectives and simulating conversations with topic experts.

STORM can enhance the pre-writing stage, resulting in well-structured and comprehensive articles that rival those found on Wikipedia.

# **Project Scope:**
Due to time constraints, we implemented the method with Claude API in this notebook but didn't have time to implement a UI. We leverage the framework to write a test article on the following topic: **Building A Powerful LinkedIn Presence**. The resulted article can be viewed from the markdown files in this repo. 

There are more things we can improve for this project such as using function calls to stablize the output for pipeline uses downstream, refining outputs, refining prompts, roles and agents architecture etc. 

We also compared result between OpenAI and Claude. Overall, we like the Claude results better in this specific use case. 

![image](https://github.com/angelina-yang/Claude_API_Contest/assets/40750217/48b072ec-c566-4596-ae7b-ecb82d1e3793)


