# kirky.me

A minimal, static personal holding page. No dependencies, analytics, cookies, backend, or outgoing application requests. The hello button only changes text locally; it does not send a message.

## Hosting
Intended for GitHub Pages, published from the root of the `main` branch, with canonical domain `kirky.me`. DNS remains at Porkbun. Enable HTTPS enforcement once GitHub provisions the certificate.

## Editing
Edit `index.html`, run the browser checks, then commit and push to `main`.

## DNS cutover scope
Change only the apex website records and `www`; preserve MX, TXT, DNSSEC, subdomains, and certificate-validation records. Save the prior zone before changing DNS.
