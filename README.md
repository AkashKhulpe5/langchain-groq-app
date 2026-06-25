# langchain-groq-app

## Alex: Tech AI Assistant
Alex is an intelligent AI assistant specialized in technology. Built using LangChain and the Groq API, it provides precise, expert-level answers to technical queries. With a strict system-level constraint, Alex ensures that all responses are focused exclusively on tech-related topics, politely declining any non-technical inquiries.

Key Features
Tech Specialization: Expertly handles software, hardware, and programming questions.

Pipeline Architecture: Utilizes LangChain's LCEL (LangChain Expression Language) for a clean, modular processing pipeline.

Deterministic Responses: Configured with a low temperature (0.3) to ensure consistent, reliable technical explanations.

Prompt Engineering: Systematic behavioral design using ChatPromptTemplate to maintain personality and domain scope.

Tech Stack
Framework: LangChain for orchestration.

LLM Engine: Groq API for high-speed inference.

Language: Python.

Setup Instructions
1. Installation
Install the necessary dependencies:

Bash
pip install langchain langchain-community langchain-groq langchain-core python-dotenv
2. Configuration
Create a .env file in the root directory and add your API credentials:

Plaintext
GROQ_API_KEY=your_actual_groq_api_key_here
MODEL_NAME=llama3-70b-8192
3. Execution
Run the application from the root directory:

Bash
python -m app.main
Usage
Once running, simply type your technical question into the terminal prompt. Type exit to terminate the session.
