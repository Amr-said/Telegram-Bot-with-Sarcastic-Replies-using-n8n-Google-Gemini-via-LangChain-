# Telegram Bot with Sarcastic Replies using n8n & Google Gemini (via LangChain)
This project implements an n8n workflow that listens to incoming Telegram messages, processes them using **Google Gemini** through a custom **LLM Chain (LangChain)**, and sends back **sarcastic and humorous** replies to the user in real-time.

---

## Components Used:

<img width="941" height="533" alt="image" src="https://github.com/user-attachments/assets/6c4a68b9-25df-4f35-8d4c-40de3acb8f54" />



### A. **Telegram Trigger**
- Listens for new messages from users on a connected Telegram bot.
- Passes the message as input to the workflow.

### B. **Basic LLM Chain (LangChain)**
- Formats the prompt with custom instructions to generate **sarcastic responses**.
- Example instruction:

- <img width="1417" height="442" alt="image" src="https://github.com/user-attachments/assets/becebe93-43ea-47dd-8870-77df23ece1eb" />
