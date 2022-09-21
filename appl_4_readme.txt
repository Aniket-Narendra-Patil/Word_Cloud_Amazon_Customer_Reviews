Application: Word Cloud.

The Amazon dataset is available in .tsv file.
The Amazon Electronics and Shoes dataset is used for this application.
Link: https://s3.amazonaws.com/amazon-reviews-pds/tsv/amazon_reviews_us_Electronics_v1_00.tsv.gz
https://s3.amazonaws.com/amazon-reviews-pds/tsv/amazon_reviews_us_Shoes_v1_00.tsv.gz

The .tsv (Tab Separated Values) file was processed and cleaned using the code file named:
'data-cleaning.ipynb'.

After cleaning the data was converted to .csv (Comma Separated Values) file and transferred to RDBMS PostgreSQL server.

For the simplicity and avoid huge file, sample datasets named 
1. appl_4_amazon_philips.csv, 
2. appl_4_amazon_toms.csv, 
3. appl_4_amazon_yoomal.csv 
have been created to create word cloud of reviews of Products.

Execution:
1. Launch the Jupyter Notebook either in your kernel or App.
2. In the Notebook Dashboard navigate to find the notebook. Open it in your browser.
3. Open the Jupyter Notebook file named: 'appl_4_word_cloud.ipynb'.
4. You can run the notebook step by step by pressing shift+enter.