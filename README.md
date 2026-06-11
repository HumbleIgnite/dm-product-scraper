[Dm Product Scraper](https://apify.com/bytepulselabs/dm-product-scraper?fpr=data)

## What is dm.cz Product Scraper?

dm.cz Product Scraper automates the **extraction of product data from dm.cz**. Just provide a product category URL to scrape all the publicly available product information you need.

## Why scrape dm.cz products?

dm.cz product data can give you valuable information about pricing trends, product availability, specifications, and market analysis. This helps with competitive research, price monitoring, and market intelligence.

## How to scrape dm.cz products

dm.cz Product Scraper is designed to be fast and easy to use so there aren't too many parameters or settings. Just follow the steps below:

1. Create a free Apify account.
2. Open [dm.cz Product Scraper](https://apify.com/bytepulselabs/dm-product-scraper?fpr=k8fqp).
3. Add a product category URL from dm.cz to scrape.
4. Click "Save & Start" and wait for the datasets to be extracted.
5. Download your data in JSON, XML, CSV, Excel, or HTML.

## Input example

The input for dm.cz Product Scraper should be a **product category URL from dm.cz**. You can add one or multiple category URLs to scrape all products from those categories.

![dm.cz Product Scraper input](https://images.apifyusercontent.com/xwHfw9cp0iGNzVqhNUdSCw1nRmy0aQ5ZBe1IaLIN320/w:1800/cb:1/aHR0cHM6Ly9wdWItMjExYjE3YzgxNGFmNGZiNjk5M2IxZDkxMjNhZWVkMjEucjIuZGV2L2RtLXByb2R1Y3Qtc2NyYXBlci9pbnB1dC5qcGc.webp)

Here's a sample of scraping products from a dm.cz category page.

In JSON it looks like this:

```
{
  "urls": [{ "url": "https://www.dm.cz/zvirata/kocky/stelivo" }],
  "proxy": {
    "useApifyProxy": true,
    "apifyProxyGroups": ["RESIDENTIAL"],
    "apifyProxyCountry": "CZ"
  }
}
```

## Output example

The results will be wrapped into a dataset which you can always find in the **Storage** tab. Here's an excerpt from the data you'd get:

![dm.cz Product Scraper output](https://images.apifyusercontent.com/10go8kyhnZ3nJ5Bf0dL4EJ4Ibs8Vbgk5fPZIAPzK6HQ/w:1800/cb:1/aHR0cHM6Ly9wdWItMjExYjE3YzgxNGFmNGZiNjk5M2IxZDkxMjNhZWVkMjEucjIuZGV2L2RtLXByb2R1Y3Qtc2NyYXBlci9vdXRwdXQuanBn.webp)

Here is the same data but in JSON. You can download the dataset extracted by dm.cz Product Scraper in various formats such as JSON, HTML, CSV, or Excel.

```
{
  "id": "4066447437522",
  "name": "PROFISSIMO Formičky na zmrzlinu",
  "description": "<p>Silikonové formičky na domácí zmrzlinu s praktickými rukojeťmi pro snadné vyjmutí.</p>",
  "url": "https://www.dm.cz/profissimo-formicky-na-zmrzlinu-p4066447437522.html",
  "price": {
    "value": 149,
    "currency": "CZK"
  },
  "availability": "in stock",
  "condition": "new",
  "rating": {
    "value": 4.5,
    "count": 23
  },
  "categories": [
    "Domácnost > Kuchyně > Formy a formičky"
  ],
  "brand": "PROFISSIMO",
  "imageUrls": [
    "https://product-cdn.dm-static.com/images/66447437522_1.jpg",
    "https://product-cdn.dm-static.com/images/66447437522_2.jpg"
  ]
}
```

## Integrate dm.cz Product Scraper and automate your workflow

Last but not least, dm.cz Product Scraper can be connected with almost any cloud service or web app thanks to [integrations](https://apify.com/integrations?fpr=k8fqp) on the Apify platform.

These include:

- [Make](https://docs.apify.com/platform/integrations/make?fpr=k8fqp)
- [Zapier](https://docs.apify.com/platform/integrations/zapier?fpr=k8fqp)
- [Slack](https://docs.apify.com/platform/integrations/slack?fpr=k8fqp)
- [Airbyte](https://docs.apify.com/platform/integrations/airbyte?fpr=k8fqp)
- [GitHub](https://docs.apify.com/platform/integrations/github?fpr=k8fqp)
- [Google Drive](https://docs.apify.com/platform/integrations/drive?fpr=k8fqp)
- and [much more](https://docs.apify.com/platform/integrations?fpr=k8fqp).

Alternatively, you can use [webhooks](https://docs.apify.com/platform/integrations/webhooks?fpr=k8fqp) to carry out an action whenever an event occurs. For example, you can get a notification whenever dm.cz Product Scraper successfully finishes a run.

## Want to scrape products from other ecommerce stores?

Looking for product scrapers for other ecommerce platforms? We offer specialized product scrapers for various online stores. Each scraper is optimized for its specific platform to ensure fast, reliable data extraction with minimal configuration.

| ![alza.cz Product Scraper](https://images.apifyusercontent.com/Nf89uEur8FJsBOW1TGWW-UBYUW0BZ9Cw43PSu7uSACg/w:1800/cb:1/aHR0cHM6Ly9wdWItMjExYjE3YzgxNGFmNGZiNjk5M2IxZDkxMjNhZWVkMjEucjIuZGV2L2FsemEtcHJvZHVjdC1zY3JhcGVyL2xvZ28ucG5n.webp) [alza.cz Product Scraper](https://apify.com/bytepulselabs/alza-product-scraper?fpr=k8fqp) | ![dm.cz Product Scraper](https://images.apifyusercontent.com/ZbU2Ck2qC89br4vcyPX37HO-AezSeVGT3yOTEOLVPts/w:1800/cb:1/aHR0cHM6Ly9wdWItMjExYjE3YzgxNGFmNGZiNjk5M2IxZDkxMjNhZWVkMjEucjIuZGV2L2RtLXByb2R1Y3Qtc2NyYXBlci9sb2dvLnBuZw.webp) [dm.cz Product Scraper](https://apify.com/bytepulselabs/dm-product-scraper?fpr=k8fqp) |
| --- | --- |
| ![kytary.cz Product Scraper](https://images.apifyusercontent.com/0Ws78BwbhX8a6b5Kfbg4ObI_Nu9UfHQWSM8sPrfuG-A/w:1800/cb:1/aHR0cHM6Ly9wdWItMjExYjE3YzgxNGFmNGZiNjk5M2IxZDkxMjNhZWVkMjEucjIuZGV2L2t5dGFyeS1wcm9kdWN0LXNjcmFwZXIvbG9nby5wbmc.webp) [kytary.cz Product Scraper](https://apify.com/bytepulselabs/kytary-product-scraper?fpr=k8fqp) | ![smarty.cz Product Scraper](https://images.apifyusercontent.com/LSg4Pa2JQNmdlEu7a2DSwDWyq68TjunS0hmYVqgeoqU/w:1800/cb:1/aHR0cHM6Ly9wdWItMjExYjE3YzgxNGFmNGZiNjk5M2IxZDkxMjNhZWVkMjEucjIuZGV2L3NtYXJ0eS1wcm9kdWN0LXNjcmFwZXIvbG9nby5wbmc.webp) [smarty.cz Product Scraper](https://apify.com/bytepulselabs/smarty-product-scraper?fpr=k8fqp) |
| ![underarmour.cz Product Scraper](https://images.apifyusercontent.com/1cGkOOT-r48Vj4d9z5eSgz7hhLrqTj8ekIZ1rvwzAEI/w:1800/cb:1/aHR0cHM6Ly9wdWItMjExYjE3YzgxNGFmNGZiNjk5M2IxZDkxMjNhZWVkMjEucjIuZGV2L3VuZGVyLWFybW91ci1wcm9kdWN0LXNjcmFwZXIvbG9nby5wbmc.webp) [underarmour.cz Product Scraper](https://apify.com/bytepulselabs/under-armour-product-scraper?fpr=k8fqp) | ![zoot.cz Product Scraper](https://images.apifyusercontent.com/PMNPi6RB2Zwuig-SKvAfex7oGt6OLnCdJusdPuq3g2g/w:1800/cb:1/aHR0cHM6Ly9wdWItMjExYjE3YzgxNGFmNGZiNjk5M2IxZDkxMjNhZWVkMjEucjIuZGV2L3pvb3QtcHJvZHVjdC1zY3JhcGVyL2xvZ28ucG5n.webp) [zoot.cz Product Scraper](https://apify.com/bytepulselabs/zoot-product-scraper?fpr=k8fqp) |

## Your feedback

We're always working on improving our Actors' performance. If you have any technical feedback for dm.cz Product Scraper or simply found a bug, please create an issue on the Actor's [Issues tab](https://apify.com/bytepulselabs/dm-product-scraper/issues?fpr=k8fqp) in Apify Console.

## FAQ

### How can I use dm.cz Product Scraper with the Apify API?

The Apify API gives you programmatic access to the Apify platform. [The API](https://apify.com/bytepulselabs/dm-product-scraper/api?fpr=k8fqp) is organized around RESTful HTTP endpoints that enable you to manage, schedule, and run Apify actors. The API also lets you access any datasets, monitor actor performance, fetch results, create and update versions, and more.

To access the API using Node.js, use the `apify-client` NPM package. To access the API using Python, use the `apify-client` PyPI package.

Check out the [Apify API reference](https://docs.apify.com/api/v2?fpr=k8fqp) docs for full details or click on the [dm.cz Product Scraper API tab](https://apify.com/bytepulselabs/dm-product-scraper/api?fpr=k8fqp) for code examples.

### How much does it cost to use dm.cz Product Scraper?

dm.cz Product Scraper uses the **Pay-per-result** pricing model, so your costs can be easily calculated: it will cost you **$6 to scrape 1,000 results**, so $0.006 per item.

Given that with the [Apify Free plan](https://apify.com/pricing?fpr=k8fqp), you get **$5 in credits monthly for free**, this tool might be your best free product scraper of all.