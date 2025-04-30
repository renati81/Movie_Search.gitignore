#  Movie Search Engine using FAISS + Embeddings

This project is a semantic movie search tool built with Python, using FAISS and vector embeddings to retrieve similar movie titles based on user input.

##  Features
- FAISS-based vector search for fast similarity matching
- Embedding-based semantic understanding of movie plots/titles
- Clean Python-based interface with lightweight design

## Project Structure

Movie_search/ ├── app.py # Main application script ├── imdb_movies_faiss.index # FAISS index file (not uploaded) ├── Movies_dataset.csv # Source dataset (not uploaded) ├── Output.pdf # Sample result output ├── Steps to run.txt # Step-by-step execution guide ├── Read me file.docx # Project overview (not uploaded) ├── local_model_cache/ # Cache folder for model artifacts ├── venv/ # Python virtual environment

How to run - 
1. Clone this repository and navigate to the folder:
   ```bash
   git clone https://github.com/YOUR_USERNAME/Movie_search.git
   cd Movie_search

2. Create a virtual Envinorment

   -python -m venv venv
   -source venv/bin/activate   # or venv\Scripts\activate on Windows
   -pip install -r requirements.txt

3.Downlaod Required Files - FAISS Index, Dataset - {https://drive.google.com/drive/folders/1Aq8aG3dBt7EvLnwlOyiZOjovStdEsjvM?usp=drive_link}
4.Run Application - python app.py
