# 🌐 Teacher’s Hub Website

This is a multilingual educational website for teachers and students.  
It supports **English, தமிழ் (Tamil), and සිංහල (Sinhala)** and includes **AI tools** to help with lesson planning, quiz generation, and text simplification.  

---

## 🚀 Features
- ✅ Multilingual support (English / Tamil / Sinhala)  
- ✅ AI-powered tools (Lesson Plan Generator, Quiz Maker, Text Simplifier)  
- ✅ Built with pure **HTML, CSS, JavaScript** (no frameworks required)  
- ✅ Free hosting using **GitHub Pages**  

---

## 📂 Project Structure
```

teacher-website/
│
├── index.html    # Main website file
├── README.md     # Documentation (this file)

````

---

## 🛠️ Setup Instructions

### 1. Run Locally
1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/teacher-website.git
````

2. Open `index.html` in your browser.
   (Or install **Live Server** extension in VS Code for auto refresh.)

---

### 2. Deploy Online (GitHub Pages)

1. Go to **Settings → Pages** in this repo.
2. Under “Source”, select **Deploy from branch → main → root**.
3. Save and wait 1–2 minutes.
4. Your website will be live at:

   ```
   https://your-username.github.io/teacher-website/
   ```

---

## 🤖 AI Integration

The website uses **Hugging Face free models** for AI features.
To enable AI:

1. Create a free account at [HuggingFace](https://huggingface.co)
2. Get an API token from **Settings → Access Tokens**
3. Replace `hf_xxxxxxxxxxxxx` in `index.html` with your token

Example:

```javascript
headers: { "Authorization": "Bearer hf_yourtokenhere" }
```

---

## 📸 Preview

Here’s what the site looks like:

* 🌐 Multilingual language switcher
* 🤖 AI tools section (Lesson plan, Quiz, Simplify text)
* 📘 Teacher-friendly interface

---

## 📝 License

This project is free to use and modify.
You can build your own teacher tools on top of it! 🎉

```
