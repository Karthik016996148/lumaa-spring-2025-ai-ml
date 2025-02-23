# Simple Content-Based Recommender System

**Screen Recording**: [Brief demo video link](https://youtu.be/3nPj4yEcpBE?feature=shared)

## How to Run the Code

1. **Clone the Repository**  
   - Clone or download the repository.

2. **Install Dependencies**  
   - Make sure you have [Streamlit](https://docs.streamlit.io) and other necessary libraries installed:
     ```bash
     pip install streamlit pandas scikit-learn nltk
     ```
   - Also install and download the NLTK stopwords if you haven’t already:
     ```bash
     python -m nltk.downloader stopwords
     ```
3. **Run .ipynb file**
   - Open the file in google colab and upload the dataset.
   - Run all the cells and install dependencies if needed.
     
4. **Run the Recommender App (.py file)**  
   - Open cmd navigate to the folder containing the `mrs_sl.py` file in your desktop (make sure all the files are in the same folder):
     ```bash
     cd "Your folder path"
     streamlit run mrs_sl.py
     ```
   - A local web page will open in your browser (by default at `http://localhost:8501`).

## Sample Query and Results

Once the app is running:
- In the **“Type your movie genre:”** text area, enter your query.
