### Q&A: Question and Answer System Based on Google Palm LLM and Langchain for E-learning company 🚀

This is an end-to-end LLM project based on Google Palm and Langchain, aimed at building a Q&A system for the e-learning company, Codebasics (website: codebasics.io). Codebasics specializes in selling data-related courses and bootcamps, catering to thousands of learners who currently use Discord or email to ask questions. The goal is to provide a streamlined, user-friendly interface using Streamlit, where students can ask questions and receive prompt answers.

## Project Highlights 🌟

- Utilizes a real CSV file of FAQs currently employed by Codebasics for their courses.
- Designed to assist Codebasics' human staff by reducing their workload through an LLM-based Q&A system.
- Empowers students to ask questions directly and receive instant responses.

## Technologies and Learning Opportunities 🧠

- **Langchain + Google Palm:** Leveraging Large Language Models (LLM) for Q&A functionality.
- **Streamlit:** Creating a user interface that is interactive and easy to use.
- **Huggingface Instructor Embeddings:** Implementing text embeddings for enhanced understanding.
- **FAISS:** Employing vector databases for efficient storage and retrieval.

## Installation 🛠️

1. Clone this repository to your local machine:

```bash
git clone https://github.com/Uttampatel1/question-and-answer_system_for_real_e-learning_company.git
```

2. Navigate to the project directory:

```bash
cd question-and-answer_system_for_real_e-learning_company
```

3. Install the required dependencies using pip:

```bash
pip install -r requirements.txt
```

4. Acquire an API key through makersuite.google.com and place it in the .env file:

```bash
GOOGLE_API_KEY="your_api_key_here"
```

## Usage 🚀

1. Run the Streamlit app:

```bash
streamlit run main.py
```

2. The web app will open in your browser.

   - To create a knowledge base of FAQs, click on the "Create Knowledge Base" button. Wait for the knowledge base to be generated; a directory called "faiss_index" will appear in your current folder.

   - You are now ready to ask questions. Type your question in the Question box and hit Enter.

## Sample Questions 🤔

- Do you guys provide internships, and do you offer EMI payments?
- Do you have a JavaScript course?
- Should I learn Power BI or Tableau?
- I have a MAC computer. Can I use Power BI on it?
- I don't see Power Pivot. How can I enable it?

## Project Structure 📁

- **main.py:** The main Streamlit application script.
- **langchain_helper.py:** Contains all the Langchain code.
- **requirements.txt:** A list of required Python packages for the project.
- **.env:** Configuration file for storing your Google API key.

Feel free to explore, ask questions, and contribute to make this project even more awesome! 🚀👩‍💻👨‍💻
