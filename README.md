# Pripar AI website

One site, six regions. The region picker (top right) switches prices, currency and wording.
Region links: pripar.com/us  /eu  /au  /sg  /in  (UK is the default at pripar.com)

## Changing prices
Open index.html and search for `const REGIONS`. Each region has a `p:{...}` block of numbers. Edit the numbers, commit, done.

## Adding a new redirect (pripar.com/[name])

To add pripar.com/newproject pointing to an external URL:

1. Create a new folder in the repo root named `newproject`
2. Inside it, create `index.html` using the redirect template in /chatbot/index.html as a reference
3. Replace DESTINATION_URL with the actual URL
4. Commit and push
5. The route pripar.com/newproject will be live within 2–3 minutes

Use this for: new client demos, new products, new tools, campaign landing pages.
Current redirects: /chatbot /nestiq /tradedesk /marketing /wealthguard /doctrack /ch-ai /prodtrack /ijh /us /eu /au /sg /in
