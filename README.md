# slam-post-assets

Static image host for the SLAM Sports AI / AI Signal LinkedIn posting routines.

Buffer's API does not accept file uploads — it fetches a **public, unauthenticated,
non-expiring HTTPS URL** at publish time. This repo exists purely so generated
post images (real company logos, data-driven charts/stat cards — never AI-generated
images) have a stable `raw.githubusercontent.com` URL for Buffer to fetch.

Images are organized as `YYYY-MM-DD/<lane>.png` (or `.svg`), one folder per day.
Nothing in here is meant to be browsed as a website — it's a bucket, not a page.
