
# n8n Inventory Assistant

An automated **Inventory Management System** built using [n8n](https://n8n.io/) and **Google Sheets**.  
This project automates stock tracking, product management, and reporting without manual effort.

---

## Features
- Fetch product data directly from Google Sheets
- Track stock availability in real-time
- Count unique items automatically
- Add, update, and delete inventory items
- AI-assisted queries for inventory management

---

## Tech Stack
- [n8n](https://n8n.io/) – Workflow automation tool  
- Google Sheets – Backend database for inventory  
- OpenAI / AI Agent – For natural language queries  
- Node functions in n8n – Custom logic handling  

---

##   Project Workflow
1. **Trigger** – Workflow starts from chat or API  
2. **Fetch Data** – Queries Google Sheets (`inventory`)  
3. **AI Agent** – Processes queries (count, search, update, delete)  
4. **Response** – Returns results in structured format  


 ##  Example
| Product          | Stock |
|------------------|-------|
| Smartphone       | 25    |
| Headphones       | 40    |
| Keyboard         | 10    |
| Mouse            | 15    |

Query: *"How many Smartphones are in stock?"*  
Response: *Smartphone – 25*  

 ##   Future Enhancements
- Low-stock alerts via Email/Slack/WhatsApp  
- Advanced reporting dashboard  
- Integration with e-commerce APIs  
- Barcode scanning support  



