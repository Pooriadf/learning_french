# 🇫🇷 French Vocabulary Flashcards

A modern, interactive, single-page web application designed to help learners master essential French vocabulary from levels **A1** to **B2** with a focus on Glassmorphism, smooth animations, and a mobile-first "Apple-like" user experience.

## 🚀 Live Demo
[Click here to practice French!](https://pooriadf.github.io/learning_french/flashcards_A1.html)

## ✨ Features
- **Comprehensive Curriculum:** Covers CEFR levels A1, A2, B1, and B2 (approx. 2000 words & expressions).
- **iOS Aesthetic:** Beautiful mesh gradients, glassmorphism effects, and San Francisco typography.
- **Interactive Learning:**
   - 3D Flip Effect: Click or tap the card to reveal the translation and example sentence.
   - Smart Navigation: Keyboard shortcuts (Arrows, Spacebar) and touch-friendly controls.
   - Shuffle Mode: Randomize the deck for better retention.

- Categorization: Words are organized by grammatical type (Verbs, Nouns, Adjectives) and themes (Travel, Business, Emotions).

- Contextual Learning: Every card includes a French example sentence with its English translation.

- Zero Dependencies: Pure HTML, Vanilla JavaScript, and Tailwind CSS (via CDN). No build step required!

## 📚 Levels Included
The application is split into four distinct modules, linked together via a navigation bar:

Level | Focus| Word Count | Target Audience|
--- | --- | --- | --- 
**A1** | Beginner| 500| Basic survival, introductions, food, numbers.
**A2**| Elementary| 500| Daily routine, travel, simple past/future, descriptions.
**B1**| Intermediate| 500| Opinions, feelings, abstract concepts, professional life.
**B2**| Upper Int.| 150| Complex arguments, debate, nuances, idioms, politics.

## 🛠️ Tech Stack
- HTML5: Semantic structure.CSS3: Advanced animations (3D transforms, backdrop-filters).

- Tailwind CSS: For rapid, responsive styling.

- Vanilla JavaScript: Handles state management, DOM manipulation, and logic (no heavy frameworks like React or Vue).

## 🎨 Customization
Want to add your own words? It's easy!
1. Open any of the HTML files (e.g., flashcards_B1.html) in a text editor (VS Code, Notepad++).
2. Scroll down to the <script> tag.
3. Locate the masterDeck array.
4. Add a new object to the list following this format:
```
{ 
    french: "Votre Mot", 
    english: "Your Word", 
    type: "n.m.", 
    category: "cat1", 
    example_fr: "Une phrase d'exemple.", 
    example_en: "An example sentence." 
},
```

## 📱 Mobile Experience

This app uses `<meta name="viewport">` and touch-optimized CSS to function like a native app on iPhone and Android.

Add to Home Screen: For the best experience, open the site in Safari (iOS) or Chrome (Android) and select "Add to Home Screen" to run it fullscreen.

## 🤝 Contributing
Contributions are welcome! If you find a typo in a translation or want to add a C1 level:
Fork the project.
Create your feature branch (`git checkout -b feature/AmazingFeature`).
Commit your changes (`git commit -m 'Add some AmazingFeature'`).
Push to the branch (`git push origin feature/AmazingFeature`).
Open a Pull Request.

## 📄 License
Distributed under the MIT License. See `LICENSE` for more information.

#### Created with ❤️ for French learners.
