# San Francisco Bay Queer Contra Dance

Website and email for San Francisco Bay Queer Contra Dance, featuring Circle Left, Improper English, and Queer Contra Camp.


## Infrastructure for queercontradance.org

### Domain Registration - Cloudflare ($10/year)
Domain registration is managed through Cloudflare. Domain registration WHOIS record points to SFBQCD as the organization, with Margaret's address. The minimal annual domain renewal fee is set to auto-payment by Ash.

### Domain DNS - Cloudflare (free)
Domain DNS is managed through Cloudflare's free DNS service. The DNS records are configured to point to GitHub Pages for web hosting and Google Workspace for email hosting.

### Email Hosting - Google Workspace (free)
Email is hosted through Google Workspace's free nonprofit plan. To add users or handle administrative tasks, log into the [Google Admin Console](https://admin.google.com/) with the email address **sfbqcd@queercontradance.org**.

### Web Hosting - GitHub Pages (free)
The website is hosted on GitHub Pages, which provides free hosting for static sites. To deploy the website, push or merge changes to the `main` branch of the repository.

### GitHub Organization (free)
The repository is part of the [queer-contra](https://github.com/queer-contra) GitHub organization. We have a free GitHub Team subscription through [GitHub for Nonprofits](https://support.github.com/contact/nonprofit).

## Access

For access to the repository, DNS, or other administrative resources, email **info@queercontradance.org**.

---

## Website Local Development

To run the website locally on `localhost:8000`:

**Using Python 3:**
```bash
python3 -m http.server 8000
```

**Using Python 2:**
```bash
python -m SimpleHTTPServer 8000
```

Then open your browser and navigate to `http://localhost:8000`

The site will be served from the current directory with `index.html` as the homepage.
