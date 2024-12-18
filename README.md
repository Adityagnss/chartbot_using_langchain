# ChartBot using LangChain and Gemini API

This repository contains a project that implements a powerful and flexible chatbot using LangChain and the Gemini API. The chatbot is designed for two primary functionalities:

1. **General Chatbot Interaction:** Facilitated through LangChain, it provides conversational abilities.
2. **Language Translation:** Utilizes the Gemini API for translating text between various languages.

## Features

- **Conversational AI:** Seamless interaction with users for diverse queries.
- **Language Translation:** Efficient text translation using the Gemini API.
- **Modular Design:** Easy to expand and customize functionalities.

---

## Getting Started

### Prerequisites

Before you begin, ensure you have the following installed:

- **Python 3.8 or higher**
- **pip** (Python package manager)
- An active **Gemini API key**

### Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/Adityagnss/chartbot_using_langchain.git
   cd chartbot_using_langchain
   ```

2. Install the required dependencies:
   ```bash
   pip install -r requirements.txt
   ```

3. Set up your Gemini API key:
   Create a `.env` file in the project directory and add your API key:
   ```env
   GEMINI_API_KEY=your_api_key_here
   ```

---

## Usage

### 1. Run the Chatbot
Execute the chatbot application:
```bash
python chatbot.py
```

### 2. Chatbot Modes

- **Normal Chatbot Mode:** Default mode for interacting with the AI.
- **Language Translator Mode:** Allows text translation using the Gemini API. To enable, use specific commands or access the mode through the chatbot's interface.

### 3. Example Interaction

**General Chatbot:**
```
User: What's the weather like today?
Bot: I’m a chatbot and don’t have real-time data, but I can answer general queries!
```

**Language Translation:**
```
User: Translate "Hello" to French.
Bot: "Bonjour"
```

---

## File Structure

```plaintext
chartbot_using_langchain/
├── chatbot.py            # Main chatbot script
├── translator.py         # Language translation functionalities
├── requirements.txt      # Python dependencies
├── .env.example          # Example environment configuration
└── README.md             # Project documentation
```

---

## Dependencies

- **LangChain**: For building conversational AI functionality.
- **Gemini API**: For language translation.
- **dotenv**: To manage environment variables securely.

Install all dependencies via:
```bash
pip install -r requirements.txt
```

---

## Contributing

Contributions are welcome! If you have suggestions or improvements:

1. Fork the repository.
2. Create a feature branch:
   ```bash
   git checkout -b feature/your-feature-name
   ```
3. Commit your changes:
   ```bash
   git commit -m "Add your feature description"
   ```
4. Push to the branch:
   ```bash
   git push origin feature/your-feature-name
   ```
5. Open a Pull Request.

---

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for more details.

---

## Contact

For inquiries or feedback, reach out at [adityagnss@gmail.com](mailto:adityagnss@gmail.com).
