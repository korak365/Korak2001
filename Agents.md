# Patent Application Tracker

The **Patent Application Tracker** scrapes recent patent applications from major patent databases (e.g., Google Patents, USPTO) to track innovation in specific industries.

## Features:
1. **Keyword Filtering**: Tracks only applications matching specific keywords (e.g., "Solid State Batteries").
2. **Collects Metadata**: Collects title, description, filing date, publication date, applicant, and link to the patent.
3. **Structured Data**: Outputs structured data for analysis.

## Inputs:
1. **Patent Database URLs**: List of URLs to scrape.
2. **Filter Keywords**: Keywords for filtering relevant patents.
3. **Max Applications**: Maximum patent entries to scrape per session.

## Outputs:
- `title`: The title of the patent.
- `description`: Brief details about the patent.
- `applicant`: Name of the company/individual applying for the patent.
- `filingDate`: Patent filing date.
- `publicationDate`: Date the patent was published.
- `keywordsMatched`: Keywords matched in the title/description.
- `patentUrl`: Link to the patent details.

## Use Cases:
1. **Track Innovation**: Keep up with advances in specific industries or technologies.
2. **Competitive Intelligence**: Monitor patents filed by competitors.
3. **Market Trends**: Identify trends in R&D for specific topics or technologies.

---
