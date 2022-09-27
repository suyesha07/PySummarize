# PySummarize
A NLP based text summarizer. Can summarize PDF documents and Wikipedia articles too.

--------------------------------------------
Uses NLTK for Python to enable tokenisation and core NLP features for Extractive Summarisation, and Hugging Face Transformers for Abstractive Summarisation, with Streamlit for front-end.

## PDF Summariser
Uses Streamlit upload feature, and PDFPlumber to parse text in the PDF. Issues with academic papers which causes some text to become garbled. Works well on non-technical text.

## Wikipedia Summariser
Uses BeautifulSoup to extract text from HTML before passing through the text summarisation engine.

## Textbox Summariser
Basic textbox to allow for copy and paste entry of text for summarisation.

### Installation Instructions
1. Install requirements - `pip install -r requirements.txt`
2. Run streamlit - `streamlit run app.py`

In the demo, you can test out extractive summarisation.

Live demo here: https://suyesha07-pysummarize-app-kwx0pp.streamlitapp.com/

