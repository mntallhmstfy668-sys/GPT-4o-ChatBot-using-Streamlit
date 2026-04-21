STEM Support Chatbot

Project Idea

  - This project is a STEM Support Chatbot designed to help students in STEM fields manage their academic and mental challenges.
The chatbot provides:

-  Mental health support (stress, motivation, focus, etc.)
-  Study tips for different subjects
-   Time management and revision plans

It answers user questions based on predefined knowledge and enhances responses using AI.



 How It Works

The chatbot works using:

- Keyword-based matching to detect user intent
- Predefined datasets (mental support, study tips, revision plans)
- Integration with OpenAI API to generate enhanced responses



 Steps I Followed

1. API Setup

   - Generated an API key from OpenAI
   - Used the GPT-4o model

2. Chatbot Logic 

   - Built a chatbot system using Python
   - Designed functions to return responses based on keywords

3. Data Preparation

    Created structured datasets for:

     - Mental health support
     - Study tips (Arabic, English, Physics, etc.)
     - Time & revision plans

4. UI Development

   - Built the interface using (Streamlit)
   - Added chat input and message display

5. Deployment

   - Deployed the project using (Streamlit Cloud)
   - Made the app publicly accessible


How to Run the Project

 1. Install dependencies

 - pip install -r requirements.txt
 

 2. Add your API key
Create a '.env' file and add: 
OPENAI_API_KEY=your_api_key_here

 3. Run the app
 streamlit run main.py
 
 
 

You can try the chatbot here:
 []



 Notes:

- The chatbot relies on predefined keywords, so make sure to use supported terms while searching.
- Designed mainly for STEM students under academic pressure.

 
