# 🛒 Grocery Lens

**Grocery Lens** is a simple grocery price comparison web application that helps users compare grocery prices across different stores in different cities.

Users can select a city, enter their grocery items, and quickly see which store offers the cheapest total and which store has the lowest price for each individual item.

## ✨ Features

* 🏙️ Compare prices across multiple cities
* 🏪 Compare prices from different grocery stores
* 🛒 Add multiple grocery items at once
* 💰 Find the cheapest store for your grocery list
* 📊 Find the cheapest price for each individual item
* 🔍 Fuzzy matching for item names and typos
* 🤖 Optional AI-based item matching using Groq
* 📍 Display store addresses
* 📱 Simple and responsive interface

## 🏙️ Available Cities

The current demo includes:

* Gujranwala
* Lahore
* Karachi
* Islamabad
* Rawalpindi
* Faisalabad
* Multan

## 🏪 Stores

The application contains sample grocery prices from stores such as:

* Metro Cash & Carry
* Imtiaz Super Market
* Naheed Supermarket
* Al-Fatah

> **Note:** The prices included in this project are sample/demo data stored locally in `data/store_prices.json`. They are not live prices.

## 🛠️ Technologies Used

* **Python**
* **Flask**
* **HTML**
* **CSS**
* **JavaScript**
* **JSON**
* **Groq API** (optional AI matching)

## 📁 Project Structure

```text
grocery-comparator/
│
├── app.py
├── matching.py
├── requirements.txt
├── .env.example
├── .gitignore
│
├── data/
│   └── store_prices.json
│
├── static/
│   ├── script.js
│   └── style.css
│
└── templates/
    └── index.html
```

## 🚀 How to Run

### 1. Clone the repository

```bash
git clone https://github.com/YOUR-USERNAME/grocery-comparator.git
```

```bash
cd grocery-comparator
```

### 2. Create a virtual environment

```bash
python -m venv venv
```

### 3. Activate the virtual environment

**Windows:**

```bash
venv\Scripts\activate
```

### 4. Install dependencies

```bash
pip install -r requirements.txt
```

### 5. Run the application

```bash
python app.py
```

### 6. Open in your browser

Go to:

```text
http://127.0.0.1:5000
```

## 🤖 Optional Groq API

The application can use Groq AI as a fallback when a grocery item cannot be matched locally.

Create a `.env` file:

```text
GROQ_API_KEY=your_api_key_here
```

**Never upload your `.env` file or API key to GitHub.**

## 📝 Adding or Updating Prices

All grocery data is stored in:

```text
data/store_prices.json
```

You can edit this file to:

* Add a new city
* Add a new store
* Update grocery prices
* Update store addresses

## 🎯 Project Goal

The goal of Grocery Lens is to make grocery shopping easier by helping users quickly identify cheaper stores and potentially save money on their grocery shopping.

## 👩‍💻 Project Status

This is a **hackathon/demo project** and currently uses manually entered sample grocery prices rather than live store pricing APIs.

## 📄 License

This project is created for educational and hackathon purposes.
isko readme.md me paste ker dijiye ga github me
