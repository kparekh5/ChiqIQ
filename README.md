Chiq Iq ✨ - Your Personal AI Fashion Assistant
Chiq Iq is a conversational AI chatbot designed to be your go-to personal stylist. Simply describe an occasion, your style preferences, or the weather, and Chiq Iq will provide tailored outfit recommendations through a natural and intuitive chat interface.

Core Features
  - Conversational Outfit Suggestions: Get personalized fashion advice through a natural chat interface.
  - AI-Powered Responses: Utilizes Vext AI to understand context and provide relevant, creative suggestions.
  - Session Management: Remembers your conversation history for a seamless and personalized experience.
  - Simple & Clean UI: Built with Streamlit for a fast, responsive, and easy-to-use interface.

Tech Stack
  - Frontend: Streamlit
  - Chat Logic: Vext AI
  - Language: Python

Setup & Deployment
This application is designed to be easily deployed for free on the Streamlit Community Cloud.

Prerequisites
  - Python 3.8+
  - A Vext AI account and API credentials (URL and Key).
  - A GitHub account.

Local Setup and Testing
Before deploying, it's best to run the app on your local machine to ensure everything is configured correctly.

    1. Clone the Repository:
        git clone <your-repository-url>
        cd chiq-iq-app
    
    2. Install Dependencies:
        pip install -r requirements.txt
    
    3. Configure API Secrets:
      - Create a new folder in your project directory named .streamlit.
      - Inside the .streamlit folder, create a new file named secrets.toml.
      - Add your Vext AI credentials to this file:
          # Vext AI API Credentials
          vext_api_url = "PASTE_YOUR_VEXT_AI_URL_HERE"
          vext_api_key = "PASTE_YOUR_VEXT_AI_KEY_HERE"
    
    4. Run the App Locally:
        streamlit run app.py

Your application should open in a new browser tab. 
<img width="983" height="783" alt="Screenshot 2025-09-16 at 10 32 04 PM" src="https://github.com/user-attachments/assets/2e5a48c4-299b-4bb8-bef5-af0c36901b11" />




