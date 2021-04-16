# Financial-Statements-Analysis
(A) Scrape data from SEC Edgar, (B) Analyze financial data of a company as a PRO using Python.

1. SEC EDGAR grants free access to all annual and quarterly financial reports of companies (US registration) for which disclosures are mandatory.
2. There are python packages exist that offer automatic scraping and download of statements, but I did not find one that is 'hassle free' and flexible enough to my requirements. 
3. With the help of knowledgeable folk out there in the wild net, wrote a simple function to scrape access to 10-K fillings and function to parse reports of interest.
4. In this project I applied functions to get data for Tesla, but all is easily customizable to extract data for any other listed company, refer to getting_data/Scraping.ipynb
5. In the second (Tesla.ipynb) notebook I review statements to get insight into financial health of the company and calculate its standard risk ratios. There are much more analyses that can be done with all the available information, my primary interest with Tesla was to understand if there is anything that justifies recent extreme valuation of it by the market.

Note: apparently github viewer does not render plotly graphs (used in the notebook), hence I recommend to view Tesla notebook in https://nbviewer.jupyter.org/
