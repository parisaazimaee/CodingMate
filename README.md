# CodingMate
A chatbot assistant for coding help and debugging

Project Title: CodingMate – Your AI-powered Documentation Assistant
Overview:
CodingMate is a chatbot designed to assist developers by providing relevant documentation for Python libraries like Pandas, NumPy, and more. It integrates official docs with community solutions from Stack Overflow, powered by LangChain, OpenAI, and ChromaDB.
Features:
    • Natural Language Querying: Ask questions in plain language.
    • Official Documentation Retrieval: Access up-to-date documentation from popular Python libraries.
    • Stack Overflow Integration: Receive community-contributed solutions for specific problems.
    • Vector Database Storage: Efficient storage and retrieval of docs with ChromaDB.
Technologies Used:
    • Python, LangChain, ChromaDB, BeautifulSoup, Requests, Streamlit, OpenAI API.
Installation Instructions:
    1. Clone the repository.
    2. Set up Python virtual environment and install dependencies: 
        python3 -m venv codingmate  
        source codingmate/bin/activate  
        pip install -r requirements.txt
    3. Set up OpenAI API key for LLM functionality.
    4. Run the Streamlit app: 
        streamlit run app.py

Project structure

CodingMate/
│── app.py               # Streamlit app
│── scraper.py           # Web scraper for documentation
│── config.py            # Store API keys and settings
│── requirements.txt      # Dependency file
│── README.md            # Project overview
│── data/                # Folder to store scraped data
└── utils/               # Utility functions (optional)

