# Greetings, I'm Minh Duc 

AI Student at HCM University of Science (HCMUS), interested in building practical AI systems and exploring how AI can be integrated into real-world applications.

## 🎯 Interests

* Artificial Intelligence, Machine Learning & Deep Learning 
* Large Language Models & RAG
* Multimodal AI
* AI Application Development

## 🛠️ Technologies

**Programming:** Python, C++, SQL

**Deep Learning and Frameworks:** PyTorch, TensorFlow, Scikit-learn, Hugging Face Transformers, OpenCV,
ONNX

**Generative AI and Search:** Large Language Models (LLMs), RAG, LangChain, Multimodal Embeddings (SigLIP-2,
CLIP), Whisper (ASR), BM25, Reciprocal Rank Fusion (RRF)

**Vector Databases and Storage:** FAISS, Milvus, SQLite, Firebase / Firestore

**Backend and MLOps:** FastAPI, RESTful APIs, Docker, Ollama, Git / GitHub
## 🚀 Featured Projects

### MOSAIC - Interactive Vietnamese Video Retrieval System 

* Architected a multimodal video retrieval system for sequential natural-language queries over 1,487 videos (397,591 keyframes): an LLM query decomposer, dense retrieval (SigLIP-2, Moondream captions) and sparse retrieval (Florence-2 OCR, Whisper ASR, YOLO objects), fused with adaptive weighted Reciprocal Rank Fusion, followed by a two-stage global--local search.
* Used SigLIP-2 embeddings with FAISS inner-product indices on GPU to run large-scale similarity search over the keyframe corpus.
* Designed two $O(N\cdot K)$ temporal dynamic-programming algorithms, PANDA (bidirectional ideal-gap penalty) and ANCHOR (anchor-event alignment with a bounded asymmetric penalty), to stitch keyframes into ordered event sequences. On a 36-query benchmark (123 events), they raised temporal monotonicity from 36.11\% to 100\% and sequence accuracy from 8.33\% to 13.89\%, with PANDA aligning in 0.28\,s per query.
  
### ARCampus-HCMUS — AI AR Campus Explorer

* Developed a Unity-based mobile application combining Augmented Reality (AR) navigation and an AI chatbot to
help students explore and navigate the HCMUS campus.
* Integrated GPS, compass, A* pathfinding, 2D maps, and AR waypoints for real-time outdoor navigation, along
with indoor map support.
* Built an AI chatbot pipeline with intent classification, entity extraction/linking, context retrieval from Firebase/Firestore,
conversation history, and LLM-based response generation
* Integrated Firebase, FastAPI, SQLite, and Ollama to support authentication, campus data management, and AI
services

### Smart EV Journey - Interactive tool for electric cars drivers and investors 

* Developed an EV charging recommendation engine that filters stations by connector compatibility and battery reachability, then ranks them
using arrival-time occupancy, estimated wait and charging time, route detour, and battery reserve.
* Built a SimPy charging-session simulator and an offline pipeline for training six horizon-specific XGBoost occupancy models, forecasting
5--30 minutes ahead from 40 temporal and spatial features using synthetic data.
* Implemented a map-based station-planning feature for Ho Chi Minh City that ranks candidate sites by demand potential, marginal coverage,
grid and site readiness, and network gaps, with results served through versioned FastAPI endpoints.

## 📫 Contact

* GitHub: [@tlmduc7796](https://github.com/tlmduc7796)
