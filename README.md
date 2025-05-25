# 📖 Dictionary App

## 🌟 Overview
The **Dictionary App** is a simple and interactive web application that allows users to search for word definitions, phonetics, synonyms, and antonyms using an online dictionary API. Built with a user-friendly UI, it provides a seamless experience for learning new words.

## 🚀 Features
- 🔍 Search for word meanings
- 🎙 Pronunciation & phonetics
- 📚 Synonyms & antonyms
- 📖 Example usage in sentences
- 🌐 Responsive and attractive UI

## 🛠 Tech Stack
- **Frontend:** HTML, CSS, JavaScript
- **Backend:** None (Uses API calls)
- **API Used:** [Free Dictionary API](https://dictionaryapi.dev/)

## 📂 Project Structure
```
📁 dictionary-app/
├── 📄 index.html       # Main HTML file
├── 📄 style.css        # Styling file
├── 📄 script.js        # JavaScript for API calls and UI interactions
├── 📄 README.md        # Documentation
```

## 🎨 UI & Design
The UI follows a modern **orange-gradient** theme with a search box at the center. Waves animation enhances the visual appeal at the bottom.

## 🔧 How to Use
1. Open the **index.html** file in a browser.
2. Type a word in the search bar.
3. Click on the **Search** button.
4. View the meaning, pronunciation, and other details.

## 🌍 API Integration
The app fetches data from the **Free Dictionary API**:
```js
fetch(`https://api.dictionaryapi.dev/api/v2/entries/en/{word}`)
  .then(response => response.json())
  .then(data => console.log(data));
```

## 📌 Setup & Deployment
1. Clone the repository:
   ```bash
   git clone https://github.com/YOUR-USERNAME/dictionary-app.git
   ```
2. Open `index.html` in a browser.
3. Deploy using GitHub Pages, Netlify, or Vercel.

## 📜 License
This project is open-source and available under the **MIT License**.

---
