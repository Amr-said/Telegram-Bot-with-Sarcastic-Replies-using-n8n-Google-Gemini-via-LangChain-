# Telegram Bot with Sarcastic Replies using n8n & Google Gemini (via LangChain)
This project implements an n8n workflow that listens to incoming Telegram messages, processes them using **Google Gemini** through a custom **LLM Chain (LangChain)**, and sends back **sarcastic and humorous** replies to the user in real-time.

---

## Components Used:

<img width="764" height="442" alt="image" src="https://github.com/user-attachments/assets/cbafd332-8128-4a29-8778-8aa2d25fe367" />



### A. **Telegram Trigger**
- Listens for new messages from users on a connected Telegram bot.
- Passes the message as input to the workflow.

### B. **Basic LLM Chain (LangChain)**
- Formats the prompt with custom instructions to generate **sarcastic responses**.
- Example instruction:

- <img width="1417" height="442" alt="image" src="https://github.com/user-attachments/assets/becebe93-43ea-47dd-8870-77df23ece1eb" />
