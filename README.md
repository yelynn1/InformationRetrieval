# Information Retrieval

## Source Codes
The source codes and dataset can be downloaded or cloned from the GitHub repository below:
https://github.com/yelynn1/InformationRetrieval

### Description	File Name
1) Final IR Codes and Size Compression Optimization.ipynb  
For all Information Retrieval Indexing and Size Compression Codes

2) Final Time Comparison Codes.ipynb

   Time Comparison of Search Queries (includes codes for skip pointers optimization and short-to-long merge postings optimization)
 
3) wikiScraper.ipynb

   Wikipedia Scrapper Codes

Jupyter Notebook is the preferred IDE application to open the .pynb Python notebook files above as it is able to have multiple outputs displayed from each cell.

## Dataset
The dataset can be downloaded from the following links:
1) Actual Dataset of Individual Text Documents (already processed to remove HTML tags)
   File Name: datafull-lean.rar
   File Size: 178 MB
   Expands to about 524 MB
   https://entuedu-my.sharepoint.com/:u:/g/personal/mloh010_e_ntu_edu_sg/EdKbtFaGGkdCsLiOE65udRgBr11qvfKbEI0rnbJzIgspZA?e=zpzfDC

2) Pickle files to work in conjunction with the Final Time Comparison Codes.ipynb.
   The pickle files save a backup of the postings list, docID dictionaries and time_to_index as Python objects so that there is no need    to go through the whole indexing process just to generate the inverted index.
   https://entuedu-my.sharepoint.com/:u:/g/personal/mloh010_e_ntu_edu_sg/EZT_CS6YokBFjz6xxQcowKMBnW6BWyVuf5xuSzTAlcisAg?e=BINPFD
   File Name: backup.rar 
   File Size: 42.5 MB
   Expands to about 118 MB
