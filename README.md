# IBM RAG and Agentic AI - Coursework

This repository serves as a centralized collection of exercises, labs, and minor projects completed as part of the **IBM RAG and Agentic AI Professional Certificate / Specialization** on Coursera. It documents my learning journey through this comprehensive 8-course program, focusing on **Retrieval Augmented Generation (RAG)** and the development of **intelligent AI agents**.

---

## 📑 Table of Contents

- [Program Overview](#program-overview)
- [Course Breakdown](#course-breakdown)
- [Technologies Covered](#technologies-covered)
- [Getting Started](#getting-started)
- [Contributing](#contributing)
- [License](#license)
- [Contact](#contact)

---

## 🎓 Program Overview

The "IBM RAG and Agentic AI" program is designed to provide a deep understanding and practical skills in building advanced AI applications. It covers:

- The fundamentals of Generative AI
- The intricacies of Retrieval Augmented Generation (RAG) using vector databases
- The cutting-edge field of AI Agents using frameworks such as:
  - LangChain
  - LangGraph
  - CrewAI
  - AutoGen

---

## 📘 Course Breakdown

This program consists of 8 courses. Below is an overview of each, along with links to dedicated project repositories where applicable.

### **Course 1: Develop Generative AI Applications: Get Started**  
**Status:** Complete  
**Description:** Introduces the core concepts of Generative AI and provides foundational knowledge for building initial AI applications.  
**Key Project:** *(None significant – foundational exercises included in this repo)*

---

### **Course 2: Build RAG Applications: Get Started**  
* **Status:** ✅ Complete  
* **Description:** Focuses on the fundamentals of Retrieval Augmented Generation (RAG), explaining how to combine LLMs with external knowledge bases for more accurate and context-aware responses.  
* **Associated Files:** [Rag_pipeline](https://github.com/AliAbdallah21/IBM-RAG-Agentic-AI-Coursework/blob/main/Course_2_Develop-Generative-AI-Applications-Get-Started/RAG_pipeline.ipynb) - A practical Implementation of the RAG Pipeline
* **Key Project:** [LinkedIn Icebreaker Bot](https://github.com/AliAbdallah21/RAG-Icebreaker-Gradio-ChatBot) – A practical chatbot using RAG to generate personalized networking messages.


---

### Course 3: Vector Databases for RAG: An Introduction
* **Status:** ✅ Complete
* **Description:** Explores the role of vector databases in RAG systems, covering key concepts, architecture, and practical usage (e.g., ChromaDB).
* **Content in this repo:** Notebooks and exercises related to understanding vector database concepts and basic interactions.
* **Associated Files:** [ChromaDB Helper Script](https://github.com/AliAbdallah21/IBM-RAG-Agentic-AI-Coursework/blob/main/Course_3_ChromaDB_Setup_Lab/ChromaDB_Filtering.ipynb)
* **Key Projects:**
    * [Employee Records Search with ChromaDB](https://github.com/AliAbdallah21/ChromaDB-Employee-Records-Search) – An application demonstrating employee record management and search using ChromaDB.
    * [Intelligent Food Recommendation System](https://github.com/AliAbdallah21/Food-Recommendation-System) – A comprehensive application demonstrating semantic search, advanced filtering, and RAG chatbot capabilities using ChromaDB and OpenAI.

---
### Course 4: Advanced RAG with Vector Databases and Retrievers
* **Status:** ✅ Completed  
* **Description:** This course covers advanced techniques for Retrieval-Augmented Generation (RAG), focusing on retriever strategies and optimization. It explores how to leverage vector databases for more efficient retrieval and enhance RAG workflows with sophisticated retriever designs.  
* **Content in this repo:** Hands-on labs and notebooks demonstrating advanced retriever implementations.  
* **Associated Files:**
    * [Parent Document Retriever Example](https://github.com/AliAbdallah21/IBM-RAG-Agentic-AI-Coursework/blob/main/Course_4_Advanced_Retrievers_Lab/Parent_Document_Retriever_Example.ipynb)  
    * [Self Query Retriever Example](https://github.com/AliAbdallah21/IBM-RAG-Agentic-AI-Coursework/blob/main/Course_4_Advanced_Retrievers_Lab/Self_Query_Retriever_Example.ipynb)  
    * [Vector Store Backed Retriever Example](https://github.com/AliAbdallah21/IBM-RAG-Agentic-AI-Coursework/blob/main/Course_4_Advanced_Retrievers_Lab/Vector_Store_Backed_Retriever.ipynb)  
    
    * [Multi-Query Retriever Example](https://github.com/AliAbdallah21/IBM-RAG-Agentic-AI-Coursework/blob/main/Course_4_Advanced_Retrievers_Lab/Multi_Query_Retriever.ipynb)  
* **Key Projects:** 
    * [Advanced Retrievers in LlamaIndex repository](https://github.com/AliAbdallah21/Advanced-Retrievers-in-LlamaIndex) - Implementation of core retriever concepts
    * [AI-Powered YouTube Summarizer](https://github.com/AliAbdallah21/AI-Powered-YouTube-Summarizer) - Practical application of RAG for video content analysis and Q&A


---

### **Course 5: Build Multimodal Generative AI Applications**  
* **Status:** Started  
* **Description:** Expected to cover Generative AI applications that integrate multiple data types, such as text, images, and audio.  

* **Associated Files:**  
  * [Text To Speech Generation using `facebook_mms_tts`](https://github.com/AliAbdallah21/IBM-RAG-Agentic-AI-Coursework/blob/main/Course_5_Build-Multimodal-Generative-AI-Applications/facebook_mms_tts.ipynb)  
  * [Speech To Text Generation using `facebook_wav2vec2_stt`](https://github.com/AliAbdallah21/IBM-RAG-Agentic-AI-Coursework/blob/main/Course_5_Build-Multimodal-Generative-AI-Applications/facebook_wav2vec2_stt.ipynb)  
  * [AI Meeting Assistant](https://github.com/AliAbdallah21/ai-meeting-assistant)  
    - Transcribes meeting audio using Whisper (transformers).  
    - Normalizes financial product terminology (e.g., “401k” → “401(k) retirement savings plan”).  
    - Generates structured **Meeting Minutes** and a **Task List** using an OpenAI chat model via LangChain.  
    - Exposes a simple web UI with Gradio for upload and download.
   
  * [Image generation Using Open AI's DALL-E-2, and DALL-E-3](https://github.com/AliAbdallah21/IBM-RAG-Agentic-AI-Coursework/blob/main/Course_5_Build-Multimodal-Generative-AI-Applications/DALL%20E%20Image%20generation%20Guide%20for%20Beginners.ipynb)
  * [Image analysis Using meta-llama/llama-4-maverick](https://github.com/AliAbdallah21/IBM-RAG-Agentic-AI-Coursework/blob/main/Course_5_Build-Multimodal-Generative-AI-Applications/ImagesAnalyzer_.ipynb)
  * [A pdf highlights how to use the advanced multi modal applications](https://github.com/AliAbdallah21/IBM-RAG-Agentic-AI-Coursework/blob/main/Course_5_Build-Multimodal-Generative-AI-Applications/Advanced%20Multimodal%20Applications.pdf)
  * [An intelligent Flask web application that analyzes food images and provides detailed nutritional information using AI-powered image recognition and nutritional analysis.](https://github.com/AliAbdallah21/AI-Nutrition-Coach)

* **Key Projects:**
    * [StyleFinder](https://github.com/AliAbdallah21/StyleFinder) - A web application for fashion analysis using computer vision, vector similarity search, and a multi-modal LLM.
    


---

### **Course 6: Fundamentals of Building AI Agents**  
**Status:** Not Started  
**Description:** Will introduce the core principles and architectures behind building autonomous AI agents.  
**Key Project:** *(To be added if applicable)*

---

### **Course 7: Agentic AI with LangChain and LangGraph**  
**Status:** Not Started  
**Description:** Expected to delve into practical agent development using popular frameworks like LangChain and LangGraph.  
**Key Project:** *(To be added if applicable)*

---

### **Course 8: Agentic AI with LangGraph, CrewAI, AutoGen and BeeAI**  
**Status:** Not Started  
**Description:** Will cover advanced agentic AI concepts and implementation using cutting-edge tools like CrewAI, AutoGen, and BeeAI.  
**Key Project:** *(To be added if applicable)*

---

## 🧰 Technologies Covered

Across this program, the following technologies and concepts are explored:

- **Programming Languages:** Python, R  
- **AI/ML Frameworks:** LlamaIndex, LangChain, LangGraph, CrewAI, AutoGen, BeeAI  
- **Generative AI Models:** Large Language Models (LLMs), ChatGPT  
- **Vector Databases:** ChromaDB (and potentially others)  
- **Data Science Libraries:** Pandas, NumPy, Scikit-learn, Matplotlib, Seaborn  
- **Web Frameworks (for apps):** Node.js, Express.js  
- **Version Control:** Git, GitHub  
- **Development Environments:** Jupyter Notebooks, Google Colab

---

## 🚀 Getting Started

To explore the notebooks and exercises in this repository:

### 1. Clone the repository:

```bash
git clone https://github.com/AliAbdallah21/IBM-RAG-Agentic-AI-Coursework.git
cd IBM-RAG-Agentic-AI-Coursework

```

### 2. Install dependencies

It's recommended to create a virtual environment first.
```bash
pip install -r requirements.txt

```

*(Note: A `requirements.txt` will be added as you progress through the courses and use new libraries.)*

### 3. Run the Notebook

You can open the `.ipynb` files in Jupyter Lab, VS Code, or Google Colab.

---

## 👋 Contributing

This repository is primarily for my personal coursework. However, if you find issues or have suggestions, feel free to open an issue or submit a pull request.

---

## 📄 License

MIT © 2025 Ali Abdallah

---

## ✉️ Contact

Ali Abdallah
📧 aliabdalla2110@gmail.com
GitHub: [AliAbdallah21](https://github.com/AliAbdallah21)
