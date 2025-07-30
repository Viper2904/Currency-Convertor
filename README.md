# 💱 Currency Converter Webhook using Flask & Dialogflow

This project is a Flask-based webhook integration for a Dialogflow chatbot that performs real-time currency conversions. When a user asks Dialogflow to convert an amount from one currency to another, the webhook handles the logic, retrieves the latest exchange rate via an external API, and sends the converted amount back.

---

## 🚀 Features

- 🔁 Converts between any two world currencies.
- 🌐 Real-time exchange rates using [CurrencyConverterAPI](https://free.currencyconverterapi.com/).
- 🤖 Easy integration with Dialogflow chatbot via webhook.
- 🪝 JSON response formatted for Dialogflow’s `fulfillmentText`.

---

## 🧑‍💻 Technologies Used

- **Python 3.x**
- **Flask** (lightweight web framework)
- **requests** (for API calls)
- **Dialogflow** (for NLP and intent handling)

---

## 📦 Installation

1. Clone the repository:

```bash
git clone https://github.com/yourusername/currency-converter-webhook.git
cd currency-converter-webhook
