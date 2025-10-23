**AI-Powered Sales Data Chatbot**
 **Project Overview**

The AI Sales Data Chatbot is an intelligent automation system built in Jupyter Notebook that allows users to query sales datasets using natural language.
Instead of writing complex SQL or Python queries, users can simply ask questions like:

“What were the total sales in 2024?”
“Which region performed best in Q3?”
“Show me the top 5 products by profit.”

The chatbot leverages Large Language Models (LLMs) and Pandas-based data analysis to interpret user intent and generate dynamic insights from the dataset.

**Key Features**

1-Natural Language Querying: Ask questions about your dataset in plain English.

2-Automated Insights: Generates relevant visualizations or summary tables automatically.

3-Dynamic Code Generation: LLM translates user queries into valid Python (Pandas) operations.

4-Dataset-Agnostic: Works with any structured CSV or Excel dataset.

5-Real-Time Analytics: Instantly returns key metrics and trends.

6-Interactive Workflow: Runs seamlessly within a Jupyter Notebook environment.

**Tech Stack**
Component	Description
Python	Core programming language
Jupyter Notebook	Interactive development and testing environment
Pandas	Data manipulation and analysis
LangChain / OpenAI API	For natural language understanding and code generation
Matplotlib / Seaborn	Data visualization
dotenv	API key management
JSON / Regex	Parsing and formatting chatbot responses

 How It Works

Data Upload: User uploads a CSV/Excel dataset into the notebook.

Question Input: User asks a question in plain English (e.g., “Which category had the highest profit?”).

LLM Interpretation: The LLM interprets the question and generates the corresponding Python (Pandas) code.

Execution & Output: The generated code runs automatically and returns:

A numeric/text answer

A data table (if relevant)

A visualization (bar chart, line chart, etc.)

 **Setup Instructions**

Clone this repository:

git clone https://github.com/<your-username>/AI-Sales-Chatbot.git
cd AI-Sales-Chatbot


**Install dependencies:**

pip install -r requirements.txt


**Set up your API key:**

Create a .env file in the root folder.

**Add your OpenAI API key:**

OPENAI_API_KEY=your_api_key_here


**Launch the notebook:**

jupyter notebook "chatbot for salesdata.ipynb"

 **Example Queries**
Example Question	Expected Output
  1-“Total sales for 2024”	Numeric KPI
  2-“Show profit by category”	Bar chart visualization
  3- “Which region had the lowest sales?”	Region name and values
  4- “Trend of revenue over time”	Line chart


**Potential Use Cases**

*Business Analysts who want fast insights without coding

*Data teams looking to automate reporting

*Non-technical users exploring datasets interactively

*Educational projects demonstrating AI + data integration

 **Future Enhancements**

*Add support for multi-turn conversations

*Enable voice-based querying

*Integrate with Power BI or Tableau for hybrid insights

*Add memory for contextual follow-up questions

***Author***

Priyal Seth
Data Analyst | AI Automation Enthusiast | LLM & Power BI Explorer

📫 Connect on LinkedIn
 | 🌟 Star this repo if you found it useful!

"Turning sales data into smart insights — powered by AI and automation."
