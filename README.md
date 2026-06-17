[Facebook Search People](https://apify.com/patient_discovery/facebook-search-people?fpr=data)

# **Facebook People Scraper - No Login Required**

## **What does this scraper do?**

This actor extracts Facebook profile search results based on a keyword query.

Enter a search term, run the actor, and receive structured profile data including names, profile URLs, verification status, and profile images.

No Facebook login, no cookies, no session handling required.

Cookieless architecture ensures stable, risk-free, and scalable automation.

## **Why scrape Facebook people search results?**

Facebook search allows discovery of professionals, entrepreneurs, and niche audiences based on keywords. This helps sales and marketing teams to:

- Build targeted prospect lists
- Discover decision-makers in specific industries
- Identify verified public profiles
- Analyze audience segments by role or niche
- Expand outreach campaigns with structured profile data
- Enrich CRM systems with public profile information
- Perform competitive intelligence research

Its cookieless design fits scalable data pipelines without needing Facebook accounts.

## **How much will scraping cost?**

The pricing for this actor is **$2.50 per 1,000 scraped results**. Refer to the pricing page.

Because this actor does not require login or session management, it reduces operational complexity and lowers the risk associated with account-based scraping. This predictable architecture keeps your data pipelines highly stable.

## **How to use the scraper**

Here is a **step-by-step guide**:

**Step 1: Open the actor:** Go to your Apify Console and open the scraper.

**Step 2: Enter your input parameters:** In the input field, enter your target search term in the `query` field (e.g., "marketing manager", "tech entrepreneur", "CEO").

**Step 3: Configure extraction depth:** Adjust optional parameters if available to control the number of results.

**Step 4: Start the run:** Click Start to begin scraping. The actor will fetch publicly available profile search results.

**Step 5: Export or integrate:** Once complete, download the dataset in JSON, CSV, or connect it via API to your CRM or marketing automation tools.

## **Input parameters**

Below are the configuration options you can use to control the scraper.

**Input example**

```
{
  "query": "digital marketing"
}
```

| Field | Type | Description |
| --- | --- | --- |
| query | String | Keyword used to search for Facebook profiles |

## **What data does this scraper extract?**

**Formats**: JSON, CSV, Excel

**Extracted Fields**:

- `type` - Record type identifier (search_profile)
- `profile_id` - Unique Facebook profile identifier
- `url` - Direct link to the Facebook profile
- `name` - Profile display name
- `is_verified` - Verification status
- `profile_picture.uri` - Profile image URL
- `profile_picture.width` - Image width
- `profile_picture.height` - Image height
- `profile_picture.scale` - Image scale factor

All data is returned as structured JSON with null-safe fields for reliable downstream processing.

## Sample Output

```
{
  "type": "search_profile",
  "profile_id": "pfbid0Xk9mPqR2vNwLtYhGfDcBaZsWxUvTsRqPoNmLkJiHgFeDcBa",
  "url": "https://www.facebook.com/people/Sarah-Thompson/pfbid0Xk9mPqR2vNwLtYhGfDcBaZsWxUvTsRqPoNmLkJiHgFeDcBa/",
  "name": "Sarah Thompson",
  "is_verified": true,
  "profile_picture": {
    "uri": "https://scontent-iad3-2.xx.fbcdn.net/v/t39.30808-1/392847561_742156389841521_583729516104253892_n.jpg",
    "width": 120,
    "height": 120,
    "scale": 2
  }
}
```

All data is delivered in structured JSON format suitable for lead generation, prospect database building, sales intelligence workflows, and audience research initiatives.

## **Key Features:**

- 📈 Extract Facebook profile search results by keyword
- 📊 Capture verification status and profile image metadata
- ⚡ Structured JSON output ready for analytics and automation
- 📈 Discover public profiles for outreach and prospecting
- 📊 Export-ready formats including JSON, CSV, and Excel
- ⚡ Scalable architecture for bulk people search extraction
- 🔒 Fully cookieless architecture with no login required

## **FAQs**

**Does this scraper require Facebook login?** No. It is fully cookieless and does not require login credentials.

**Can it scrape private profiles?** No. Only publicly accessible profile search data can be extracted.

**Can I run multiple search queries?** Yes. Execute separate runs for different keywords or integrate via API for bulk prospect discovery.

**Other Facebook scrapers that you may find useful:**

[Facebook Page Search Scraper](https://apify.com/patient_discovery/facebook-search-pages)

[Facebook Group Posts Scraper](https://apify.com/patient_discovery/facebook-group-posts)

[Facebook Search Events Scraper](https://apify.com/patient_discovery/facebook-search-events)

[Facebook Page Details Scraper](https://apify.com/patient_discovery/facebook-page-details)

[Facebook Marketplace Details Scraper](https://apify.com/patient_discovery/facebook-marketplace-details)

[Facebook Page Reviews Scraper](https://apify.com/patient_discovery/facebook-page-reviews)

[Facebook Page Posts Scraper](https://apify.com/patient_discovery/facebook-page-posts)

[Facebook Search People Scraper](https://apify.com/patient_discovery/facebook-search-people)