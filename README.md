Steps to Run the Application
Install Ollama
Download and install Ollama from the official website: https://ollama.com.
After installation, make sure Ollama is running in the background.
Pull the Required Models
Open Command Prompt or Terminal and run the following commands to download the required models:
ollama run hf.co/CompendiumLabs/bge-base-en-v1.5-gguf
ollama run hf.co/bartowski/Llama-3.2-1B-Instruct-GGUF
These models are used for embedding generation and language model inference.
Install Required Python Modules
Ensure Python version 3.9 or higher is installed.
Navigate to the project directory and install dependencies using:
pip install -r requirements.txt
Run the Application
Start the Streamlit application by running:
streamlit run ollama-app.py
Once the server starts, open the local URL shown in the terminal (usually http://localhost:8501) in your web browser.
Verify Execution
Confirm that Ollama is running and the application loads successfully in the browser.
