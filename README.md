# Introduction 
The **Fintech_Lab_10-k_scraping.ipynb** is used to download 10-k filling from SEC. The notebook downloads 10-k filling of 3 given companies.
The **Chat_with_pdf_FTL_GT** is used to run [this code](https://github.com/ShubhamAXS19/Fintech-Lab-GT) on a hosted piece computer (Google Colab in our case)

## Pre-processing performed in Fintech_Lab_10-k_scraping notebook 
1. Renaming each directory inside the 10-k directory to it's year of filling.
2. Converting the downloaded filling to simple text ( Few fillings are in HTML format )
3. Renaming each year's filling to it's respective year.
4. Removing extra spacing between words and paramgraphs and converting the .txt filling to .pdf.
5. To run the notebook just upload the notebook on colab and run all the cells.

## How to run Chat_with_pdf_FTL_GT notebook.
1. Run the first 5 cells and before running the 6th cell provide your API key and then execute the rest of the cells.
2. After executing the last cell you will see a link as an output of the cell click on the link.
3. The link opens a new tab and in this tab provide your IP address ( obtained in cell 10 ) and click on submit.
4. A streamlit app will be displayed on the screen.
5. On the left sidebar click on browse button. This button allows you to upload your own PDF.
6. After the pdf's are uploaded (when all the blue progress bar are completed for each pdf ) click on process button.
7. Once the pdf's are processed you can interact with and ask questions to the pdf.
8. To generate visualization just provide a note while prompting to generate HTML.


## Why i chose streamlit and colab notebook for the assignment 
**Ans** 
1. Streamlit makes it to build a web app with very less amount of code and provides abstration over all the small details that must be take care if building a web app from scratch.
2. With the free tier of colab notebook 1 or 2 large pdf can be easily processed and a window's or mac user can run the project with the os and hardware architecture issues.
3. If user have colab pro then more than 10 pdf's can processed and can be utilized to generate insight's.



## NOTE
I was not able to create visualiztion's because it was not possible to run the code locally or on google colab.
Local issue - No GPU on macbook m1 air.
Colab issue - No access to colab pro. 
