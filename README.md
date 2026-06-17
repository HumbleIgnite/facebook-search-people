[Facebook Search People](https://apify.com/iron-crawler/facebook-search-people?fpr=data)

"# Facebook People Scraper (No Login Required)

## What does Facebook People Scraper (No Login Required) do?

This tool extracts public profile data from Facebook without requiring authentication or cookies. Built with a **No Login / Cookieless** architecture, it bypasses the traditional barriers of session management and account restrictions, allowing you to gather professional contact information and profile details at scale. Whether you're building lead lists or researching market segments, this scraper operates reliably without the risk of account bans or login complications.

**Key Features:**

- Scrape public Facebook profiles without authentication
- Extract contact details, occupation, and company information
- Export data to JSON, CSV, or Excel formats
- Filter results by location and professional criteria
- Track profile activity timestamps
- Process multiple search queries in batch mode
- No rate limiting from account-based restrictions

## Why scrape Facebook?

Sales professionals want to scrape contact details of potential leads across multiple platforms to build comprehensive prospect databases and accelerate pipeline generation. Facebook remains one of the largest repositories of professional and personal contact information, making it invaluable for outreach campaigns and market intelligence.

**Primary Use Cases:**

- **Lead Generation:** Build targeted prospect lists by searching for professionals in specific industries, locations, or job titles to fuel your sales pipeline with qualified contacts.
- **Market Research:** Analyze demographic patterns, professional distributions, and geographic concentrations to identify untapped market opportunities and competitive landscapes.
- **Recruitment Intelligence:** Source potential candidates by extracting profiles matching specific skill sets, experience levels, and location preferences for talent acquisition teams.

## How to scrape Facebook using this tool?

**Step 1:** Identify your search criteria. Determine the keywords, job titles, or industry terms that match your target audience (e.g., ""software engineer San Francisco"" or ""marketing director"").

**Step 2:** Configure the input parameters. Enter your search query in the `query` field. Plan your extraction volume accordingly: **1 search query ≈ 50-100 profiles** depending on result availability.

**Step 3:** Run the scraper and download your data. Once the extraction completes, export your results in JSON, CSV, or Excel format for immediate use in your CRM or outreach tools.

## What are the input parameters?

| Field | Type | Description |
| --- | --- | --- |
| `query` | String | Search term or keyword to find Facebook profiles (e.g., ""insights"", ""product manager"", ""real estate agent Boston""). Supports job titles, industries, locations, or any combination of search terms. |

## What data can you extract?

You can download the following data in JSON, CSV, or Excel formats:

```
{
  ""search_id"": ""sr_789456123"",
  ""full_name"": ""Michael Chen"",
  ""profile_url"": ""https://people.search.com/mchen"",
  ""location"": ""San Francisco, CA"",
  ""occupation"": ""Software Engineer"",
  ""company"": ""TechCorp Inc."",
  ""email_hash"": ""mchen_sf@example.com"",
  ""last_active"": ""2025-12-15T08:30:22Z""
}
```

**Available Fields:**

- `search_id`: Unique identifier for the search result
- `full_name`: Complete name of the profile owner
- `profile_url`: Direct link to the Facebook profile
- `location`: Geographic location (city and state/country)
- `occupation`: Current job title or professional role
- `company`: Current employer or organization
- `email_hash`: Contact email (when publicly available)
- `last_active`: Timestamp of most recent profile activity

---

This **people search scraper** and **profile data extractor** serves as a powerful **social media scraper** for teams focused on **lead generation**. Use this **people finder tool** to **export profiles** efficiently, enabling **professional profile scraping** at scale without the complexity of traditional authentication methods."