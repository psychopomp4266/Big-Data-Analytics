Running the Code Files: A Step-by-Step Guide

Step 1: Accessing the Code

1.	Open the report PDF or visit the corresponding webpage to access the required links.

2.	Click on the hyperlink redirecting to the Google Colab file named "CSOE_18_FPM_Assignment_1_107121045.ipynb." You can find this hyperlink embedded either in the report or on the webpage.

3.	Within the code file, make sure the following sections are visible:

"importing drive"
"Path and Support Threshold Setting"
"Functions Definitions"
"Reading Data and Generating Candidates & Frequent Itemsets"
"Closed Frequent Itemsets"
"Writing into Files"
"Cross Checking with Apriori Library in mlextend"
"Final Comparison"
"References"

If any of these sections are missing, you can refer to the .py or .ipynb files in the Google Drive folder to copy/paste or run the code.

Step 2: Setting the Directory and Thresholds

1.	Under the "Path and Support Threshold Setting" section of the code:

	*	Set the correct directory path pertaining to the dataset "categories.txt" in the required path variable.

2.	Also, set the minimum support and relative minimum supports for the required variables. Adjust these values based on your specific dataset and analysis requirements.

Step 3: Defining Minimum Threshold

1.	Under the "Reading Data and Generating Candidates & Frequent Itemsets" section:
	*	In the very first block of code, set the minimum threshold, either by calculation (e.g., 771.85, which can be rounded to 772) or manually enter the exact value (e.g., 771). Adjusting this threshold will yield different results compared to results obtained using the mlextend.apriori library.

Step 4: Comparison and Output

1.	The comparison between the developed algorithm and the library-based one is shown under the "Final Comparison" section.

2.	The corresponding .txt output files will be created/updated in the same directory set earlier.

	By following these steps, you can efficiently run the code, adjust the necessary parameters, and compare the results with the library-based approach, ensuring a comprehensive understanding of the algorithm's performance.