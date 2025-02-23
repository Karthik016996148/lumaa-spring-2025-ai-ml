# Simple Content-Based Recommender System

**Screen Recording**: [Brief demo video link](https://youtu.be/3nPj4yEcpBE?feature=shared)

## How to Run the Code

1. **Clone the Repository**  
   - Clone or download the repository.

2. **Navigate to the Folder**  
   - Open your terminal and navigate to the repository folder containing the `mrs_sl.py` file.

3. **Install Dependencies**  
   - Make sure you have [Streamlit](https://docs.streamlit.io) and other necessary libraries installed:
     ```bash
     pip install streamlit pandas scikit-learn nltk
     ```
   - Also install and download the NLTK stopwords if you haven’t already:
     ```bash
     python -m nltk.downloader stopwords
     ```

4. **Run the Recommender App**  
   - Start the Streamlit app:
     ```bash
     cd "Your file path"
     streamlit run mrs_sl.py
     ```
   - A local web page will open in your browser (by default at `http://localhost:8501`).

## Sample Query and Results

Once the app is running:
- In the **“Type your movie genre:”** text area, enter your query.
