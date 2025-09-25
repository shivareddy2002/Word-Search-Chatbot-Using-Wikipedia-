
# 📘 PICTOPEDIA – Word Search Chatbot Using Wikipedia  


<img width="278" alt="image" src="https://github.com/user-attachments/assets/c9e79365-bc9d-4468-be03-61aea052b0c4" />



**PICTOPEDIA** is a chatbot that allows users to search for information on specific words or terms using the Wikipedia API. It works like an **interactive word-search assistant**, where users can input queries and instantly receive relevant, real-time information.

## 🔗 Live Demo  
👉 [**PICTOPEDIA Chatbot**](https://shivareddy2002.github.io/Word-Search-Chatbot-Using-Wikipedia-/)  

---

## 🚀 Project Overview  

**How It Works (Step-by-Step):**

1. **User Input** → User types a query in the chatbot.  
   *Example:* `"What is Artificial Intelligence?"`  

2. **Input Handling** → Input validated and handled by `handleUserInput()` in `script.js`.  

3. **API Request** → Sends request to **Wikipedia API** for relevant information.  

4. **Response Processing** → Extracts and formats the response.  

5. **Displaying Results** → Shows content in a **chat-style interface**.  

6. **Interaction Loop** → Supports multiple queries with **chat history retention**.  

➡️ **Flow Summary:**  
User Input ➡️ Input Handling ➡️ API Request ➡️ Response Processing ➡️ Display Results ➡️ Repeat Interaction  

---

## ✨ Features  

- 🖥️ **Simple & Interactive UI** – Clean and user-friendly interface.  
- ⚡ **Real-Time Retrieval** – Fetches data live from Wikipedia.  
- 💬 **Chat-Style Display** – Results presented conversationally.  
- 🔄 **Multi-Search Support** – Keeps chat history during session.  
- ❌ **Error Handling** – Provides fallback messages if data not found.  

---

## 🛠️ Technologies Used  

- **HTML5, CSS3** – UI design & layout.  
- **JavaScript (ES6)** – Logic, event handling & API calls.  
- **Wikipedia API** – Fetches word/term information.  

---

## 🔮 Future Enhancements 

Below are **ready-to-drop code snippets** you can paste into your project to implement the five enhancements:

- 🔊 **Text-to-Speech (TTS)**
- 🌐 **Multiple-language support (Wikipedia language domains)**
- 🎨 **UI/UX themes (theme presets + CSS variables)**
- 📱 **Mobile responsive layout (CSS breakpoints & flexible layout)**
- 💾 **Download chat history (JSON / TXT export)**

---

## 👨‍💻 Author

**LOMADA SIVA GANGI REDDY**

---

## 📂 Project Flow  

```mermaid
flowchart LR
A[User Input] --> B[Input Handling]
B --> C[Wikipedia API Request]
C --> D[Process Response]
D --> E[Display Results]
E --> F[Interaction Loop]

