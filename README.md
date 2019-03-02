# dynamic-web-scraping
Dynamic web scraping with selenium , pandas and chromedriver
If the data you are looking for is available in “view page source” only, you don’t need to go any further. But if you need data that are present in components which get rendered on clicking JavaScript links, dynamic scraping comes to the rescue.
Dynamic scraping uses an actual browser (or a headless browser) and lets JavaScript do its thing. Then, it queries the DOM to extract the content it's looking for.
selenium package — used to automate web browser interaction from Python
ChromeDriver — provides a platform to launch and perform tasks in specified browser

P.S -
A single slash at the start of Xpath instructs XPath engine to look for element starting from root node.
A double slash at the start of Xpath instructs XPath engine to search look for matching element anywhere in the XML document.
