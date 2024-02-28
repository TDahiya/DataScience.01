## How to run the .py file to generate output

1. **Install Required Libraries:** 
   - Make sure you have installed the necessary libraries mentioned at the beginning of the script (`requests`, `beautifulsoup4`, `nltk`, `pandas`).

2. **Prepare Input Data:** 
   - Ensure that you have an input Excel file named `Input.xlsx` with the necessary URLs and URL IDs.

3. **Prepare Stop words and Master Dictionary Files:**
   - Make sure you have the required stop words and master dictionary files in the specified folders (`stopwords` folder for stop words and `MasterDictionary` folder for positive and negative words).

4. **Run the Script:** 
   - Execute the Python script (saved as a `Test.py` file). The script will extract content from the provided URLs, perform textual analysis, and save the updated input data to a new Excel file named `Input.xlsx`.

5. **Check Output:** 
   - After running the script, you can check the `Input.xlsx` file to view the computed metrics for each URL.
