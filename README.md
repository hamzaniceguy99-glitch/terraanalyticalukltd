# Terra Analytical — terra analytical uk ltd

Static marketing site (HTML / CSS / JS, no build step) hosted on GitHub Pages
at `terraanalyticalukltd.shop`.

> Generated from `C:\Users\souha\coaching-sites-factory` (content file `sites/terraanalyticalukltd.mjs`).
> To change the content, edit that file and run `node build.mjs terraanalyticalukltd` — editing the
> HTML here directly would be overwritten on the next build.

## Before you promote this site

| Priority | What | Where |
|---|---|---|
| 🔴 Blocking | Legal page: fill every `[BRACKET]` (legal name, address, state, payment provider). Have a lawyer review it if you can. | `legal.html` |
| 🟠 Important | `contact@terraanalyticalukltd.shop` doesn't exist yet: set up free email forwarding in Namecheap (*Domain List → Manage → Redirect Email*). | Namecheap |
| 🟠 Important | Contact form: replace `VOTRE_ID_FORMSPREE` with your Formspree id (until then it falls back to `mailto:`). | `contact.html` |
| 🟠 Important | Add a real introduction of the coach (name, background, photo). Never invent credentials. | `about.html` |
| 🟡 Later | Prices ($Quote / $Quote / $Declined) and plan contents should match what you actually sell. | `index.html` `#pricing` |
| 🟡 Later | Testimonials: only add real ones, with permission. Fake reviews are illegal (FTC). | — |

## Business description (Stripe, directories…)

```
Terra Analytical UK Ltd provides ground investigation and environmental consulting from Essex, working since 2022. We carry out site investigation, test drilling and boring, contamination assessment and the reporting that planning conditions require. The thing that decides whether an investigation was worth paying for is where the samples were analysed. A regulator or planning authority can reject data that did not come from a laboratory holding UKAS accreditation, and for soils the MCERTS scheme, which means a report built on cheap analysis fails and the whole investigation has to be repeated. Our samples go to an accredited laboratory and we tell you which, rather than implying accreditation we do not hold ourselves. We also trace buried services before a rig turns, because striking one is the real risk in this work. Site: terraanalyticalukltd.shop
```

## Structure

```
index.html            Home: hero, programs, method, pricing, approach, FAQ
programs.html         The four programs in detail
about.html            How we work, principles
contact.html          Contact form
legal.html            Business info, privacy policy, terms of service
404.html              Error page (absolute paths)
assets/css/style.css  Brand colors at the top, shared styles below
assets/js/main.js     Menu, theme, animations, form
```

## DNS (Namecheap → Advanced DNS)

Delete the parking records, then add:

| Type | Host | Value |
|---|---|---|
| A Record | `@` | `185.199.108.153` |
| A Record | `@` | `185.199.109.153` |
| A Record | `@` | `185.199.110.153` |
| A Record | `@` | `185.199.111.153` |
| CNAME Record | `www` | `hamzaniceguy99-glitch.github.io.` |
