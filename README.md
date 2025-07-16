
## **Setup Instructions**

Install dependencies:

```bash
npm install express cors openai dotenv
```

Create the files:

1. Create `server.js` with the backend code  
2. Create `index.html` with the frontend code  
3. Create `.env` file with your OpenAI API key

Run the server:

```bash
node server.js
```

Access the chatbot:  
Open `index.html` in your browser or serve it through your web server.

---

## **Features**

- **Natural Language Processing**: Uses OpenAI's `gpt-3.5-turbo` model for conversational AI  
- **Responsive Design**: Works on mobile and desktop devices  
- **Error Handling**: Robust error handling on both frontend and backend  
- **Typing Indicator**: Shows when the AI is generating a response  
- **Conversation History**: Maintains context throughout the conversation  

---

## **Customization Options**

- **Styling**: Modify the CSS variables in the `:root` selector to match your brand colors  
- **Model**: Change the model in the backend code (e.g., to `"gpt-4"` if you have access)  
- **Behavior**: Adjust the `temperature` and `max_tokens` parameters for different response styles  
- **Initial Message**: Modify the welcome message in the frontend JavaScript  
