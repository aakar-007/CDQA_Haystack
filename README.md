# haystack
Haystack with ES + TFIdf

Optimal combination for the best results of closed domain Question Answering.

Steps:
1) Load :PDF/doc
2) Convert :Doc/PDFtoText
3) Preprocessor:Clean and Split
4) Retriever
5) Reader
6) Pipeline
7) Query




Haystack API: listens on port 8000
DocumentStore (Elasticsearch): listens on port 9200
Streamlit UI: listens on port 8501

Upload all the documents in data directory on colab
