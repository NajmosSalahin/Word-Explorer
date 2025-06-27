# Vocabulary Checker App

A comprehensive web-based Vocabulary Checker application built with HTML, Tailwind CSS, and JavaScript. It provides detailed word information (definitions, synonyms, antonyms, pronunciation) and AI-powered content (stories, usage tips, quizzes, etymology, translations, word families, idioms, collocations). Users can also save and manage vocabulary lists for future reference.

## ✨ Features

* **Word Search:** Get instant definitions, synonyms, antonyms, and pronunciation for English words.

* **Pronunciation Playback:** Hear US and UK pronunciations using the Web Speech API.

* **AI-Powered Content Generation:**

    * **Contextual Stories:** Generate short paragraphs featuring the searched word.

    * **Usage Tips & Common Mistakes:** Learn nuances and avoid pitfalls.

    * **Interactive Quizzes:** Test your understanding with multiple-choice questions.

    * **Etymology / Word Origin:** Explore the history of words.

    * **Related Concepts/Topics:** Discover broader ideas connected to the word.

    * **Synonym/Antonym Nuances:** Understand subtle differences in similar words.

    * **Cross-Language Translations:** Translate words into multiple languages (Bengali, Korean, Japanese, Filipino, Indonesian, Chinese, French, Italian, Arabic, German, Russian).

    * **Styled Usage Examples:** See how words are used in formal, informal, poetic, or journalistic styles.

    * **Word Family / Related Terms:** View different forms and associated terms.

    * **Suffix/Prefix Information:** Understand how affixes modify word meanings.

    * **Idioms & Phrases:** Explore common expressions using the word.

    * **Cultural Context:** Learn about regional or social usage nuances.

    * **Common Collocations:** Discover words that frequently appear together.

* **Save & Load Vocabulary:** Persist your favorite words and their generated content in your browser's local storage.

* **Clear Saved Words:** Option to delete all saved vocabulary.

* **Responsive Design:** Optimized for various screen sizes, from mobile to desktop.

## 🚀 Technologies Used

* **HTML5:** Structure of the web application.

* **Tailwind CSS:** For rapid and responsive UI styling.

* **JavaScript (ES6+):** Core logic, DOM manipulation, and API interactions.

* **Web Speech API:** For text-to-speech pronunciation.

* **Google Gemini API:** For all AI-generated content (stories, quizzes, translations, etc.).

## 🧠 AI Integration

This application leverages the power of the Google Gemini API to provide rich, dynamically generated content. When you click on the "Generate" buttons for sections like "Word in Context Story," "Quiz Question," or "Cross-Language Translation," the application makes a call to the Gemini API with a specific prompt based on the currently displayed word. The AI then processes this request and returns relevant text or structured data (like quiz questions or translation details), enhancing your learning experience beyond static dictionary entries.

## 🔑 How to Get a Gemini API Key

To run this application with full AI functionality, you'll need a Google Gemini API key. Follow these steps:

1.  **Go to Google AI Studio:** Visit <https://aistudio.google.com/>.

2.  **Sign In:** Sign in with your Google account.

3.  **Create API Key:**

    * In the left sidebar, click "Get API Key" or "Create API Key."

    * You might need to create a new project first if you haven't done so.

    * Copy the generated API key.

4.  **Integrate the Key:** In the `index.html` file, find the line:

    ```javascript
    const apiKey = "YOUR_GEMINI_API_KEY_HERE";
    ```

    Replace `"YOUR_GEMINI_API_KEY_HERE"` with the actual API key you obtained from Google AI Studio. **Note:** In a Canvas environment, the `apiKey` variable (`""`) is often automatically provided or handled by the environment, so direct modification might not be necessary if running within such a platform. However, for local development outside Canvas, you would replace it.

## 💻 Usage

1.  **Clone the repository:**

    ```bash
    git clone [https://github.com/your-username/vocabulary-checker-app.git](https://github.com/your-username/vocabulary-checker-app.git)
    ```

    (Replace `your-username` with your actual GitHub username if you fork it)

2.  **Navigate to the project directory:**

    ```bash
    cd vocabulary-checker-app
    ```

3.  **Open `index.html`:** Simply open the `index.html` file in your web browser. No local server is required.

4.  **Enter a word** in the input field and click "Search Word".

5.  **Explore** the detailed information and click "Generate" buttons for AI-powered content.

6.  Use "Save Current Word" to store words and "Load Saved Words" to retrieve them.

## 🤝 Contributing

Contributions are welcome! If you have suggestions for improvements, new features, or bug fixes, feel free to open an issue or submit a pull request.

## 📄 License

This project is open-sourced under the [MIT License](LICENSE).
