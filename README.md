```markdown
# Grocery Price Comparison using Groq Vision & Twilio

## Overview
This project automates grocery price comparison using Groq's **Llama-3.2-11b-Vision-Preview** model to extract flyer data and a WhatsApp chatbot powered by **Twilio** for quick price lookup.

## Features
- **Fast OCR Processing**: Extracts structured data from grocery flyers.
- **Price Comparison**: Compares prices across **Freshco, No Frills, and Walmart**.
- **WhatsApp Integration**: Query prices via WhatsApp using **Twilio API**.
- **Blazing Speed**: Thanks to **Groq's LLM**, data extraction happens in milliseconds!

## Setup Instructions

### 1. Clone the Repository
```bash
git clone https://github.com/YOUR_GITHUB_USERNAME/grocery-price-bot.git
cd grocery-price-bot
```

### 2. Install Dependencies
```bash
pip install -r requirements.txt
```

### 3. Set Up API Keys
- Replace `YOUR_API_KEY_HERE` in `Updated_Notebook.ipynb` with your **Groq API Key**.
- Replace `YOUR_TWILIO_SID`, `YOUR_TWILIO_AUTH_TOKEN`, and `YOUR_TWILIO_WHATSAPP_NUMBER` with your **Twilio credentials**.

### 4. Run the Notebook
Execute the Jupyter Notebook to extract grocery prices:
```bash
jupyter notebook Updated_Notebook.ipynb
```

### 5. Connect to WhatsApp
Deploy the Twilio bot and send a message with an item name (e.g., `"Tomatoes"`) to get the best price.

## Credits
- **Groq** for super-fast LLM inference 🚀
- **Twilio** for seamless WhatsApp integration 💬
- Special thanks to my wife for inspiring this project! 😊

---
Check out the project in action and feel free to contribute! 🎉
