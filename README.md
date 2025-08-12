# Marketing Automation System

An AI-powered marketing automation system that generates **personalized product recommendations**, crafts **customized emails**, and creates **Instagram posts** with relevant images and captions — all automated using advanced machine learning models and APIs.

## Features

- **Personalized Product Recommendation:**  
  Utilizes **ChromaDB** for vector-based similarity search on product descriptions to deliver tailored recommendations based on customer purchase history.

- **Email Generation & Delivery:**  
  Generates human-like, engaging marketing emails with **LLaMA 3.3** and sends them securely via Gmail SMTP using **smtplib**.

- **Event-Triggered Email Campaigns:**  
  Dynamically creates an event calendar and maps event categories to product categories to send timely and relevant product recommendations.

- **Instagram Post Automation:**  
  Generates product images using **Hugging Face transformers**, crafts captions with **LLaMA 3.3**, and posts automatically via **instagrapi**.

- **Keyword Extraction & Readability Enhancement:**  
  Uses **Summa** and **Textstat** to improve the relevance and clarity of generated content.

## Technologies Used

- Python  
- LangChain  
- LLaMA 3.3 (Large Language Model)  
- ChromaDB (Vector Database)  
- Hugging Face Transformers  
- instagrapi (Instagram API wrapper)  
- smtplib (Email via SMTP)  
- Summa, Textstat (NLP utilities)

## Installation

1. **Clone the repository:**  
   ```bash
   git clone https://github.com/yourusername/marketing-automation.git
   cd marketing-automation

2. **Create and activate a Python virtual environment (optional but recommended):**
    ```bash
    python3 -m venv venv
    source venv/bin/activate  # Linux/Mac  
    venv\Scripts\activate     # Windows

3. **Install dependencies:**
    ```bash
    pip install -r requirements.txt

## Usage
  - Prepare your datasets (product data, customer data, event calendar JSON).
  - Configure email SMTP credentials and Instagram login credentials securely.
  - Run the main automation script:

    ```bash
    python main.py
    
  - The system will:
    - Generate personalized product recommendations
    - Create and send emails automatically
    - Generate Instagram posts and publish them
