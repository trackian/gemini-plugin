# Trackian extension for Gemini CLI

Ask Gemini why sales moved, which ads waste money and what to fix next, answered from your live [Trackian](https://trackian.com) data. Trackian brings GA4, Google Ads, Meta Ads, TikTok Ads, Search Console and your Shopify, WooCommerce or Magento store into one place, and its Sentinel engine checks every project for anomalies each night.

## What this extension does

- **Answers questions in plain business language:** "why did sales dip on Tuesday?", "which campaigns should I cut?", "are we on track this month?" Every number comes from a Trackian tool call.
- **Makes changes only after you confirm.** Every change shows a preview first and waits for your yes. Changes to live ad campaigns and stores are off for a new connection; an account owner can switch them on in Trackian under Settings > AI Agent Setup.

## Installation

```bash
gemini extensions install https://github.com/trackian/gemini-plugin
```

## Sign in

The first time Gemini uses a Trackian tool it opens a Trackian page in your browser: sign in, or create an account, choose the company and click **Allow**. There is no API key to copy. Platforms (Google Ads, Meta, GA4 and so on) are connected in the Trackian app at [trackian.app](https://trackian.app) under Setup > Platforms.

New here? Ask Gemini to run the `getting-started` command from Trackian.

## Read-only access

Grant only the read scope and Gemini can never change anything in Trackian or in your connected accounts.

## Links

- [trackian.com](https://trackian.com)
- [Privacy policy](https://trackian.com/privacy-center/privacy-policy/)

## License

MIT
