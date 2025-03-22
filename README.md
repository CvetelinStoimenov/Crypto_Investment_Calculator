# Crypto Investment Calculator

## 🏆 Описание
Това уеб приложение изчислява стойността на инвестицията в Биткойн, ако потребителят е инвестирал определена сума от избрана начална дата. Проектът използва **Flask**, **Selenium**, и **requests** за динамично извличане на исторически и текущи цени на Биткойн.

## 📌 Функционалности
- 📅 **Избор на начална и крайна дата на инвестицията**
- 💰 **Въвеждане на еднократна или периодична инвестиция**
- 🔎 **Извличане на исторически цени на Биткойн**
- 📊 **Изчисляване на текущата стойност и процента на печалба/загуба**
- 🎨 **Динамичен и интерактивен потребителски интерфейс с CSS и JavaScript**
- 🔄 **Обновяване на резултатите без презареждане на страницата**

## 🚀 Инсталация и стартиране
1. **Клониране на хранилището:**
   ```sh
   git clone https://github.com/your-username/crypto-investment-calculator.git
   cd crypto-investment-calculator
2.  **Създаване на виртуална среда и инсталиране на зависимостите:**
    
    ```sh
    python -m venv venv 
    source venv/bin/activate    # За Linux/Mac 
    venv\Scripts\activate       # За Windows 
    pip install -r requirements.txt  
3.  **Стартиране на Flask сървъра:**
    
    ```sh
    python app.py     
4.  **Отваряне на приложението в браузъра:**
    
    ```cpp
    http://127.0.0.1:5000
## 🛠 Технологии

-   **Backend:** Flask, Python, requests, lxml
    
-   **Frontend:** HTML, CSS, JavaScript (динамично зареждане)
    
-   **API:** CoinMarketCap (за исторически данни), CoinGecko (за текуща цена)
    
-   **Автоматизация:** Selenium (при необходимост)
    

## 📌 Бъдещи подобрения

-   ✅ Добавяне на графика за ценовите промени
    
-   ✅ Поддръжка на допълнителни криптовалути
    
-   ✅ Интеграция с потребителски акаунти за запазване на инвестиции
    

## 📄 Лиценз

Този проект е с **MIT лиценз** – можеш да го използваш и модифицираш свободно. 🚀