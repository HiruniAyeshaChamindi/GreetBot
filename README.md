# GreetBot
**GreetBot** is a simple rule-based and TF-IDF-powered chatbot that responds to greetings and basic chatbot-related queries.

# 📌 Project Scop
This chatbot is a basic rule-based and retrieval-based conversational agent designed to:

Respond to greetings using a set of predefined inputs and outputs.

Handle user queries related to chatbots by matching them with relevant responses from a small knowledge base using TF-IDF vectorization and cosine similarity.

The chatbot works entirely offline using Python libraries such as:

nltk for text processing,

sklearn for vectorization and similarity comparison.

It provides a simple terminal-based interaction loop and is best suited for introductory chatbot demonstrations or educational purposes.

## 🧠 Key Concepts

| Technique              | Purpose                                                                 |
|------------------------|-------------------------------------------------------------------------|
| `TF-IDF Vectorization` | Converts words into numbers based on frequency and importance           |
| `Cosine Similarity`    | Measures similarity between user input and corpus responses             |
| `NLTK` Preprocessing   | Tokenization, lemmatization for cleaning and normalizing text input     |

## 🚀 How to Run

1. Clone this repository or download the files.
2. Open `chat-bot.ipynb` in Jupyter Notebook.
3. Run all cells in order.
4. Interact with the chatbot in the final cell.
