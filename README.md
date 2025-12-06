<!-- HEADER BANNER -->
<!-- <p align="center">
  <img src="./screenshots/banner.png" alt="Mahaaraaj Banner" width="100%">
</p> -->

<h1 align="center">🍽️ Mahaaraaj — AI Recipe Suggestor</h1>

<!-- <p align="center">
  <strong>Showcase Repository — Code is Private</strong>
</p>

<p align="center">
  Smart AI-based recipe suggestions powered by natural language understanding.
</p>  -->


<p align="center"><strong>Showcase-Only Repository (Main Codebase Is Private)</strong></p>

<p align="center">An AI-driven recipe suggestion app that understands natural-language food queries and recommends the most relevant dishes using a custom-built ML pipeline.</p>

<!-- BADGES -->
<p align="center">
  <img src="https://img.shields.io/badge/Framework-Django-0C4B33?style=for-the-badge" />
  <img src="https://img.shields.io/badge/AI-Google%20Gemini%20Flash-blue?style=for-the-badge" />
  <img src="https://img.shields.io/badge/Frontend-Bootstrap%205-7952B3?style=for-the-badge" />
  <img src="https://img.shields.io/badge/Status-Production%20Demo-brightgreen?style=for-the-badge" />
  <img src="https://img.shields.io/badge/Code-Private-red?style=for-the-badge" />
</p>

---

## 🔗 Live Demo  
👉 **Visit the deployed app:** <a href="https://mahaaraaj.onrender.com" target="_blank">https://mahaaraaj.onrender.com</a>  
_(Note: Free Render tier → first load may take a few seconds due to cold start.)_


---

# ❓ What is Mahaaraaj?

**Mahaaraaj is an AI-powered recipe recommendation web app** that understands free-text cooking queries such as:

> *“I want something with bread, aloo, paneer—veg only.”*

It then returns **structured, accurate recipe suggestions** using a combination of:

- A **custom recipe-intelligence model** that interprets user intent, ingredients, diet, and taste  
- A small Gemini layer used only to structure the text input 
- A fast recipe-matching pipeline that ranks dishes by suitability  
- A clean and responsive UI for browsing suggested recipes

The goal of Mahaaraaj is to make cooking decisions simple, intuitive, and personalized for everyday users.

---

# ⭐ Key Features

<div style="font-size: 0.9rem;">

✔ **Natural-language recipe search**  
✔ **AI interprets ingredients, diet, taste profile, and dish intent**  
✔ **Custom ML recipe engine** (private) for matching and scoring recipes  
✔ **Internal recipe-ranking logic** using similarity and user intention**  
✔ **Fast, lightweight Django backend** for smooth performance  
✔ **Clean & responsive UI** across mobile and desktop  
✔ **Decoupled AI + Recipe Engine Architecture** <!-- — the text-understanding layer stays separate from the core logic for better modularity and security  --><br>
✔ **Fully deployed & production-ready demo**

</div>
---

# 🗂️ High-Level Architecture


```text
User Query
     ↓
Django Backend
     ↓
Structured Prompt → Google Gemini Flash API
     ↓
JSON Response (Dish, Ingredients, Taste Profile, Time)
     ↓
Recipe Engine → Filters + Ranking
     ↓
Browser UI → Recipe Cards Shown to User
```

---

# 🧰 Tech Stack

### **Backend**
- Python  
- Django  
- Gunicorn  
- Env-based configuration  

### **AI Layer**
- Google Gemini Flash → Converts natural text → structured JSON  
- Custom structured prompting  
- Strict JSON response enforcement
- Beyond text structuring, all decision-making and recipe ranking are performed by my own ML system(Recipe Engine)

### **Recipe Engine (Private)**
- Ingredient similarity  
- TF-IDF / vector preprocessing (internal)  
- Taste & diet filtering  
- Ranking logic  
- Efficient lookup

### **Frontend**
- Django Templates  
- Bootstrap 5  
- Responsive card grid UI  

### **Deployment**
- Render.com  
- GitHub Auto Deploy  
- Secure environment variables  

---



# 🔒 Why the Code is Private
  
To maintain security and protect the internal logic, **the full implementation is stored in a private repo**.  

<!--I want this project to stay safe, secure, and fairly presented as my own work. --> 

The private repo contains:

- My custom recipe engine logic  
- Dataset + preprocessing scripts  
- Prompting strategy and pipeline design
- Recipe ranking algorithms   
- API key handling  
- Internal scoring formulas  

To prevent accidental misuse, cloning, or exposure of sensitive logic, the full implementation is kept private.  
This public repository exists **only to showcase the app, its design, and its capabilities** in a safe, professional, and transparent way.

This public repo contains:

- README  
- Screenshots  
- System explanation  
- Live demo link  

---



# 📸 Screenshots

### 🏠 Home Page
![Home Page](./screenshots/home-page.png)
<img width="1918" height="437" alt="Screenshot 2025-12-06 172346" src="https://github.com/user-attachments/assets/d95647ea-c4ba-4add-a7be-a79c59638657" />


### 🔎 Results Page
![Results Page](./screenshots/results-page.png)
<img width="1262" height="950" alt="Screenshot 2025-12-06 172754" src="https://github.com/user-attachments/assets/6eac6c24-b2dd-4b60-a89c-9f2268c6e35a" />
<img width="1152" height="966" alt="Screenshot 2025-12-06 172701" src="https://github.com/user-attachments/assets/4b417452-7245-4a98-bde8-9c90101d6a41" />

*(Upload your actual PNG files and ensure names match.)*

---

# 🧾 Summary

Mahaaraaj demonstrates:

- Full-stack engineering  
- AI integration  
- Prompt engineering  
- UI design  
- Deployment & architecture planning  

It solves a very relatable daily problem:

> *“I have ingredients… what can I cook today?”*

<!--
- AI integration + structured interpretation  
- Custom ML pipeline design  
- Backend engineering  
- Clean UI development  
- Deployment & environment management  
- Turning an idea → product → live demo  

The result is a smooth tool that solves a familiar problem:

> *“I have ingredients… what can I cook today?”* -->

Technical enough for engineers.  
Simple enough for everyday users.


---

# 👤 Author

**Raghav Singhal**    
- GitHub: <a href="https://github.com/RSV851" target="_blank">https://github.com/RSV851</a>  
- Live App: <a href="https://mahaaraaj.onrender.com" target="_blank">https://mahaaraaj.onrender.com</a>  
- Location: India


---




