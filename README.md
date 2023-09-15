# simple_web_search_engine
Building a Web Search Engine with Scrapy and PyTerrier

To run the program:

1. run "scrapy crawl corkwiki"
        Scrap the Cork Wiki page, get all the links and store them in a file named "link.txt"
        Scarp all the links and download the web page as a document for further indexing


2. run the indexer.py file
        Note: Depending upon the environment you might have to comment out or change the JDK path (4th line in code)
        It will move all the Document files to a folder named "DocumentCollection"
        Index it and the result will be the document ranked based on the relevance to "Cork City"
