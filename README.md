# 🛒 PRICE VERSE — E-Commerce Product Comparison Analyzer

**PRICE VERSE** is an AI-powered JavaFX desktop application that helps users compare products across multiple Indian e-commerce platforms.

It brings product prices, ratings, offers, delivery information and historical price trends together in one place, helping users make faster and more informed purchasing decisions.

---

## ✨ Features

- 🤖 **AI-Powered Product Analysis**  
  Uses the Google Gemini API to assist with collecting and processing product information.

- 🏪 **Multi-Platform Comparison**  
  Compares product information across platforms such as Amazon, Flipkart, Meesho, Shopify, Myntra, Ajio, Snapdeal and Tata CLiQ.

- 📊 **Smart Insights**  
  Helps identify the best price, top-rated platform and fastest delivery option.

- 📈 **Price Tracking**  
  Stores and displays historical price trends using interactive charts.

- 🎨 **Dual Themes**  
  Supports modern dark and light themes.

- 💾 **Database Storage**  
  Uses PostgreSQL for persistent storage of product and price information.

- 📑 **Export Options**  
  Supports exporting product comparisons to PDF and Excel.

- 🔄 **Auto Refresh**  
  Supports automatic updates of product information.

---

## 🎯 Problem Statement

Online shoppers often have to visit multiple e-commerce websites to compare the same product.

Important information such as:

- Product price
- Ratings
- Offers
- Delivery information
- Historical price trends

may be distributed across different platforms.

PRICE VERSE aims to simplify this process by bringing product information together into a single application and providing AI-assisted analysis.

---

## 💡 Solution

PRICE VERSE follows this basic workflow:

```text
User searches for a product
          ↓
AI-assisted product data collection
          ↓
Product information processing
          ↓
Data stored in PostgreSQL
          ↓
Comparison and analysis
          ↓
Best price / rating / delivery insights
          ↓
Historical price analysis
          ↓
User makes an informed decision
