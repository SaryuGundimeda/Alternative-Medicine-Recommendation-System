# Alternative-Medicine-Recommendation-System
A Streamlit-based Alternative Medicine Recommendation System that suggests similar medicines using cosine similarity on preprocessed textual data. It allows users to enter a medicine name and discover alternative options efficiently.

Features
- User-friendly UI with Streamlit
- Cosine Similarity-based alternative medicine recommendations
- Text Preprocessing & Stemming for improved matching
- Interactive Search with a dropdown for medicine selection

Tech Stack
- Python
- Streamlit
- NLP (Text Preprocessing, Stemming)
- Scikit-learn (CountVectorizer, Cosine Similarity)
- Pandas

How It Works
- The dataset contains medicine names, descriptions, and reasons for use.
- Text is preprocessed, stemmed, and vectorized using CountVectorizer.
- Cosine similarity is used to compute similarity scores between medicines.
- Users can search for a medicine and get a list of alternative options.

Conclusion

MedCare provides a simple yet effective way to find alternative medicines using cosine similarity and NLP-based text processing. With an intuitive Streamlit interface, users can explore medication alternatives quickly. Future improvements could enhance accuracy with advanced ML models and larger datasets.
