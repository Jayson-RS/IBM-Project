Medical AI Assistant
An AI-powered Health Assistant built with Gradio and IBM Granite Instruct Model, designed to provide:
- Symptom-based disease predictions
- Personalized treatment plan suggestions
- General health tips
- Basic medication information

⚠️ Disclaimer: This project is for educational purposes only. It is not a substitute for professional medical advice. Always consult a certified healthcare provider for diagnosis and treatment.
Features
- Disease Prediction: Enter symptoms and receive possible conditions with recommendations.
- Treatment Plan Generator: Personalized guidance based on condition, age, gender, and medical history.
- Health Tips: Get quick and actionable health tips on various topics.
- Medication Information: Learn about uses, side effects, and precautions for common medicines.
- Secure Login System: Basic login/logout before accessing the assistant.
- User-friendly Interface: Built with Gradio for smooth interaction.
Installation & Setup
This project is designed to run in Google Colab.

1. Clone this repository:
   git clone https://github.com/your-username/health-ai-assistant.git
   cd health-ai-assistant

2. Open the notebook in Google Colab.

3. Install dependencies:
   !pip install -q --upgrade gradio
   !pip install -q transformers torch

4. Run the script. The Gradio app will launch and provide a shareable link.
Tech Stack
- Python
- Gradio – Interactive UI framework
- Transformers (Hugging Face)
- Torch (PyTorch)
- IBM Granite Model – LLM for natural language processing
Project Structure
health-ai-assistant/
│── README.md          # Project documentation
│── health_ai.py       # Main application code
Login Credentials
For demo purposes, default login is:

- Username: user
- Password: password
Use Cases
- College project (Naan Mudhalvan submission)
- Basic health information tool
- Demonstration of AI + Healthcare integration using LLMs
Disclaimer
This project is NOT a medical tool.
It provides general information only and should not replace consultation with qualified healthcare professionals.
