# Skill Horizon – AI-Powered Course Recommendation System

> 🔍 Bridging the skill gap with intelligent, personalized course recommendations powered by LLMs, real-world data, and semantic search.

## 📌 Overview

Skill Horizon is an AI-driven platform that leverages **real-world job listings** and **authentic course reviews** to identify skill gaps in job seekers and recommend highly personalized online courses. By combining job market analysis, course data scraping, vector-based semantic search, and LLM reasoning, the system delivers recommendations that reflect both **industry demand** and **user-specific learning needs**. 

Users can enter **natural language queries** like “real-world projects, hands-on labs, beginner-friendly” to get course suggestions that **align with their actual preferences**, extracted directly from what real learners have said about the course—making the output more grounded, honest, and actionable.

> 🚀 Developed as a Hackathon Project at **HackHound 3.0**

---

## 🎯 Objective

- Analyze a user’s profile (job title, experience, and skills)
- Detect missing skills by scraping and analyzing **real-world job listings**
- Recommend the most relevant **real-world online courses**
- Accept **natural language input** for fine-grained user preferences
- Leverage **authentic user reviews** to uncover the real value of a course
- Use LLMs and vector databases to deliver the most **specific and beneficial** courses

---

## 🛠️ Tech Stack

- **Languages & Tools**: Python, MongoDB, Playwright, Scrapy
- **AI/ML**: LangChain, FAISS, LLMs (Encoders & Decoders), Vector Embeddings
- **Web Scraping**: Scrapy, Playwright
- **Data Storage**: MongoDB
- **NLP & Retrieval**: Semantic search with FAISS + LangChain for vector search and RAG pipeline

---

## ⚙️ How It Works

### 🔹 Step 1: Job & Skill Gap Analysis

1. User inputs:  
   `Job Title`, `Years of Experience`, and `Current Skills`

2. Backend process:  
   - Scrapes **live job listings** using Playwright & Scrapy
   - Extracts required skills from job descriptions
   - Compares with user skills to detect personalized skill gaps

---

### 🔹 Step 2: Course Recommendations

1. Scrapes **real-world courses and reviews** from platforms like Coursera, Udemy, and edX
2. Courses ranked based on:
   - Enrollments
   - Ratings
   - **Authentic learner feedback**
3. Relevance determined through skill-gap mapping

---

### 🔹 Step 3: Semantic Search + LLM Personalization

1. User enters personal preferences in **natural language** (e.g., _"real-world projects, labs, beginner-friendly"_)
2. FAISS + LangChain used to semantically search within **course descriptions and user reviews**
3. An LLM analyzes and ranks results to suggest **the most relevant, honest, and specific courses** that match both the job requirements and the user’s expressed intent

---

## 💡 Example

**User Input:**  
- Job: Cyber Security  
- Skills: Linux, Network Security  
- Experience: 2–4 years  
- Query: _"real-world projects, lab practicals, and basics covered in detail"_

**🔍 Output Recommendation:**  
✅ **Recommended Course:**  
📌 _Course Name_  
🔗 _Course Link_  
📖 _Why was this course recommended?_  
_This course covers foundational topics in depth, includes lab-based learning, and matches your preference for real-world, hands-on content—as reflected in user reviews._

---

## 📈 Future Enhancements

- Add resume upload & NLP parsing
- Build user learning paths using curriculum planning
- Enable feedback loop to improve recommendations
- Visual dashboards for in-demand skill tracking

---

## 👥 Collaborators

- **Harsh Gupta**: Developed Generative AI for course selection, semantic search with vector DB, and integrated LLM-based personalization from natural language input.
- **Aditya Maurya** & **Saurabh Tripathi**: Scraped **real-world job listings** and courses; handled data ingestion and MongoDB optimization.
- **Shivangi**: Crafted and delivered the pitch presentation.

---

## 🤝 Contributing

Pull requests and suggestions are welcome! If you'd like to contribute, fork the repo and open a PR.

---

## 📬 Contact

**Harsh Gupta**  
📧 [harshnkgupta@gmail.com](mailto:harshnkgupta@gmail.com)  
🔗 [LinkedIn](https://www.linkedin.com/in/harsh-gupta-2021) | [Portfolio](https://datascienceportfol.io/harshgupta)

---

## 📄 License

This project is licensed under the MIT License – see the [LICENSE](LICENSE) file for details.
