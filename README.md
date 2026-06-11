[Dm Product Scraper](https://apify.com/m3web/dm-product-scraper?fpr=data)

## Overview

Easily collect product data from DM-drogeriemarkt websites across all countries where the company operates. This scraper supports product categories, filtered results, and individual product URLs, making it ideal for gathering detailed product information such as GTIN, name, brand, price, availability, ratings, and more.

| Website | Country |
| --- | --- |
| [www.dm.de](https://www.dm.de/) | Germany |
| [www.dm-drogeriemarkt.at](https://www.dm-drogeriemarkt.at/) | Austria |
| [www.dm-drogeriemarkt.ba](https://www.dm-drogeriemarkt.ba/) | Bosnia and Herzegovina |
| [www.dm-drogeriemarkt.bg](https://www.dm-drogeriemarkt.bg/) | Bulgaria |
| [www.dm.hr](https://www.dm.hr/) | Croatia |
| [www.dm.cz](https://www.dm.cz/) | Czech Republic |
| [www.dm.hu](https://www.dm.hu/) | Hungary |
| [www.dm-drogeriemarkt.it](https://www.dm-drogeriemarkt.it/) | Italy |
| [www.dm.pl](https://www.dm.pl/) | Poland |
| [www.dm.ro](https://www.dm.ro/) | Romania |
| [www.dm.rs](https://www.dm.rs/) | Serbia |
| [www.dm.sk](https://www.dm.sk/) | Slovakia |
| [www.dm.si](https://www.dm.si/) | Slovenia |

## Features

- Supports product categories, filtered results and individual product URLs.
- Fetches detailed product information, including GTIN, name, price, brand, availability, ratings, and more.

**Important Notice on "/search" URLs**

This scraper is designed to comply fully with the website's [robots.txt](https://www.dm.de/robots.txt) rules. According to these rules, URLs containing "/search" are disallowed and therefore will be automatically skipped by the scraper. Users are advised not to generate URLs using the search functionality of the website, as such URLs will not be processed. The scraper ensures adherence to these rules to respect the website's terms of service and policies.

## URL examples

- Category: [https://www.dm.de/pflege-und-parfum/parfum/damen-parfum](https://www.dm.de/pflege-und-parfum/parfum/damen-parfum)
- Category with filters: [https://www.dm.de/pflege-und-parfum?allCategories.id0=020000&pageSize0=10&sort0=editorial_relevance&brandName0=NIVEA&currentPage0=0](https://www.dm.de/pflege-und-parfum?allCategories.id0=020000&pageSize0=10&sort0=editorial_relevance&brandName0=NIVEA&currentPage0=0)
- Single Product [https://www.dm.de/nivea-gesichtscreme-in-der-dose-p4005900917171.html](https://www.dm.de/nivea-gesichtscreme-in-der-dose-p4005900917171.html)

**Scraping Limitations per URL for "Category URL"**

The maximum number of products that can be scraped from one "Category URL" or "Category URL with filters" is limited to **200**. If the total product count exceeds 200, use multiple URLs from subcategories or apply filters to stay within the limit. There is no restriction on the overall number of results you can collect using this scraper.

## Results

### Sample Output

The following is a sample output you can expect from the DM Product Scraper:

**From Product Category URL**

```
{
    "website": "dm.de",
    "gtin": 8411061041673,
    "dan": 1598845,
    "brand": "CAROLINA HERRERA",
    "title": "Good Girl Eau de Parfum, 30 ml",
    "category": "Damen Parfum",
    "image": "https://products.dm-static.com/images/f_auto,q_auto,c_fit,h_320,w_320/v1747524668/assets/pas/images/ec835906-2a35-4d8e-9cf2-4b0f2c798485/carolina-herrera-good-girl-eau-de-parfum",
    "priceCurrency": "EUR",
    "price": 59.95,
    "url": "https://www.dm.de/carolina-herrera-good-girl-eau-de-parfum-p8411061041673.html",
    "ratingValue": 4.9,
    "ratingCount": 10,
    "additionalData": {
      "priceInfo": {
        "tileInfos": ["0,03 l (1.998,33 € je 1 l)"],
        "price": { "current": { "value": "59,95 €" } },
        "prefix": "Einzelpreis"
      },
      "netPriceInfo": {
        "tileInfos": ["0,03 l (1.679,27 € je 1 l)"],
        "price": { "current": { "value": "50,38 €" } },
        "prefix": "Einzelpreis"
      },
      "categories": ["Damen Parfum"],
      "a11yLabel": "Marke: CAROLINA HERRERA; Produktname: Good Girl Eau de Parfum, 30 ml; Preis: 59,95 €; Grundpreis: 0,03 l (1.998,33 € je 1 l); Nur im Online-Shop erhältlich; 4,9 von 5 Sternen bei 10 Bewertungen"
    }
  }
```

**From Single Product URL**

```
{
    "website": "dm.de",
    "gtin": 4005900917171,
    "dan": 1442173,
    "brand": "NIVEA",
    "title": "Gesichtscreme in der Dose, 250 ml",
    "category": "Bodylotion & Hautcreme",
    "image": "https://products.dm-static.com/images/f_auto,q_auto,c_fit,h_440,w_500/v1755095906/assets/pas/images/290af9fc-c152-4bd1-a528-6d11d13ffc47/nivea-gesichtscreme-in-der-dose",
    "priceCurrency": "EUR",
    "price": 3.65,
    "url": "https://www.dm.de/nivea-gesichtscreme-in-der-dose-p4005900917171.html",
    "ratingValue": 4.8229,
    "ratingCount": 638,
    "additionalData": {
      "priceInfo": {
        "infos": [
          "0,25 l (14,60 € je 1 l)",
          "inkl. MwSt. zzgl. <linking>Versand</linking>"
        ],
        "paybackInfo": "Du erhältst <bold>1 PAYBACK</bold> °Punkt",
        "price": { "current": { "value": "3,65 €" } },
        "notIncreasedSince": {
          "text": "nicht erhöht seit 21.03.2024",
          "title": "dm-Dauerpreis"
        }
      },
      "netPriceInfo": {
        "infos": [
          "0,25 l (12,27 € je 1 l)",
          "exkl. MwSt. zzgl. <linking>Versand</linking>"
        ],
        "price": { "current": { "value": "3,07 €" } },
        "notIncreasedSince": {
          "text": "nicht erhöht seit 21.03.2024",
          "title": "dm-Dauerpreis"
        }
      },
      "breadcrumbs": [
        "Pflege & Parfum",
        "Körperpflege",
        "Bodylotion & Hautcreme"
      ],
      "description": [
        "Die NIVEA Creme in der 250ml Dose pflegt mit ihrer reichhaltigen Formel jeder Hauttyp unabhängig vom Alter und zu jeder Gelegenheit. Die cremige Textur mit dem beliebten Duft schützt und verwöhnt die Haut besonders unkompliziert – für eine schöne, geschmeidige Haut. Geeignet für die tägliche Anwendung, wo auch immer die Haut sanfte und reichhaltige Pflege benötigt. Dermatologisch bestätigt hautverträglich."
      ]
    }
  }
```

## GTIN-13 (EAN) Number

DM Product Scraper collects GTIN (EAN) numbers when provided with a Single Product URL and Product Category URLs.

## Is it legal to scrape DM-drogeriemarkt website?

This scraper was designed to comply with the directives specified in the [dm.de robots.txt](https://www.dm.de/robots.txt) file as of 25.03.2025.