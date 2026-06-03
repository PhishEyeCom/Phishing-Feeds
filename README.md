# PhishEye Phishing-Feeds

Open, automatically-updated feeds of phishing URLs, published by [PhishEye](https://phisheye.com) - a digital risk protection platform for phishing detection, lookalike-domain monitoring, and coordinated takedowns.

## What's in here

- `feeds/urlscan-phishing-30d.txt` - phishing URLs observed in the last 30 days, one per line. Refreshed **daily** by an automated GitHub Action.
- `feeds/LAST_UPDATED.txt` - timestamp (UTC) of the most recent refresh.

No API key needed - the latest list is always committed here in plain text.

## How it updates

A scheduled [GitHub Action](.github/workflows/update-feed.yml) runs every day at 06:00 UTC, pulls the latest feed, and commits any changes automatically. You can also run it on demand from the **Actions** tab ("Run workflow").

## Free tools from PhishEye

PhishEye publishes a set of **free phishing and email-security tools** - no signup required. Try them at **[phisheye.com/tools](https://phisheye.com/tools)**:

- **Phishing quiz** - test how well you spot phishing
- **URL red-flag checker** - flag suspicious links before you click
- **Email header analyzer** - inspect message headers for spoofing
- **DMARC checker & generator** - validate and build DMARC records
- **SPF checker & generator** - validate and build SPF records
- **DKIM checker & generator** - validate and build DKIM records

## About PhishEye

[PhishEye](https://phisheye.com) helps security, fraud, and brand-protection teams find and shut down phishing sites, lookalike domains, impersonation, and brand abuse across web, ads, social, and search.

- Website: https://phisheye.com
- Free tools: https://phisheye.com/tools
- Blog & research: https://phisheye.com/resources/blog

## Use & attribution

These feeds are provided for defensive and research use. The listed URLs are live phishing links - handle them only in a safe environment. If you use this data, a link back to [phisheye.com](https://phisheye.com) is appreciated.
