# TikTok source collection for a competitor brief

A small, reusable workflow for collecting messages, dates and source links before writing a competitor or product brief. Built by Diamade for its own paid [TikTok research service on Apify](https://apify.com/diamade/tiktok-ads-research-service).

## Try it without code

1. Open the [competitor research Task](https://apify.com/diamade/tiktok-ads-research-service/examples/research-specific-tiktok-competitor), or the [product/topic Task](https://apify.com/diamade/tiktok-ads-research-service/examples/research-tiktok-ads-for-product-topic).
2. Replace the sample query with your competitor or phrase. Select the research market and applicable period.
3. Start with Preview, which samples up to 12 activities without result/report event fees; Apify account terms apply.
4. Read the run summary and review the delivered rows. A successful process can still have partial source coverage. Do not treat a blocked source as an empty market.
5. Export the Dataset as CSV, Excel or JSON. Use `research-sheet-template.csv` for your manual selection and notes. The template is a review sheet, not a promise of exact Dataset field names.

For larger research, read [live Pricing](https://apify.com/diamade/tiktok-ads-research-service/pricing) and set result and spending limits before starting. No API key is needed to read this repository; running research requires your own Apify account. Never put credentials in a public issue, sheet or URL.

## What belongs in the sheet

Keep the source class, original message, publication or source-observation dates, original URL and your reason for including the example. Missing fields stay blank. Separate observations from your interpretation. A creator may have multiple distinct relevant posts.

The service supports 32 European Ads Library markets plus US and Ukraine routes. Public US/Ukraine activity is separate from paid-ad evidence; a search-market route does not establish creator location, brand ownership or sponsorship. Public matches need manual relevance review. Original Unicode text, including Cyrillic, can be retained in export.

## Agent-assisted use

The included `skills/apify-tiktok-research-brief/SKILL.md` describes task selection, budget checks, source outcomes and evidence delivery. It does not supply credentials, install an integration or authorize paid runs. Use it with your existing Apify tooling; if execution tools are unavailable, follow the browser Task path above.

## Validation and limits

On October7, 2026 the workflow was replayed against an existing September30 Ukraine topic export: ten distinct source links, dates and public-activity classifications were checked. That historical run was partial. It validates retained-output review and export, not fresh source acquisition, all-market availability or customer results. No customer data or owner-run costs are included in this repository.

This workflow does not estimate ad spend, rank winning ads, infer sales from engagement, guarantee a complete archive, or perform monitoring. No affiliation with or endorsement by TikTok is claimed.

## Feedback

For a source-collection workflow, describe the research question, desired market and missing output. Remove credentials and private customer information before sharing examples. Diamade owns the linked service; there are no affiliate links.
