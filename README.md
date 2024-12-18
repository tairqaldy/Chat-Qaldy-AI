# Chat Qaldy AI

![License](https://img.shields.io/badge/License-MIT-blue.svg)
![Version](https://img.shields.io/badge/Version-1.0.1-brightgreen.svg)

Chat Qaldy AI is a JavaScript-based clone of ChatGPT, powered by OpenAI's GPT models. This project offers an interactive chatbot interface that allows users to engage in conversations, customize settings, and save their chat history. Designed with simplicity and responsiveness in mind, Chat Qaldy AI is perfect for both desktop and mobile users.

---

## 🚀 Features

- **Interactive Chat Interface**: Engage in real-time conversations with the GPT model.
- **Customizable Settings**: Adjust API Key, model type, maximum tokens, and more.
- **Save & Load Conversations**: Export and import chat sessions effortlessly.
- **Responsive Design**: Optimized for both desktop and mobile devices.
- **User Personalization**: Set and display your username for a personalized experience.
- **Versioning**: Keep track of different versions with clear updates.

---

## 🛠️ Installation & Setup

### 1. Clone the Repository

Start by cloning the repository to your local machine:

```bash
git clone https://github.com/tairqaldy/Chat-Qaldy-AI.git
```
2. Navigate to the Project Directory
```bash
Copy code
cd Chat-Qaldy-AI
```
3. Initialize Git (If Not Already Initialized)
```bash
If you haven't initialized Git in your project directory, do so with:
```
```bash
git init
```
```bash
4. Add and Commit Files
Add all files to the staging area and commit them:
```
```bash
git add .
git commit -m "First Commit version 1.0.1"
```
5. Add Remote Repository
Link your local repository to GitHub:
```bash
git remote add origin https://github.com/tairqaldy/Chat-Qaldy-AI.git
```
6. Set Branch to Main
```bash
git branch -M main
```
7. Push to GitHub
```bash
git push -u origin main
```
🔑 Setting Up Your OpenAI API Key
To use Chat Qaldy AI, you need an OpenAI API Key:

Sign Up / Log In: Visit OpenAI's platform and sign up or log in.
Generate API Key: Navigate to the API section in your dashboard and generate a new API key.
Configure API Key:
Open the index.html file in your project.
Locate the initialization script and replace 'API_KEY' with your actual API key:
html:
```bash
<script>
    new ChatAI({
        container: '.chat-ai',
        api_key: 'YOUR_API_KEY_HERE',
        model: 'gpt-3.5-turbo',
        max_tokens: 1000
    });
</script>
```
🧪 Running the Project Locally
Open the Project:

Navigate to the project directory.
Open the index.html file in your preferred web browser (e.g., Chrome, Firefox, Edge).
Start a Local Server (Optional but Recommended):

Using Python:

```bash
python -m http.server 8000
Then, open http://localhost:8000 in your browser.
```

Using VS Code Live Server:
```bash
Install the Live Server extension.
Right-click on index.html and select "Open with Live Server".
```
Interact with the Chatbot:

Type your messages in the input box and press Enter or click the send button.
Customize settings by clicking the gear icon in the sidebar.

📜 Version History
Version 1.0.1
Initial release.
Implemented chat interface, conversation saving, and customizable settings.

🌐 Resources & Credits
Tutorial Inspiration: This project was inspired by the CodeShack tutorial.
Icons: Font Awesome is used for icons throughout the project.

🧑‍💻 About the Author
This project was made with ❤️ by Tair Kaldybayev.
Feel free to explore my GitHub profile for more exciting projects.

🌟 Contributing
Contributions are welcome! If you'd like to suggest improvements or report bugs, feel free to open an issue or create a pull request.

🛡️ License
This project is licensed under the MIT License.
You are free to use, modify, and distribute this project, provided you include the original license.
