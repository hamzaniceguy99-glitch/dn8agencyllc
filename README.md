# DN8 Agency — dn8agency llc

Static marketing site (HTML / CSS / JS, no build step) hosted on GitHub Pages
at `dn8agencyllc.shop`.

> Generated from `C:\Users\souha\coaching-sites-factory` (content file `sites/dn8agencyllc.mjs`).
> To change the content, edit that file and run `node build.mjs dn8agencyllc` — editing the
> HTML here directly would be overwritten on the next build.

## Before you promote this site

| Priority | What | Where |
|---|---|---|
| 🔴 Blocking | Legal page: fill every `[BRACKET]` (legal name, address, state, payment provider). Have a lawyer review it if you can. | `legal.html` |
| 🟠 Important | `contact@dn8agencyllc.shop` doesn't exist yet: set up free email forwarding in Namecheap (*Domain List → Manage → Redirect Email*). | Namecheap |
| 🟠 Important | Contact form: replace `VOTRE_ID_FORMSPREE` with your Formspree id (until then it falls back to `mailto:`). | `contact.html` |
| 🟠 Important | Add a real introduction of the coach (name, background, photo). Never invent credentials. | `about.html` |
| 🟡 Later | Prices ($Quote / $Quote / $Declined) and plan contents should match what you actually sell. | `index.html` `#pricing` |
| 🟡 Later | Testimonials: only add real ones, with permission. Fake reviews are illegal (FTC). | — |

## Business description (Stripe, directories…)

```
DN8 Agency LLC is a Florida digital marketing agency, formed in 2019. We do content and social, paid media, email and SMS, and reporting that shows what actually happened. What shapes how we work is a set of rules most agencies still treat as optional. The FTC's rule on consumer reviews and testimonials prohibits fake reviews, buying positive or negative ones, undisclosed insider reviews and suppressing unfavourable ones, and it carries civil penalties. Its endorsement guides require any material connection between a brand and an endorser to be disclosed clearly, and liability for a missing disclosure sits with the advertiser, not just the creator. We also will not send marketing texts without prior express written consent, because the statutory damages there are per message. So we will not buy followers, write reviews, or bury the bad ones. Site: dn8agencyllc.shop
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
