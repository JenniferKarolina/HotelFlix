# 🎬 HotelFlix

**HotelFlix** es un proyecto de análisis de datos y desarrollo de aplicación web que busca crear un **“Netflix para hoteles”**:  
un recomendador inteligente que muestra hoteles en un catálogo visual estilo streaming, con fichas en vídeo y sugerencias personalizadas según el perfil del viajero.

---

## 🎯 Objetivo
Reducir la incertidumbre al elegir hotel y mejorar la experiencia del viajero mediante un sistema de recomendación que va más allá del precio,  
tomando en cuenta **amenities, perfil de usuario, reseñas y estacionalidad**.

---

## 👥 ¿Para quién?
- **Viajeros** → encontrar hoteles que encajen con su perfil (business, familia, lujo, mochilero).  
- **Hoteles / Cadenas** → aumentar visibilidad y conversión con contenido en vídeo.  
- **TravelTech / OTAs** → prototipo de herramienta innovadora de recomendación.  

---

## 📊 Dataset
El proyecto combina varias fuentes abiertas y públicas:
- **Open Data Barcelona** → catálogo oficial de hoteles en la ciudad.  
- **TripAdvisor Reviews (Kaggle)** → reseñas textuales para análisis NLP ligero.  
- **AENA (Estadísticas)** → datos de llegadas de pasajeros para añadir señal estacional.  

Dataset final → `data/processed/hotels_final.csv`

---

## 🛠️ Stack tecnológico
- **Python (pandas, numpy, scikit-learn)** → limpieza, feature engineering, recomendador.  
- **NLP básico** → extracción de keywords de reseñas para etiquetar hoteles.  
- **Streamlit** → desarrollo de app web interactiva.  
- **GitHub** → control de versiones y portfolio público.  

---

## 📂 Estructura del proyecto
```bash
HotelFlix/
├─ data/
│  ├─ raw/         # datasets originales
│  ├─ interim/     # pasos intermedios de limpieza
│  └─ processed/   # dataset final para la app
├─ scripts/        # ETL paso a paso (Python)
├─ app/            # aplicación en Streamlit
├─ README.md       # este archivo
└─ requirements.txt

---

## 🚀 Roadmap
1. Limpieza del dataset de hoteles (Open Data BCN).  
2. Enriquecimiento con amenities y vídeos.  
3. Generación de etiquetas por perfil usando reviews (NLP ligero).  
4. Señal de popularidad estacional con datos de AENA.  
5. Desarrollo de la app en Streamlit con carruseles estilo Netflix.  
6. Despliegue en **Streamlit Cloud** con demo pública.  

---

## 📌 Estado actual
✅ Repositorio creado y estructurado.  
🔜 Limpieza inicial del dataset de hoteles.  

---

## 👩‍💻 Autora
Proyecto desarrollado por Karolina,  
Master en Economía y Negocios Internacionales, con foco en **Turismo y Data Analytics**.  

---
