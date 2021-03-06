# ❴❵ JSON-LD
JSON-LD structured data snippets collection for Textpattern CMS

Hight quality handcrafted codes collection. All snippets has been tested successfully with the "OpenLink Structured Data Sniffer" browser extension and within the official "Structured Data Testing Tool" by Google. Multiple case studies for your conveniences. No headaches; just copy/paste!

(The collection will be augmented with new snippets in the next days)

## Usage

All snippets can be added directly into your page templates or by invoke a form (support for all contexts: in list or individual article):

    <txp:output_form form="snippet_name_of_your_choice_here" />

i.e.

    <txp:output_form form="JSON-LD_Person" />

The JSON-LD snippets (only one or multiples) can be added before the last `</head>` part of your HTML template or just before the last `</body>` tag.


## Snippets list and purpose

Note: check the snippet content and replace the `XXXX` where signs appaer by the information needed. The commented parts (included into `/*!` ... `*/`) are optional and can be deleted.

+ **JSON-LD_BedAndBreakfast**: a data graph for logging or B&B.
+ **JSON-LD_BlogPosting**: a data graph for individual blog article types.
+ **JSON-LD_Book**: in list or individual article data graph for a book store and its book details (list of different books or an individual book) with current breadcrumb page, list of pages (a breadcrumb list of pages), the local business URL, its postal address, its logo, its email address, its range of prices (default: two digits, € sign); all details for books (few custom fields are required: **Format** with ebook or paperback choices, **Price** for the price without currency symbol, **Pages** for the number of pages, **ISBN** for the ISBN code, **Stock** for availability and **Language**) and the cover images.
+ **JSON-LD_Breadcrumb**: display your navigation structure based on sections into the Google search results (SERP) directly under your site name as  cliquable links into an arrows separated list.
+ **JSON-LD_ItemList**: a graph for your article page to display relationship within related articles (based on their categories).
+ **JSON-LD_LocalBusiness**: a data graph for small business with website URL, postal address, email address, logo, slogan, the founder name, social network links and the search page which Google can adds into the SERP.
+ **JSON-LD_NewsArticle**: a data graph for individual article news.
+ **JSON-LD_Person**: a data graph for individual articles with the author informations. Name, author's URL, address email, its image, and a optional URL list of its colleagues.
+ **JSON-LD_Photograph**: a data graph for photographers.
+ **JSON-LD_Place**: a data graph for business location.
+ **JSON-LD_ProfessionalService**: a data graph for displaying professional services and offers.
+ **JSON-LD_Restaurant**: a data graph suitable for a restaurant.
+ **JSON-LD_TVSeries**: a data graph for broadcasting and tv series.
+ **JSON-LD_WebPage**: a data graph for general purpose web pages.
+ **JSON-LD_Website**: a general purpose for personal websites with the website's author name and its URL, social network's list of links, technological skills and the search page which Google can adds into the SERP.

## About JSON-LD

The JSON-LD ("JSON for Linking Data") structured data graph for machines (Crawler Bots) is the latest technology recommended by Google and replace the old microdata markup (Schema.org). It is the prefered choice by SEO specialists because all the informations are located into a unique javascript JSON array, never more within the entire HTML document: simple acess and all changes are made easier.

[JSON-LD W3C Recommendation](https://www.w3.org/blog/news/archives/3589)

[Bing supports JSON-LD](https://searchengineland.com/bing-announces-bing-amp-viewer-json-ld-support-in-bing-webmaster-tools-300037)

[Google dedicated online documentation](https://developers.google.com/schemas/formats/json-ld)

[The Google Official Structured Data Testing Tool](https://search.google.com/structured-data/testing-tool)

[MOZ website](https://moz.com/blog/using-google-tag-manager-to-dynamically-generate-schema-org-json-ld-tags)

[JSON-LD dedicated website](json-ld.org/)

[Schema App JSON-LD markup online generator](https://www.schemaapp.com/tools/jsonld-schema-generator/)
