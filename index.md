---
title: Privacy Policy
layout: default
---
# Privacy Policy for Colora

*Last updated: September 13, 2026.*

---

Colora is a coloring app for children aged 3 to 8, purchased and managed
by their parents. It is built to collect the strict minimum, and nothing,
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

When a **parent**, behind the parental control, types a coloring idea
(for example, "a dragon astronaut"):

- **the text of that idea is sent to Google's Gemini API** to draw the
  page. This is the only moment any human-written content leaves our
  systems, and it is sent alone: no name, no email, no advertising
  identifier.
- every idea passes automatic moderation before generation, and every
  image passes a safety check before display.
- refused ideas are never generated.

Nothing the child draws (their coloring) ever leaves the device.

## Your permission

The first time a parent asks for a page, the app explains that the idea
will be sent to Google's Gemini API and asks for explicit agreement. No
idea is sent before that agreement. A parent can withdraw it at any time
in Settings ("Send ideas to Gemini"); once withdrawn, no further idea is
sent, and the question is asked again before the next one.

Please do not type names or other personal details into an idea. If you
believe you did, write to the contact address below and we will delete it.

## Reporting a page

A parent can report a generated page from the Creator. A report sends us
the page reference, the idea it was drawn from, the age range setting,
and one reason chosen from a fixed list. It contains no free text. We use
reports only to review the page and improve moderation.

## Letter tracing

When a child traces letters, the app remembers, for each letter, how much
help it currently shows and whether the letter has been learned. This stays
**only on the device**: it is never sent to us or to anyone else, and
deleting the app deletes it. A parent can clear it at any time in Settings
("Start letters over").

## The subscription

Payments are handled by Apple's App Store or Google Play, and
orchestrated by **RevenueCat**, which receives only the anonymous
identifier and the subscription state, never any information about the
child. Every payment and every setting sits behind a parental control
(a hold-to-confirm control designed for adult deliberateness).

## Processors

| Service | Role | What it receives |
|---|---|---|
| Supabase | Hosting (database, storage, anonymous identity) | the anonymous identifier, the generated pages |
| Google (Gemini API) | Drawing generation | the text of the idea typed by the parent |
| RevenueCat / Apple / Google | Subscription | the anonymous identifier, the purchase state |

We share data only with the processors listed above, only for the purposes
described in this policy, and we require each of them to protect it with
at least the level of protection this policy describes.

## Children's privacy (COPPA)

Colora is directed at children, so we follow the Children's Online Privacy
Protection Act (COPPA) and comparable laws such as the GDPR. We do not
knowingly collect personal information from a child. The child-facing
screens accept no text and contain no links, and every place where
information can be entered or a purchase made sits behind the parental
control. The age range a parent chooses in Settings is stored only on the
device.

A parent can ask at any time to review or delete the data associated with
their device, or to stop further processing, by writing to the contact
address below.

## Retention and deletion

Generated pages are kept so they can be shown again in the app. Deleting
the app deletes the local identifier; on request to the contact address
below, we delete the data associated with an anonymous identifier.
Withdrawing consent for the Creator (see "Your permission") takes effect
immediately on the device. Reports are kept only as long as needed to
review them.

## Contact

Yenna Ltd, hamza.bekoury@hotmail.com
