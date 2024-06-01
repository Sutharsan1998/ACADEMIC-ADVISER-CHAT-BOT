# ACADEMIC-ADVISER-CHAT-BOT

The Academic Advisor Chat Bot is an intelligent chat bot capable of answering academic questions from a provided PDF file. This innovative tool is designed to revolutionize how students and researchers access and utilize educational resources. The chat bot serves as a virtual academic assistant, providing users with instant access to a vast repository of knowledge, fostering self-directed learning, and enhancing overall educational experiences.

Key Features

•	PDF to JSON Conversion: The data from the PDF file is converted into a JSON format for easier processing.
•	Model Training: The JSON data is used to train the model, ensuring accurate and contextually relevant answers.
•	Instant Access: Users receive immediate responses to their academic queries, facilitating efficient and interactive learning.
•	Self-Directed Learning: Encourages users to independently explore academic topics and find answers to their questions.

 How It Works

1. Upload PDF: Users upload an academic PDF document.
2. Data Conversion: The content of the PDF is converted into a structured JSON file.
3. Model Training: The JSON data is fed into the model for training.
4. Ask Questions: Users can ask academic questions, and the chat bot will provide accurate answers based on the trained model.





 Getting Started

Prerequisites

•	Python 3.6 or higher
•	Required Python packages (listed in `requirements.txt`)

Installation

1. Install Dependencies
•	pip install -r requirements.txt
   
3. Run the Application
•	python app.py
   
Project Structure

•	app.py: The main application file.
•	chatbot.py: Contains the chatbot implementation.
•	data.pth: Trained model data.
•	model.py: Defines the model architecture.
•	nltk_utils.py: Utility functions for natural language processing.
•	tasks.json: Example JSON data used for training the model.
•	train.py: Script for training the model.

