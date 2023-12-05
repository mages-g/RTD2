Abstract:
The main purpose of this project was to develop a Streamlit web application using natural language processing (NLP) techniques to assist users in finding related job titles based on their input and extract commonly requested skills and experiences from job descriptions. The project aimed to provide a user-friendly interface where individuals could enter a job designation, and the app would search a preprocessed database of job descriptions to display related job titles. Furthermore, the application extracted and showcased common skills and experience required among the related job listings.

Data Description:
The data used for this project consisted of job-related information such as job titles, company names, job descriptions, work types, locations, listed times, application types, company descriptions, company sizes, industries, and matched keywords. The dataset was preprocessed, including steps like data cleaning, removing duplicates, standardizing text (lowercasing, removing special characters), and tokenizing job titles and descriptions.

Algorithm Description:
The core algorithms driving the web app included:

Tokenization and Lemmatization: Utilized spaCy's natural language processing capabilities for tokenization (splitting text into words or tokens) and lemmatization (reducing words to their base forms) of job titles, job descriptions, and keywords.
Semantic Similarity Calculation: Employed NLP techniques to calculate the semantic similarity between user-input job designations and job descriptions in the database. This facilitated the retrieval of related job titles based on similarity scores.
Tools Used:
Python: The primary programming language used for development.
Pandas: Used for data manipulation and preprocessing tasks within the DataFrame.
spaCy: Leveraged for natural language processing tasks such as tokenization, lemmatization, and semantic similarity calculations.
Streamlit: Utilized for building the user interface and creating the interactive web application.
scikit-learn: Employed for various machine learning-related functionalities if required (e.g., vectorization, similarity calculations).
Virtual Environment Tools (virtualenv/conda): Utilized for managing dependencies and creating an isolated Python environment.