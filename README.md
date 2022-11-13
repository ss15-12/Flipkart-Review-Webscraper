# Flipkart-Review-Webscraper
This is the code for a basic program which scrapes the content from the flipkart website and configures it in a proper manner


For this module we use python,the main main emphasis is on using its library for webscraping i.e Beautiful Soup(bs4) and also 
other necessary libraries like pandas etc.


The following is the methodology we use for the module:



		1)First we import the required libraries 
		2)Then we choose a website in this case flipkart website, and in detail the product review website for that product
		3)Extract the required content from beautiful soup
		4)Categorize the content extracted from beautiful soup into 7 different lists containing various attributes like date, time ,location,summary ,review etc.
		5)For all the elements which have the required class tag append the properties of them into the required lists.
		6)By this time you should have seven lists,try printing them and see the different attributes they display related to the review.
		7)Store all the lists in a dataframe.
		8))The last step is to convert the dataframe into a csv file,the csv file will create itself and appear in the general directory on which ever platform you are working on.
		

The following are available in the repository :
			
			
			1)The entire notebook,with required comments for easier undertsanding
			2)The CSV file generated from the above code.
      
