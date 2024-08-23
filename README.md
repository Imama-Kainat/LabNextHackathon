

# ChatCinema: A Conversational Movie Recommendation System

**ChatCinema** is an interactive movie recommendation system that uses natural language processing (NLP) and machine learning to provide personalized movie suggestions based on user input. Built using Streamlit, ChatCinema leverages Groq, a vector database, to store and retrieve movie embeddings, offering a seamless and engaging user experience.

You can try the live demo here: [ChatCinema](https://chat-cinema.streamlit.app/)
Demo video and presentation:  https://shorturl.at/YzQ74
## Features

- **Conversational Interface:** Users can input movie names or descriptions and receive personalized movie recommendations.
- **Personalized Recommendations:** Suggestions are tailored to the user’s input, ensuring relevant and accurate movie options.
- **Download Chat History:** Users can download their chat history in an encrypted CSV file, ensuring privacy and security.
- **Decryption Tool:** The app includes a tool for decrypting the downloaded chat history and any encrypted datasets.
- **AI-Powered Dataset Generation:** Users can generate new datasets using AI models, with the option to download them in an encrypted ZIP file.

## Getting Started

To run the application locally, follow these steps:

1. **Clone the repository:**
   ```bash
   git clone https://github.com/OSAMAGHAFFARTKOJL/LabNextHackathon
   cd chatcinema
   ```

2. **Install the required dependencies:**
   ```bash
   pip install -r requirements.txt
   ```

3. **Run the application:**
   ```bash
   streamlit run app.py
   ```
   This command will launch the application in your default web browser.

## Application Tabs

ChatCinema consists of four main tabs:

1. **Chatbot:** Interact with the conversational movie recommendation system.
2. **Download Chat History:** Download your chat history in an encrypted CSV file.
3. **Decryption:** Decrypt an encrypted CSV file or text using a provided key.
4. **Generate Dataset:** Generate a new dataset using AI models and download it in an encrypted ZIP file.

## Technical Requirements

- **Python 3.8** or later
- **Streamlit 1.10** or later
- **Groq 1.3** or later
- **SentenceTransformers 2.2** or later
- **scikit-learn 1.0** or later
- **NumPy 1.20** or later
- **Cryptography 3.4** or later
- **Torch 1.10** or later
- **Transformers 4.12** or later

## Installation

To install the necessary dependencies, use the following command:

```bash
pip install -r requirements.txt
```

## Usage

1. **Chatbot Interaction:**
   - Enter movie names or descriptions in the Chatbot tab to get personalized recommendations.
2. **Download and Encrypt Chat History:**
   - Save your chat history securely by downloading it as an encrypted CSV file.
3. **Decrypt Encrypted Data:**
   - Use the Decryption tab to decrypt your downloaded files or any encrypted text.
4. **Generate Encrypted Dataset:**
   - Create new datasets using AI models and download them securely in an encrypted ZIP file.

## License

This project is licensed under the MIT License. For more details, see the [LICENSE](LICENSE) file.

## Acknowledgments

This project was built using the following open-source libraries and frameworks:

- [Streamlit](https://streamlit.io/)
- [Groq](https://groq.com/)
- [SentenceTransformers](https://www.sbert.net/)
- [scikit-learn](https://scikit-learn.org/)
- [NumPy](https://numpy.org/)
- [Cryptography](https://cryptography.io/)
- [Torch](https://pytorch.org/)
- [Transformers](https://huggingface.co/transformers/)

A big thank you to the maintainers and contributors of these projects for their hard work and dedication.
Team Members
M. Osama Ghaffar
Imama Kainat
Abdullah Sajid
Ahmad Ali
Ayesha Siddique
Fareeha Amir
