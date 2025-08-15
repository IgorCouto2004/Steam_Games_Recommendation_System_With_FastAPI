# 🎮 Steam Games Recommendation System with FastAPI  

**Sistema de recomendação de jogos da Steam** usando similaridade de conteúdo (cosine similarity) e expondo recomendações via API REST com FastAPI.  

[![Python](https://img.shields.io/badge/Python-3.9%2B-blue)](https://www.python.org/)
[![FastAPI](https://img.shields.io/badge/FastAPI-0.68.0-green)](https://fastapi.tiangolo.com/)
[![Scikit-learn](https://img.shields.io/badge/scikit--learn-1.0.2-orange)](https://scikit-learn.org/)  

---

## 📌 Visão Geral  
O sistema analisa características de jogos da Steam para recomendar títulos similares através de uma API.  

**Funcionalidades**:  
- ✅ Endpoint `/recommend/{game_id}` retorna jogos similares em JSON.  
- ✅ Modelo baseado em **similaridade de cosseno** (TF-IDF + matriz de similaridade).  
- ✅ Integração simples com front-ends ou aplicativos.  
