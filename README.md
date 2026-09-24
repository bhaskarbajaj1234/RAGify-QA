# RAGify-QA

Developed by **Bhaskar Vikas Bajaj**

---

## About The Project

**RAGify-QA** is an AI-powered Document Question Answering System designed to streamline information retrieval from vast document collections. Built on advanced natural language processing (NLP) techniques, the application provides a user-friendly interface powered by Streamlit.

Leveraging the **LangChain** framework, **Google Generative AI**, and **Groq**, the system ingests documents, converts them into vector embeddings, and employs a Retrieval-Augmented Generation (RAG) architecture for highly accurate contextual question answering.

### Key Features
- **Context-Aware QA**: Answers user queries based strictly on the provided document context.
- **Fast Vector Search**: Utilizes FAISS for fast and scalable similarity search.
- **LLM Integration**: Powered by Google Gemini and Groq models for fast, high-quality responses.
- **Interactive UI**: Clean, responsive interface built with Streamlit.

---

## Library Requirements

- faiss-cpu
- langchain-groq
- PyPDF2
- langchain_google_genai
- langchain
- streamlit
- python-dotenv

---

## Getting Started

Follow these steps to set up and run the project locally on your machine.

### Prerequisites

Ensure you have Python installed on your system (Python 3.9 or higher recommended).

### Installation Steps

1. **Clone the Repository**
   git clone https://github.com/bhaskarbajaj1234/RAGify-QA.git
   cd RAGify-QA

2. **Create a Virtual Environment** (Recommended)
   - Using venv:
     python -m venv venv
     source venv/bin/activate  # On macOS/Linux
     venv\Scripts\activate     # On Windows
   - Or using conda:
     conda create -n ragify-qa python=3.10 -y
     conda activate ragify-qa

3. **Install Dependencies**
   pip install -r requirements.txt

4. **Set Up Environment Variables**
   Create a .env file in the root directory of the project and add your API keys:
   GROQ_API_KEY=your_groq_api_key_here
   GOOGLE_API_KEY=your_google_api_key_here

5. **Run the Application**
   streamlit run app.py

6. **Access the Web App**
   Open your browser and navigate to http://localhost:8501

---

## Contributing

Contributions are what make the open-source community such an amazing place to learn, inspire, and create. Any contributions you make are greatly appreciated.

1. Fork the Project
2. Create your Feature Branch (git checkout -b feature/AmazingFeature)
3. Commit your Changes (git commit -m 'Add some AmazingFeature')
4. Push to the Branch (git push origin feature/AmazingFeature)
5. Open a Pull Request

---

## License

This project is open-source and available under the GNU General Public License v3.0.

---

## Author

**Bhaskar Vikas Bajaj**
- GitHub: https://github.com/bhaskarbajaj1234
