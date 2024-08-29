# DEV WIZARD: Your VS Code Copilot
![image](https://github.com/user-attachments/assets/256a92d0-0c0d-4f93-a179-2566dfe4e736)


# Overview
DEV WIZARD is a VS Code extension that acts as an intelligent copilot for developers, offering code completions, suggestions, and contextual insights. It leverages multiple language models to understand the user's queries and provides relevant responses. The copilot can analyze code surrounding the cursor (previous and next 5 lines) and can be tailored using different models like llama3-8b-8192, gemma2-9b-it, and mixtral-8x7b-32768.

# Key Features
1. Multi-Model Support: Choose from multiple AI models for different tasks (llama3-8b-8192, gemma2-9b-it, and mixtral-8x7b-32768).
Context-Aware Responses: Analyzes the surrounding lines of code (5 lines before and after the cursor) to provide relevant suggestions.
2. Enhanced UI: Visually appealing and user-friendly interface, with markdown support for better text and code rendering.
3. Quick Actions: Easily regenerate or delete responses directly from the UI.
4. Copy to Clipboard: Copy code blocks with a single click for efficient workflow integration.

# Usage
Open the Sidebar: Activate the copilot by clicking on the "JARVIS" icon located in the sidebar or pressing Shift + C.
Select a Model: Use the dropdown menu to select the desired model (llama3-8b-8192, gemma2-9b-it, or mixtral-8x7b-32768).
Ask a Question: Type your query in the input box and either press "Enter" or click on the "Submit" button.
View Responses: The response will be displayed below the input box, separated into normal text and code sections.

# Quick Actions:
![image](https://github.com/user-attachments/assets/bd9cc952-9a7a-4323-9855-00e5b2ad5a27)

1. Regenerate: Click on the "Regenerate" button to generate a new response for the same query.
2. Delete: Remove any response by clicking the "Delete" button.
3. Copy: Use the "Copy" button next to code sections to copy the code to your clipboard.

# Testing the Context Analysis Feature
To test the context-aware analysis:

Open a code file in VS Code.
Place your cursor on a specific line in the editor.
Activate the copilot and type a query related to the code around the cursor.
The copilot will analyze the 5 lines of code before and after the cursor and provide a contextual response.

# Troubleshooting
Common Issues
API Key Not Set: If you see an error message saying "GROQ_API_KEY is not set," ensure you have replaced the placeholder API key with your actual key in the extension.ts file.
No Response:
Check the console (Help > Toggle Developer Tools > Console) for any errors.
Ensure your API key is correct and that you have an active internet connection.
UI Not Appearing Correctly:
Ensure the extension is properly installed.
Check for any conflicts with other VS Code extensions.

#Contributing
Feel free to contribute by submitting issues, suggesting features, or making pull requests to the GitHub Repository (replace with your actual link).



