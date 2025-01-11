# Amazon Search Scraper: Unlocking Data with Ease

Scraping Amazon search results has never been easier! With the Amazon Search Scraper API, you can extract search result data by simply passing your desired query.

## Why Use the Amazon Search Scraper API?

Gone are the days of struggling with proxies and CAPTCHAs. The Amazon Search Scraper API provides a seamless way to gather data from Amazon search results, offering a wide array of details about products.

Stop wasting time on proxies and CAPTCHAs! ScraperAPI's simple API handles millions of web scraping requests, so you can focus on the data. Get structured data from Amazon, Google, Walmart, and more. 👉 [Start your free trial today!](https://bit.ly/Scraperapi)

---

## How to Use the API

To utilize the Amazon Search Scraper, send a GET request to the following endpoint:

```
https://api.scrapingdog.com/amazon/search
```

### Required Parameters

Make sure to include these essential parameters in your request:

- **`query`**: Specify your search term (e.g., "spoon," "headphones").
- **`page`**: Choose the results page (default is page 1).
- **`api_key`**: Use your Scrapingdog API key for authentication.

---

## API Example Request

Here’s an example of a typical GET request to the API:

```http
GET https://api.scrapingdog.com/amazon/search?query=spoon&page=1&api_key=YOUR_API_KEY
```

---

## API Response Format

When your request is successful, you’ll receive a JSON response containing the following information:

```json
[
    {
        "type": "search_product",
        "position": 1,
        "title": "Amazon Basics Stainless Steel Dinner Spoons with Round Edge, Pack of 12, Silver",
        "image": "https://m.media-amazon.com/images/I/61Y-85Ei4-L._AC_UL320_.jpg",
        "has_prime": true,
        "is_best_seller": true,
        "is_amazon_choice": false,
        "stars": 4,
        "total_reviews": "7,647",
        "url": "https://www.amazon.com/gp/bestsellers/kitchen/367314011/ref=sr_bs_0_367314011_1",
        "price_string": "$12",
        "price_symbol": "$",
        "price": 12
    },
    {
        "type": "search_product",
        "position": 2,
        "title": "Hampton Forge Ginger 4 Pc Dinner Spoons, 0.35 LB, Metallic",
        "image": "https://m.media-amazon.com/images/I/710R3I758GL._AC_UL320_.jpg",
        "has_prime": true,
        "is_best_seller": false,
        "is_amazon_choice": false,
        "stars": 4,
        "total_reviews": "340",
        "url": "https://www.amazon.com/Hampton-Forge-Ginger-Dinner-Metallic/dp/B09RQ1X9W9",
        "price_string": "$2",
        "price_symbol": "$",
        "price": 2
    }
]
```

### Key Attributes in the Response:

- **`title`**: Product name.
- **`image`**: URL of the product image.
- **`stars`**: Average customer rating (out of 5 stars).
- **`total_reviews`**: Total number of reviews for the product.
- **`price`**: The product's price.

---

## What Makes This API Stand Out?

1. **Efficient Data Retrieval**: Extract structured data in seconds.
2. **Scalable Performance**: Handle millions of requests with ease.
3. **Comprehensive Product Details**: Get ratings, pricing, and more.

---

### Start Your Journey with ScraperAPI

Stop wasting time on proxies and CAPTCHAs! ScraperAPI's simple API handles millions of web scraping requests, so you can focus on the data. Get structured data from Amazon, Google, Walmart, and more. 👉 [Start your free trial today!](https://bit.ly/Scraperapi)

---

## Related Links and Resources

- [Amazon Search Documentation](https://bit.ly/Scraperapi)
- [Scrapingdog API Key Setup Guide](https://bit.ly/Scraperapi)

**Note**: All other external links have been removed to ensure focused content and improved user experience.

---
**Disclaimer**: Use of the Amazon Search Scraper must comply with Amazon’s terms of service and local regulations. Always handle scraped data ethically and responsibly.
