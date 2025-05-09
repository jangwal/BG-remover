﻿# BG-remover
# BG_REMOVER
# BG_REMOVER
## 📂 Project Structure
BG-remover/
├── .gitignore
├── README.md
├── codelab_2/
│   ├── ai_api_101/
│   │   ├── main.py
│   │   └── services/
│   │       └── bg_remover.py
│   ├── config.json
│   └── requirements.txt
# BG Remover 🖼️➡️🔲

[![FastAPI](https://img.shields.io/badge/FastAPI-005571?style=for-the-badge&logo=fastapi)](https://fastapi.tiangolo.com/)
[![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)](https://www.python.org/)
[![Uvicorn](https://img.shields.io/badge/Uvicorn-000000?style=for-the-badge)](https://www.uvicorn.org/)

---

## 📋 Description

**BG Remover** is a simple and fast API service that automatically removes the background from uploaded images.  
Built using **FastAPI**, **Python**, and the **rembg** library, it provides a quick and easy way to remove backgrounds for your projects.

---

## 🚀 Features
- Upload an image and instantly get the background removed.
- Built with FastAPI for high performance and speed.
- API documentation auto-generated at `/docs`.
- Easy to integrate into any app or service.

---

## 🛠️ Tech Stack
- **Python 3**
- **FastAPI**
- **Uvicorn** (ASGI server)
- **rembg** (background removal library)

---
IN YOUR VS CODE TERMINAL GIVE COMMAND :-
pip install fastapi uvicorn pillow python-dotenv requests aiofiles


1. Clone the repository:
   ```bash
   git clone https://github.com/jangwal/BG-remover.git
   
2. cd BG-remover
3. pip install -r codelab_2/requirements.txt
4. uvicorn codelab_2.ai_api_101.main:app --reload --port 8001
5. http://127.0.0.1:8001/docs


