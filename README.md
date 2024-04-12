# NLP Web App
This is a Natural Language Processing (NLP) Web Application built using Streamlit and various pre-trained transformer models.
The app provides several functionalities for processing textual data, including text summarization, named entity recognition, sentiment analysis, question answering, and text completion.

<p align="center">
<img src="https://github.com/Francisco-Guillen/NLPWebApp/assets/83434031/326d021a-d2ac-4b59-8bd3-a01d2a2e0e96" width="900">
<br>
  Figure 1: Web Application Example
</p>

## Key Features
1. Advanced Text Summarizer: Summarize input text to a specified number of words.
2. Named Entity Recognition: Extract named entities from the input text.
3. Sentiment Analysis: Determine the sentiment (positive, negative, or neutral) of the input text.
4. Question Answering: Provide answers to questions based on a given context.
5. Text Completion: Automatically complete incomplete text using AI.

## Prerequisites
- Streamlit
- Stqdm
- Pandas
- Transformers
- Spacy
- Spacy-streamlit

## How to Run
1. Clone this repository.
2. Install dependencies: pip install -r requirements.txt
3. Additionally, download the en_core_web_trf model for SpaCy:

```bash
python -m spacy download en_core_web_trf
```

5. Run the Streamlit app: streamlit run app.py
6. Choose one of the available functionalities from the sidebar menu to interact with the NLP models.

## Functionality
1. Advanced Text Summarizer
To use the text summarization feature, select "Summarizer" from the sidebar menu.
Enter the text you want to summarize in the text area provided.
Specify the number of words you want the summary to contain.
Click on the "Summarize" button to generate the summary.
2. Named Entity Recognition
Select "Named Entity Recognition" from the sidebar menu.
Enter the text from which you want to extract named entities in the text area provided.
The application will display the identified named entities in the input text.
3. Sentiment Analysis
Choose "Sentiment Analysis" from the sidebar menu.
Enter the text for which you want to determine the sentiment in the text area provided.
The application will classify the sentiment of the input text as positive, negative, or neutral.
4. Question Answering
Select "Question Answering" from the sidebar menu.
Provide the context and ask a question related to the context in the text areas provided.
The application will generate the answer to the question based on the provided context.
5. Text Completion
Choose "Text Completion" from the sidebar menu.
Enter incomplete text in the text area provided.
The application will automatically complete the text using AI.




