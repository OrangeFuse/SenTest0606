# SENshine multi-page static prototype

This is a static multi-page version of the SENshine Embrace prototype.

## Included routes

- `/`
- `/schools/`
- `/teachers/`
- `/sencos/`
- `/school-leaders/`
- `/mats/`
- `/councils/`
- `/how-it-works/`
- `/evidence/`
- `/book-a-conversation/`
- `/vision/`
- `/team/`
- `/values/`
- `/contact/`
- `/news-and-insights/`
- `/news-and-insights/how-can-schools-consistently-deliver-whole-school-inclusion/`
- `/news-and-insights/the-word-that-could-change-everything-if-we-let-it/`

Legacy redirects are included for `/blogs/`, `/multi-academy-trusts-mats/` and the original article routes.

## Protections retained

- `robots.txt` blocks all crawlers.
- Every HTML page includes `noindex,nofollow,noarchive`.
- `_headers` adds `X-Robots-Tag: noindex, nofollow, noarchive` and basic security headers.

## Forms and lead generation

- Primary CTA: Book a conversation via the existing HubSpot form.
- Secondary CTAs: School, MAT and Council ScoreApp quizzes.
- No external tracking scripts are embedded. External forms open as links.

## Known content note

The article route for `The Word That Could Change Everything. If We Let It.` is retained, but the full article body needs migrating from SENshine’s CMS. The article title is visible on the current SENshine blog index, but the body could not be fetched during this build.

## Video embed
The existing SENshine YouTube video is embedded on the homepage, `/schools/`, and `/how-it-works/` using the privacy-enhanced YouTube domain. Caption display is requested with `cc_load_policy=1`, `cc_lang_pref=en`, and `hl=en-GB`, subject to YouTube availability.
