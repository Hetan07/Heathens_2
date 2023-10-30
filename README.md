# AI/ML Ecosystem for Legal Workflow Enhancement

An AI-driven ecosystem developed by team HEATHENS for the NEXUS'23 Hackathon organized by DEVFOLIO . Our platform is designed to enhance the efficiency of legal councils and attorneys in their workflow to 
increase their productivity and output

## Features

Here's a comprehensive overview of the key features of our web app:

1. **Chatbot for Legal Queries**
   - We have designed a chatbot based on LLM provided by OpenAI that is specifically tailored to handle legal queries. It can provide easy references to previous cases and laws, making it an invaluable resource for legal professionals and
can handle the real-time circumstances put forth by the lawyers

2. **Document Simplification**
   - Our platform includes a document simplification feature that can simplify various legal documents, including legal textbooks and petitions. This feature saves time and improves document readability.

3. **Case Timeline Management**
   - Legal professionals can input the current timeline and facts of ongoing cases. The platform allows them to summarize the case briefly with key facts, providing an organized overview of each case.

4. **Case Prediction Model**
   - We offer a case prediction model that enables lawyers to input evidence related to their cases. This model can provide predictions and insights into the potential outcomes of the cases.

## Getting the API Key

Before using the web app, you need to obtain an API key. Follow these steps to obtain and update the API key in the relevant apps:

1. **OpenAI API Key:**
   - Visit the [OpenAI website](https://www.openai.com) and sign up or log in to your account.
   - Create an API key in your OpenAI account and copy it.

2. **Update API Key in Apps:**
   - Update the API key in the following files within your local repository:
     - `openai.js`
     - `1_chatbot.py` 

## Getting Started

Follow these steps to get our web app up and running on your local machine:

1. Clone this repository:

   ```bash
   git clone https://github.com/your-repo-url.git
   cd your-repo-folder

2. Install Node.js packages into your local repository by running ```npm install```

3. Start the local development server with the ```npm run``` command.

4. Access the web app at http://localhost:your-port in your web browser.

Dependencies

Here are some of the key technologies and libraries used in our project:

- Node.js
- Python
- Hugging Face Transformers
- OpenAI API

----

One can specifically run the huggingface built model locally by running the app.py locally. This uses the streamlit services along with OpenAI API. 

----
Made and created By Team Heathens:
Contributors:
HETANSHU MALIK
SHIVANSHU VERMA

