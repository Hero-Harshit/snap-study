# 📚 Snap Study

Snap Study is an AI-powered tutoring application designed to help students learn effectively. 
You simply take a photo of a problem, diagram, or page of notes, and Snap Study breaks down the key concepts using plain language. At the end of the session, it can email you a personalized summary of the concepts discussed for your records.

## Features
- **Visual Learning:** Upload images of problems or notes to get clear, clear explanations.
- **Interactive Chat:** Ask follow-up questions to understand the concepts deeply.
- **Email Summaries:** Get a customized summary of your learning session sent directly to your email inbox.

## How to run it locally

1. **Clone the repository:**
   ```bash
   git clone <your-repo-url>
   cd <your-repo-folder>
   ```

2. **Set up a virtual environment (optional but recommended):**
   ```bash
   python -m venv venv
   source venv/bin/activate  # On Windows use: venv\Scripts\activate
   ```

3. **Install the dependencies:**
   ```bash
   pip install -r requirements.txt
   ```

4. **Set up your secrets:**
   - Copy the `.streamlit/secrets.toml.example` file to `.streamlit/secrets.toml`.
   - Open `.streamlit/secrets.toml` and fill in your Gemini API key, your Gmail address, and your 16-character Gmail App Password.
   - *Never commit your real `secrets.toml` to version control.*

5. **Run the application:**
   ```bash
   streamlit run app.py
   ```

Your browser should automatically open the app at `http://localhost:8501`.
