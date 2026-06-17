[Facebook Search People](https://apify.com/data-slayer/facebook-search-people?fpr=data)

Extract Facebook profile data at scale without authentication or cookies. This scraper enables sales teams to build comprehensive prospect databases by searching for people on Facebook and collecting publicly available profile information — no login credentials required.

## 📺 Video Tutorial: How it Works

[Video](https://www.youtube.com/embed/NOnfFO9N248?enablejsapi=1&rel=0)

---

## Key Features

🔒 **Cookieless / No Login Required** - Access public Facebook profile data without authentication, eliminating account suspension risks and credential management overhead.

📈 **Scalable Architecture** - Process multiple search queries simultaneously to build extensive prospect databases across different industries, locations, and demographics.

✅ **Rich Profile Data** - Extract profile IDs, names, URLs, verification status, and high-resolution profile pictures with complete metadata.

⚡ **Fast & Reliable** - Optimized scraping engine delivers consistent results with minimal latency, perfect for time-sensitive lead generation campaigns.

📊 **Export-Ready Formats** - Download data in JSON, CSV, or Excel formats for immediate integration with CRM systems, marketing automation tools, and analytics platforms.

## Use Cases

**Sales Professionals**: Build targeted prospect lists by searching for decision-makers in specific industries or roles. Export contact details directly into your CRM to accelerate pipeline generation and reduce manual research time.

**Marketing Analysts**: Gather demographic and profile data to understand audience segments, analyze competitor followings, and identify influencers or brand advocates for partnership opportunities.

**Business Development Teams**: Discover potential partners, clients, or collaborators by searching relevant keywords and industries. Create comprehensive databases of prospects with verified profile information for outreach campaigns.

## Inputs

| Field | Type | Description |
| --- | --- | --- |
| query | String | Search term or keyword to find Facebook profiles (e.g., "marketing manager", "tech entrepreneur") |

## Outputs

**Available Formats**: JSON, CSV, Excel

**Extracted Fields**:

- `type` - Record type identifier (search_profile)
- `profile_id` - Unique Facebook profile identifier
- `url` - Direct link to the Facebook profile
- `name` - Display name of the profile
- `is_verified` - Verification status (true/false)
- `profile_picture` - Object containing profile image URI, dimensions (width/height), and scale factor

## How to Use

**Step 1**: Enter your search term in the `query` field (e.g., "digital marketing", "software engineer", "CEO").

**Step 2**: Configure any additional parameters based on your scraping needs.

**Step 3**: Run the scraper and download results in your preferred format (JSON, CSV, or Excel) for immediate use in your sales or marketing workflows.

## Sample Output

```
{
  "type": "search_profile",
  "profile_id": "pfbid0Xk9mPqR2vNwLtYhGfDcBaZsWxUvTsRqPoNmLkJiHgFeDcBa",
  "url": "https://www.facebook.com/people/Sarah-Thompson/pfbid0Xk9mPqR2vNwLtYhGfDcBaZsWxUvTsRqPoNmLkJiHgFeDcBa/",
  "name": "Sarah Thompson",
  "is_verified": true,
  "profile_picture": {
    "uri": "https://scontent-iad3-2.xx.fbcdn.net/v/t39.30808-1/profile_pic.jpg",
    "width": 120,
    "height": 120,
    "scale": 2
  }
}
```

## 🧩 Other Facebook Actors by Data Slayer

| Actor | What it does | Link |
| --- | --- | --- |
| Facebook Page Search Scraper | Search and discover Facebook pages by keyword | [Try it](https://apify.com/data-slayer/facebook-search-pages) |
| Facebook Page Details Scraper | Get full page profiles — followers, contact info, ratings | [Try it](https://apify.com/data-slayer/facebook-page-details) |
| Facebook Posts Scraper | Extract posts from any Facebook page | [Try it](https://apify.com/data-slayer/facebook-page-posts) |
| Facebook Group Posts Scraper | Extract posts from any public Facebook group | [Try it](https://apify.com/data-slayer/facebook-group-posts) |
| Facebook Reviews Scraper | Extract customer reviews from any Facebook page | [Try it](https://apify.com/data-slayer/facebook-page-reviews) |
| Facebook Events Scraper | Discover Facebook events by keyword search | [Try it](https://apify.com/data-slayer/facebook-search-events) |
| Facebook Marketplace Listing Scraper | Extract detailed listing data from Facebook Marketplace | [Try it](https://apify.com/data-slayer/facebook-marketplace-details) |

## 💬 Feedback and Support

We actively maintain this actor and ship improvements based on user feedback. If you run into any issues or have ideas for new features:

- Create an issue on the Actor's **Issues tab** in Apify Console
- Rate the actor if it helped you — it helps others find it too
We typically respond within 24 hours.