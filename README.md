# Software-testing
# 🧪 Selenium Automation Framework (Python)

## 👋 About
Hi! I am Juhi Mondal, a Software Test Engineer.
This project demonstrates a scalable UI automation framework built using Python and Selenium, following industry best practices such as Page Object Model (POM), reusable utilities, and structured test design.

## 🛠 Tech Stack
- Python
- Selenium WebDriver
- Pytest
- HTML Reports

## 🧱 Framework Design
- Page Object Model (POM)
- Data-driven testing
- Reusable utilities
- Config-based execution

## 📂 Project Structure
The framework follows a modular and scalable structure:

```
automationexercise-pom/
│
├── tests/                  # All test scripts
│   ├── test_homepage.py
│   ├── test_signup.py
│   ├── test_login.py
│   ├── test_logout.py
│   ├── test_contact_us.py
│   ├── test_products.py
│   ├── test_cart.py
│   ├── test_checkout.py
│   ├── test_subscription.py
│   ├── test_category_brand.py
│   ├── test_invoice.py
│   ├── test_scroll.py
│
├── pages/                  # Page Objects
│   ├── base_page.py
│   ├── home_page.py
│   ├── signup_page.py
│   ├── login_page.py
│   ├── account_page.py
│   ├── contact_page.py
│   ├── product_page.py
│   ├── cart_page.py
│   ├── checkout_page.py
│   ├── category_page.py
│   ├── brand_page.py
│
├── utils/                  # Helpers
│   ├── driver_factory.py
│   ├── config_reader.py
│   ├── logger.py
│
├── resources/              # Test data/configs
│   ├── config.ini
│   ├── test_data.json
│
├── reports/                # Test reports
│
├── conftest.py             # Pytest fixtures
├── requirements.txt
└── README.md


```

## 📌 What this project demonstrates
- Scalable test framework design
- Clean code practices using POM
- Real-world automation testing approach

## 🚀 Features
- Cross-browser testing
- Screenshot capture on failure
- HTML test reports
- Command-line execution

## ▶️ How to Run
pip install -r requirements.txt
pytest --html=reports/report.html

## 📸 Reports
(Attach screenshots)

## 👨‍💻 Author
Juhi Mondal
(juhi22mondal@gmail.com)
