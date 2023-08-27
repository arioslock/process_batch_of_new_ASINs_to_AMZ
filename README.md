# Process_Batch_of_New_ASINs_to_AMZ

At work, one of my customers provided an Excel sheet that I needed to process in order to pick a batch of products and load them onto Amazon. However, there was a problem: the Excel sheet for each marketplace had over 500k rows, making it impossible for me to work with on my PC. My PC repeatedly crashed whenever I attempted to work with such a large dataset.

In response, I decided to write a simple Python script. This script takes the inventory data that the customer provides (from the 'all_listing_report' on Amazon), compares it with the ASINs we obtain from analysis (data analyzed using specialized software), and prepares a file for me. The file contains the desired number of rows specified in the function for the chosen marketplace. This file includes selected ASINs, corresponding SKUs, and prices. As a result, all I need to do is copy and paste the prepared information into the Amazon template.
