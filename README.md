### Chat Qaldy AI

![License](https://img.shields.io/badge/License-MIT-blue.svg)
![Version](https://img.shields.io/badge/Version-1.0.1-brightgreen.svg)
![GitHub Repo stars](https://img.shields.io/github/stars/tairqaldy/Chat-Qaldy-AI?style=social)

Chat Qaldy AI is a JavaScript-based clone of ChatGPT, powered by OpenAI's GPT models. This project offers an interactive chatbot interface that allows users to engage in conversations, customize settings, and save their chat history. Designed with simplicity and responsiveness in mind, Chat Qaldy AI is perfect for both desktop and mobile users.

---

## 🚀 Features

- **Interactive Chat Interface**: Engage in real-time conversations with the GPT model.
- **Customizable Settings**: Adjust API Key, model type, maximum tokens, and more.
- **Save & Load Conversations**: Export and import chat sessions effortlessly.
- **Responsive Design**: Optimized for both desktop and mobile devices.
- **User Personalization**: Set and display your username for a personalized experience.
- **Versioning**: Keep track of different versions with clear updates.
- **Error Handling**: Gracefully manage API errors and display informative messages.
- **Local Storage**: Persist user settings and conversations across sessions.

---

## 🛠️ Installation & Setup

### 1. Clone the Repository

Start by cloning the repository to your local machine:

```bash
git clone https://github.com/tairqaldy/Chat-Qaldy-AI.git
```

### 2. Navigate to the Project Directory

```bash
cd Chat-Qaldy-AI
```

### 3. Initialize Git (If Not Already Initialized)

If you haven't initialized Git in your project directory, do so with:

```bash
git init
```

### 4. Add and Commit Files

Add all files to the staging area and commit them:

```bash
git add .
git commit -m "First Commit version 1.0.1"
```

### 5. Add Remote Repository

Link your local repository to GitHub:

```bash
git remote add origin https://github.com/tairqaldy/Chat-Qaldy-AI.git
```

### 6. Set Branch to Main

```bash
git branch -M main
```

### 7. Push to GitHub

```bash
git push -u origin main
```

---

## 🔑 Setting Up Your OpenAI API Key

To use Chat Qaldy AI, you need an OpenAI API Key:

1. **Sign Up / Log In**: Visit [OpenAI's platform](https://platform.openai.com/) and sign up or log in.
2. **Generate API Key**: Navigate to the API section in your dashboard and generate a new API key.
3. **Configure API Key**:
   - Open the `index.html` file in your project.
   - Locate the initialization script and replace `'API_KEY'` with your actual API key:
   
   ```html
   <script>
       new ChatAI({
           container: '.chat-ai',
           api_key: 'YOUR_API_KEY_HERE',
           model: 'gpt-3.5-turbo',
           max_tokens: 1000
       });
   </script>
   ```

---

## 🧪 Running the Project Locally

### 1. Open the Project

- Navigate to the project directory.
- Open the `index.html` file in your preferred web browser (e.g., Chrome, Firefox, Edge).

### 2. Start a Local Server (Optional but Recommended)

Serving the project via a local server can enhance development and prevent potential CORS issues.

#### Using Python:

```bash
python -m http.server 8000
```

Then, open [http://localhost:8000](http://localhost:8000) in your browser.

#### Using VS Code Live Server:

1. Install the [Live Server extension](https://marketplace.visualstudio.com/items?itemName=ritwickdey.LiveServer).
2. Right-click on `index.html` and select **"Open with Live Server"**.

### 3. Interact with the Chatbot

- **Send Messages**: Type your messages in the input box and press **Enter** or click the send button.
- **Customize Settings**: Click the gear icon in the sidebar to adjust settings like API Key, model type, and maximum tokens.
- **Save & Load Conversations**: Use the save and open database features to manage your chat history.

---

## 📝 Version History

### Version 1.0.1

- **Initial Release**:
  - Implemented chat interface.
  - Added conversation saving functionality.
  - Introduced customizable settings.
  - Enhanced user personalization with username display.
  - Integrated error handling for API responses.

---

## 🌐 Resources & Credits

- **Tutorial Inspiration**: This project was inspired by the [CodeShack tutorial](https://codeshack.io/build-ai-powered-chatbot-openai-chatgpt-javascript/).
- **Icons**: Font Awesome is used for icons throughout the project.
- **OpenAI API**: Utilizes OpenAI's GPT models for natural language processing.

---

## 🧑‍💻 About the Author

This project was made with ❤️ by **[Tair Kaldybayev](https://github.com/tairqaldy)**.  
Feel free to explore my [GitHub profile](https://github.com/tairqaldy) for more exciting projects.

---

## 🌟 Future Plans

- **User Authentication**: Implement user accounts to manage personalized settings and chat histories.
- **Advanced Settings**: Provide more customization options for chat behavior and appearance.
- **Multi-language Support**: Enable the chatbot to understand and respond in multiple languages.
- **Enhanced UI/UX**: Improve the user interface with better animations and accessibility features.
- **Deployment**: Host the application on platforms like GitHub Pages, Vercel, or Netlify for easy access.

---

## 🛡️ License

This project is licensed under the **MIT License**.  
You are free to use, modify, and distribute this project, provided you include the original license.

---

## 👩‍💻 Developer Guide

### Contributing

Contributions are welcome! Whether it's fixing bugs, improving documentation, or adding new features, your help is appreciated.

1. **Fork the Repository**: Click the "Fork" button on the repository page.
2. **Create a Branch**:  
   ```bash
   git checkout -b feature/YourFeatureName
   ```
3. **Make Your Changes**: Implement your feature or bug fix.
4. **Commit Your Changes**:  
   ```bash
   git commit -m "Add some feature"
   ```
5. **Push to the Branch**:  
   ```bash
   git push origin feature/YourFeatureName
   ```
6. **Open a Pull Request**: Describe your changes and submit the pull request for review.

### Development Environment

- **Prerequisites**:
  - Modern web browser (e.g., Chrome, Firefox, Edge)
  - Code editor (e.g., VS Code)
  - Git installed on your machine

- **Project Structure**:
  ```
  Chat-Qaldy-AI/
  ├── index.html
  ├── ChatAI.js
  ├── style.css
  └── README.md
  ```

- **Code Standards**:
  - Follow consistent indentation and formatting.
  - Write clear and concise comments where necessary.
  - Ensure accessibility and responsiveness in design.

### Testing

- **Manual Testing**: Interact with the chatbot to ensure all features work as expected.
- **API Testing**: Verify that API requests and responses are handled correctly, including error scenarios.
- **UI/UX Testing**: Ensure the interface is intuitive and responsive across different devices and screen sizes.

---

Happy coding! 🎉
