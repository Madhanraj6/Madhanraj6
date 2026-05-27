# Hey, I'm Madhan 👋

**AI/ML Engineer** building end-to-end production systems from data to inference.

I take complex ML problems and ship them—from computer vision pipelines processing real-world images to agentic RAG systems that actually work. Obsessed with reliability, observability, and measurable impact.

---

## 🎯 What I Do

- **Production ML Systems**: End-to-end pipelines from raw data to deployed models
- **Computer Vision**: OCR, object detection, real-time image processing in field conditions
- **Generative AI**: LLM fine-tuning, agentic RAG, corrective retrieval-augmented generation
- **ML Infrastructure**: Docker, AWS (Lambda, S3, ECR), serverless deployments
- **Data-Driven Engineering**: Diversity-aware data selection, validation frameworks, systematic testing

---

## 💼 Current Work

**AI/ML Engineer @ Sujanix** *(Sep 2024 – Present)*

### Meter OCR Pipeline
Built an end-to-end computer vision system that reads meter displays in the field with **95–97% accuracy** across diverse lighting and angles.
- YOLO v8 for robust meter detection
- Custom OCR model (ViT-Small + BiLSTM-CTC) with intelligent preprocessing
- Deployed as serverless Flask API on AWS Lambda via ECR
- Structured logging + metadata tracking for production observability

### Diversity-Aware Data Selection
Engineered a pipeline that identifies blind spots in training data.
- Convert images → high-dimensional vectors → PCA/UMAP reduction
- HDBSCAN clustering to find unique patterns
- **Result**: Better model generalization on edge cases without collecting more data

### Production Reliability
- **Validation modules** catch blurred, rotated, low-quality images before inference
- **AWS infrastructure** with S3 for centralized output storage
- **Systematic evaluation** with holdout sets for regression testing before updates

---

## 🚀 Recent Projects

### AI Research Assistant
**Corrective Agentic RAG over 500+ ML papers**
- Built with LangGraph for autonomous agent orchestration
- Dual-layer relevance filtering reduces hallucination by 35%
- Live arXiv scraping + FAISS vector indexing
- [Repository](https://github.com/Madhanraj6)

### Bug Report Extractor
**Fine-tuned Llama 3.2 3B on 4,800+ scraped bug reports**
- QLoRA for efficient instruction fine-tuning
- 49% training loss reduction
- 100% valid JSON output compliance
- Exported to GGUF for CPU inference

### Local Coding Agent
**FastAPI + Ollama agentic pipeline with sandbox execution**
- Planner-Coder-Reviewer architecture
- BM25 + semantic hybrid search for document-grounded RAG
- Server-Sent Events for real-time token streaming

---

## 🛠️ Tech Stack

**Languages & Fundamentals**
```
Python | SQL | NumPy | Pandas | Scikit-learn
```

**GenAI & LLMs**
```
PyTorch | HuggingFace | PEFT (QLoRA) | LangChain | LangGraph | Ollama
```

**Computer Vision**
```
YOLO v8 | OpenCV | OCR (ViT + BiLSTM) | TensorFlow Lite | PyTorch
```

**Engineering & Deployment**
```
AWS (Lambda, S3, ECR) | Docker | FastAPI | Flask | FAISS | Git
```

---

## 📚 Education

**B.E. Computer Science and Engineering**  
Dhirajlal Gandhi College of Technology, Tamil Nadu  
GPA: 8.26/10 | 2020–2024

**Certifications**
- Getting Started with AWS Services (Simplilearn)
- Introduction to Model Context Protocol (Anthropic)

---

## 🔗 Connect With Me

- **GitHub**: [github.com/Madhanraj6](https://github.com/Madhanraj6)
- **LinkedIn**: [linkedin.com/in/madhanraj-anandhan](https://www.linkedin.com/in/madhanraj-anandhan/)
- **Email**: madhanraj6522@gmail.com
- **Phone**: +91 88706 08335

---

## 📌 Let's Talk

Interested in discussing ML systems, agentic AI, production computer vision, or opportunities? Reach out—I'm excited about building reliable, impactful systems.

*Location: Bengaluru | Open to relocation: Chennai*
