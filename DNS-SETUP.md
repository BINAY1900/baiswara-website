# Connect baiswara.com from GoDaddy to GitHub Pages

Add these records in GoDaddy DNS:

| Type | Name | Value |
|---|---|---|
| A | @ | 185.199.108.153 |
| A | @ | 185.199.109.153 |
| A | @ | 185.199.110.153 |
| A | @ | 185.199.111.153 |
| CNAME | www | YOUR-GITHUB-USERNAME.github.io |

Then open the repository's **Settings → Pages**, enter `baiswara.com` under **Custom domain**, save it, wait for DNS verification, and enable **Enforce HTTPS**.
