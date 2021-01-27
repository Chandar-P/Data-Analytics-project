# Data-Analytics-project
Data scrapping of the website flipkart.com using Python

Objective: The objective of this project is to scrap data using Python from the website flipkart.com. The target product is Desktop PCs.
Description: Using Python, we are able to extract data pertaining to all the Desktop PCs that are available for sale in the online store Flipkart. The tools that are used in this exercise are Pandas (a software library in Python that is used for data manipulation and analysis), BeautifulSoup (another software library in Python used for pulling data out of HTML and XML files).
Methodology: We use a function called ‘requests’ to get the content of our target item (Desktop PCs) from the website. We then get the html content of our product using the function ‘soup’ and then print them for our study using another function called ‘prettify’. We then apply the appropriate xml tags used for different elements in Desktop PC – Brand name, processor, operating system, storage capacity, display size of the PC monitor, price, discount, warranty etc to fetch them as an organized output called Data Frame.
Outcome: A new dataset that is created in a tabular form with all the details of the Desktop PCs currently available in Flipkart becomes our expected outcome.
