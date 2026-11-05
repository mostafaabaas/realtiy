# Realtiy — realtiy.com (static landing site)

The real-estate content & UGC desk of **influUGC**. Built Nov 6, 2026. **Files only — not deployed.**

## ⚠️ Content model + design direction (owner orders, Nov 5–6, 2026)

- **Content-first (owner update, Nov 6, 00:24):** network sites must NOT be pure
  company brochures. They lead with useful **content** — tips, guides and
  information that search engines and AI answers surface and that brings
  traffic — with influUGC's services and real work woven inside the content,
  and the central CTAs doing the conversion. This site applies the model: the
  homepage carries a full **"Guides for developers & brokers"** section
  (3 substantive starter guides, below) ahead of the services list, and each
  guide closes with a soft woven-in influUGC line + the standard central CTA.
- **Identity (owner order, Nov 5, 23:57):** ALL network satellite sites use the
  main influUGC identity — black background `#000`, neon lime accent `#C8FF00`,
  dark panels, bold heavy typography, the www.influugc.com feel.
- Brand lockup: `Realtiy.` wordmark with the subline "Content & UGC for real
  estate by influUGC" (Arabic: «تسويق المحتوى وUGC للعقارات من influUGC»).
- Only real company data: est. 2020, Arab League St Agouza (Giza 12651),
  Egypt + Saudi/Gulf, real client names (Riyadh Season, Saudi Tourism
  Authority, flynas, Saudia, realme, Domino's, TikTok Live, Zanussi).
  No prices, no invented figures or statistics, no testimonials,
  no stock imagery (CSS/text only).

## Domain history — why this site exists (Nov 6, 2026)

- `realtiy.com` sat in the NEW Namecheap account (`influugc`) at the **$200
  tier**, and had an **outbound sale queue mid-flight** (69 queued prospect
  emails at $200; 2 already sent).
- **Owner decision Nov 6, 2026 (00:41, «ابدا تنفيذهم كلهم»):** convert
  realtiy.com from a sale asset into a network site — the third vertical
  satellite (real-estate UGC). The outbound sale queue for this domain is
  HALTED by that decision; a serious buyer reply to the 2 already-sent emails
  still goes to the owner.
- Delisting follows from the conversion: the domain is a keeper now, not sale
  stock (any live sale listings are pulled in the registrar-session batches).

## Pages built (3 HTML pages, 2 languages)

| File | What |
|---|---|
| `index.html` | Arabic-first landing (RTL): hero, client proof strip, **Guides for developers & brokers** (3 starter guides, anchor-linked), 5 services (UGC walkthroughs & creator tours, off-plan launch campaign content, developer brand content, broker/agent personal-brand content, launch-event coverage), 4-step how-it-works (consultation & brief → creators & tour plan → filming & delivery → run & refill), why influUGC (with the in-body editorial link to influugc.com), 6-question answer-first FAQ, contact/CTA band, network footer. |
| `en.html` | Full English mirror (LTR), same structure, guides and FAQ. |
| `404.html` | Branded not-found page (English). |

Plus: `styles.css`, `favicon.svg` (black + lime R mark), `sitemap.xml`
(hreflang-annotated), `robots.txt`, `llms.txt`, `render.yaml`.

### The 3 starter guides (on-page sections, both languages)

1. `#guide-walkthrough` — **How a unit walkthrough should be shot to sell the
   unit**: start at the front door, walk in the order of a buyer's day, honest
   scale, the practical details buyers ask about, natural light and a real
   voice; the unit first and the compound's context last — beauty shots earn
   admiration, an honest tour books visits.
2. `#guide-offplan` — **UGC for off-plan launches — building trust before
   delivery**: the developer's delivered record first, dated construction-
   progress series, the show unit filmed honestly, fear-question videos, and
   only the published payment plan (never return promises); renders always
   labelled as renders.
3. `#guide-brief` — **What to put in a creator brief for a real-estate tour**:
   location facts as published, unit facts, payment-plan facts split into
   may-say / may-not-say, disclosure rules (paid partnership, labelled
   renders, access and drone permits on production), must-show moments and
   format, deliverables + usage agreed in writing.

Each guide ends with a soft woven-in line (Realtiy runs exactly this for
developers and brokers) + the standard book/WhatsApp CTAs with
`utm_source=realtiy`.

## SEO / GEO

- Canonical base `https://realtiy.com/` (the real domain; if this site is
  first deployed to an `onrender.com` URL before the domain attaches, switch
  all canonical/OG/sitemap/robots/llms bases in one pass, same as the
  ugccompany rule in `../DEPLOY.md` §2).
- Title/meta target "UGC & content marketing for real estate" + Egypt /
  Saudi Arabia in both languages; OpenGraph + Twitter cards; hreflang ar/en
  both ways (Arabic is the root page, English at `/en.html`).
- JSON-LD: `Organization` (with `parentOrganization: influUGC`, postal address,
  areaServed, the four real social profiles), `WebSite` (Arabic page), and
  `FAQPage` matching each page's visible FAQ word for word.

## CTAs (both carry the satellite UTM set)

- Booking → `https://www.influugc.com/book?utm_source=realtiy&utm_medium=satellite&utm_campaign=network`
- WhatsApp (client line) → `https://wa.me/201029979797?utm_source=realtiy&utm_medium=satellite&utm_campaign=network`
- Footer legal line: "Part of the influUGC network" linking to the hub.

## What remains (not done here)

1. **Render service** — create the free Static Site from the PUBLIC repo
   (public from birth by the activation design) using the `render.yaml`
   blueprint (name `realtiy`, publish path `.`); expected interim URL
   https://realtiy.onrender.com. No Render API key is available to the
   automation — dashboard step (runs in the activation browser batch).
2. **Custom domain** — add `realtiy.com` (+ www) to the Render service and
   record the exact DNS values Render shows.
3. **DNS batch** — set those records in the NEW Namecheap account (`influugc`)
   session batch, together with the network's other attaches and the shield
   redirects. No MX changes — mail stays on influugc.com.
4. **Delist** — confirm no live sale listings remain for realtiy.com
   (Afternic/Namecheap) in the registrar-session batches; the domain is a
   keeper now.
5. After go-live: dedicated Google Search Console property + submit
   `sitemap.xml`; verify both pages return 200, the guides render, and the FAQ
   matches the JSON-LD.

## Deploy status (Nov 6, 2026)

- **Repo**: https://github.com/mostafaabaas/realtiy (PUBLIC from birth,
  branch `main`) — source pushed Nov 6, 2026.
- **Hosting**: PENDING-DASHBOARD — the Render Static Site service has **not**
  been created yet (see "What remains" item 1 above).
- **Domain attach**: separate later batch (see "What remains" items 2–3).
