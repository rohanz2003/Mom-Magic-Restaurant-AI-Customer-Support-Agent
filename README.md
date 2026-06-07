# Mom Magic Restaurant AI Assistant 🍽️

An AI-powered customer support assistant built with n8n that helps customers view menus, place orders, and get restaurant information in real time.

## Features

* 📋 View the latest restaurant menu
* 🛒 Place food orders
* 📦 Real-time inventory checking
* 🔄 Automatic inventory updates after orders
* ❓ Restaurant FAQ support
* 📜 Policy and terms information
* 🤖 AI-powered customer service
* ⚡ Fast and automated responses

## Workflow

Customer → AI Assistant → Inventory Check → Order Processing → Inventory Update → Customer Confirmation

## Tools Used

* n8n
* OpenAI
* Google Sheets (Inventory & Orders)
* AI Agent
* Chat Trigger

## How It Works

### Menu Requests

The assistant fetches live inventory data and displays available menu items with prices.

### Order Placement

Customers provide:

* Name
* Item
* Quantity

The assistant validates inventory, places the order, and updates stock automatically.

### Out of Stock Handling

If an item is unavailable, the assistant notifies the customer and suggests an alternative item.

### FAQ & Policies

The assistant answers questions using the restaurant's policy and FAQ database.

## Live Demo

Chat with the assistant:

🔗 https://rohan1020.app.n8n.cloud/webhook/44dc5c6b-c055-41de-8098-75f5447945ea/chat

## Project Structure

* Inventory Management
* Order Processing
* Inventory Updates
* FAQ & Policy Support
* AI Customer Service

## Benefits

* 24/7 customer support
* Automated order management
* Reduced manual work
* Real-time inventory tracking
* Improved customer experience

## Author

Developed using n8n workflow automation and AI-powered customer support technology.
