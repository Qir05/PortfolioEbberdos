# Search implementation notes

Canonical identity: **Erique Berdos**. Alternate name: **Eriq Berdos**.
Canonical URL: https://qir05.github.io/PortfolioEbberdos/

## Implemented

- Visible name in the main heading, biography and FAQs.
- Consistent page title, description, canonical and social metadata.
- Person, WebSite and ProfilePage JSON-LD matching the visible identity and services.
- GitHub and LinkedIn identity links. Vaze is linked as a demo lab, not a personal identity profile.
- Crawlable service text, navigation, selected work and contact details.
- Responsive layout, skip link, keyboard focus states, reduced-motion support and portrait dimensions.
- Sitemap and optional llms.txt reference file.

## External follow-up

- Verify the exact GitHub Pages URL-prefix property in Google Search Console, submit sitemap.xml, and request indexing of the homepage. These require signed-in Search Console access and are not performed by editing this repository.
- Check indexing and name-query impressions over time; rankings and AI citations are not guaranteed.
- Keep professional profiles consistent with the portfolio's current services.
- Only the host-root /robots.txt is authoritative. This project's robots.txt is under /PortfolioEbberdos/ and does not set host-wide crawler policy.
- llms.txt is informational and is not required for Google's AI features or a guarantee of inclusion.

References: https://developers.google.com/search/docs/appearance/ai-features and https://developers.google.com/search/docs/appearance/structured-data/profile-page
