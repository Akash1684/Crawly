# Crawly
A naive web crawler designed in Python that uses spider technique to crawl through the pages.

Module Details
---

* `handle_starttag` - This procedure takes base URL is input, which then combine a relative URL with the base URL to create an absolute URL.
* `getLinks` - This is a new function that we are creating to get links that our spider() function will call.
* `spider` - This procedure takes URL, search word and number of maximum pages as input and parse the webpage to search the word. It also adds URLs present in that webpage to the collection.

Dependencies
---

* html.parser
* urllib
