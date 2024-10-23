This project extracts organization names from multiple .docx documents using Natural Language Processing (NLP). It processes the documents, identifies named entities of type ORGANIZATION, and outputs the unique organization names. The project uses Python and NLTK (Natural Language Toolkit) for named entity recognition (NER).

Key Features
Document Loading: Automatically loads multiple Word (.docx) files and extracts the text using python-docx.
Named Entity Recognition (NER): Leverages NLTK's ne_chunk, pos_tag, and word_tokenize to perform Named Entity Recognition for organization names.
Error Handling: Implements robust error handling to manage potential issues with loading and processing document files.
Organization Extraction: Extracts unique and sorted organization names from text data and outputs them for further analysis.

Use Case
This project can be applied in scenarios where users need to process a large volume of documents to extract organization names, such as:
Competitive analysis for market research
Analyzing partnership networks or company mentions in industry reports
Automated data extraction from legal or financial documents
Key Skills Used
Python: Main programming language used for text extraction and NER.
NLTK (Natural Language Toolkit): Used for tokenization, part-of-speech tagging, and named entity chunking.
python-docx: For reading and extracting text from Word documents.
Error Handling: Managing potential file processing errors to ensure smooth execution.
Text Processing: Techniques for extracting and cleaning textual data from documents.
