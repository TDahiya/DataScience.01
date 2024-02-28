## Explaining How I Approached the Solution

To approach the solution, I followed these steps:

1. **Data Extraction from URLs:** 
   - I used the `requests` library to fetch the HTML content of the provided URLs. Then, I used `BeautifulSoup` for parsing the HTML and extracting the title and article text from tags.

2. **Storing Extracted Data:**  
   - The extracted title and article text were stored in text files named after their corresponding URL IDs in the "Extracted data" folder.

3. **Reading Input Data:** 
   - I read the input data from an Excel file using the `Pandas` library.

4. **Processing Text Data:** 
   - I processed the text data to perform textual analysis, including removing stop words and computing various variables.

5. **Performing Textual Analysis:** 
   - Textual analysis was performed on the extracted article text files using functions to compute the required metrics.

6. **Updating Input Data:** 
   - The computed metrics were then updated in the input data.

7. **Saving Output Data:** 
   - Finally, the updated input data with computed metrics was saved to a new Excel file.
