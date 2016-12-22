# JSON-LD
JSON-LD structured data snippets collection for Textpattern CMS

Hight quality handcrafted codes. All snippets has been tested successfully with the "OpenLink Structured Data Sniffer" browser extension and within the official "Structured Data Testing Tool" by Google.

(The collection will be augmented with new snippets in the next days)

## Usage

All snippets can be added into your page templates by invoke a form (support for all contexts: in list or individual article):

    <txp:output_form form="snippet_name_of_your_choice_here" />

i.e.

    <txp:output_form form="JSON-LD_Person" />

The JSON-LD snippets (only one or multiples) can be added before the last `</head>` part of your HTML template or just before the last `</body>` tag.


## Snippets list and purpose

Note: check the snippet content and replace the `XXXX` where signs appaer by the information needed. The commented parts (included into `/*!` ... `*/`) are optional and can be deleted.

+ **JSON-LD_Website**: a general purpose for personal websites with the website's author name and its URL, social network's list of links, technological skills and the search page which Google can adds into the SERP.
+ **JSON-LD_Person**: a data graph for individual articles with the author informations. Name, author's URL, address email, its image, and a optional URL list of its colleagues.
+ **JSON-LD_LocalBusiness**: a data graph for small business with website URL, postal address, email address, logo, slogan, the founder name, social network links and the search page which Google can adds into the SERP.
+ **JSON-LD_Book**: in list or individual article data graph for a book store and its book details (list of different books or an individual book) with current breadcrumb page, list of pages (a breadcrumb list of pages), the local business URL, its postal address, its logo, its email address, its range of prices (default: two digits, € sign); all details for books (few custom fields are required: **Format** with ebook or paperback choices, **Price** for the price without currency symbol, **Pages** for the number of pages, **ISBN** for the ISBN code and **Language**) and the cover images.

## About JSON-LD

(coming soon)
