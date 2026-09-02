---
title: Privacy Policy
layout: default
---
# Privacy Policy — Colora

*Last updated: September 2, 2026.*

---

Colora is a coloring app for children aged 3 to 8, purchased and managed
by their parents. It is built to collect the strict minimum — and nothing,
absolutely nothing, about the child.

## What we do not collect

- **No personal data about the child.** No name, no age, no photo, no
  account. The child-facing interface contains no text, no input field,
  and no external link.
- **No advertising.** The app embeds no advertising SDK.
- **No third-party analytics.** No analytics service that collects data
  is integrated.
- **No sign-up.** There is no account, no email address, no password.

## The anonymous identity

On first launch, the app obtains an **anonymous identifier** from our
hosting provider (Supabase). This identifier is a random number: it
contains no personal information and cannot be traced back to any. It is
used only to:

- recover pages still being generated after a restart;
- apply the fair-use limit on generation;
- attach the subscription to the same device.

## Coloring ideas (the "Creator" feature)

When a **parent** — behind the parental control — types a coloring idea
(for example, "a dragon astronaut"):

- **the text of that idea is sent to Google's Gemini API** to draw the
  page. This is the only moment any human-written content leaves our
  systems, and it is sent alone: no name, no email, no advertising
  identifier.
- every idea passes automatic moderation before generation, and every
  image passes a safety check before display.
- refused ideas are never generated.

Nothing the child draws (their coloring) ever leaves the device.

## The subscription

Payments are handled by Apple's App Store or Google Play, and
orchestrated by **RevenueCat**, which receives only the anonymous
identifier and the subscription state — never any information about the
child. Every payment and every setting sits behind a parental control
(a hold-to-confirm control designed for adult deliberateness).

## Processors

| Service | Role | What it receives |
|---|---|---|
| Supabase | Hosting (database, storage, anonymous identity) | the anonymous identifier, the generated pages |
| Google (Gemini API) | Drawing generation | the text of the idea typed by the parent |
| RevenueCat / Apple / Google | Subscription | the anonymous identifier, the purchase state |

## Retention and deletion

Generated pages are kept so they can be shown again in the app. Deleting
the app deletes the local identifier; on request to the contact address
below, we delete the data associated with an anonymous identifier.

## Contact

Yenna Ltd — hamza.bekoury@ensem.ac.ma
