# Canva SaaS Template Adaptation Notes

Source: pasted Canva/Envato-style HTML template using the placeholder brand `Cloudlet`.

Verdict: useful as a polished special-issue layout or lead feature format, but not as the full recurring Startup Scoop digest unless it is expanded with repeatable modules.

## What The Template Is

This is a product-marketing email template:

- 600px white email container on a light gray background.
- Small utility row with date, view online, and forward.
- Large full-width hero image.
- Two-column intro: big headline plus short explanation.
- Center section title.
- Three image-plus-copy feature rows.
- Centered CTA button.
- Social icons.
- Large footer image.
- Compliance footer with placeholder browser, preferences, unsubscribe, address, and company number links.

## Best OM Use Cases

Use this template style for:

- A special Builder Program push.
- An Innovate South recap feature email.
- A founder story or OM Docs release.
- A sponsor/partner feature.
- A single major opportunity with supporting reasons to act.
- A themed Startup Scoop issue with one dominant story and 3 supporting modules.

Avoid using it as-is for:

- A long monthly digest with 8 to 10 unrelated sections.
- A jobs-heavy issue.
- A newsletter where the most important value is scanning many links quickly.

## OM Mapping

| Template Area | Original Role | OM Replacement |
| --- | --- | --- |
| Date / View Online / Forward row | Utility nav | Send date, `*|ARCHIVE|*`, `*|FORWARD|*` or Mailchimp forward link |
| Hero image | Product brand visual | Canva hero for Startup Scoop, Builder, Innovate South, or OM Docs |
| Big headline | Product positioning | Issue thesis or campaign headline |
| Intro copy | Product promise | Why this issue matters for founders now |
| Three feature rows | Product benefits | Three founder-value modules |
| CTA button | Subscription plan conversion | Register, apply, read recap, watch story, or take survey |
| Social icons | Brand follow links | OM LinkedIn, Facebook, YouTube, Instagram, website |
| Footer | Compliance | Mailchimp-required footer and OM mailing address |

## Strong Adaptation For May Startup Scoop

If recreating the May issue inside this layout, use it as a front-half feature email:

Headline:

Founder opportunities to know before summer starts

Intro:

May's Startup Scoop brings together Builder 1.0, statewide startup research, Startup Prize: Energy, OM Docs, alumni news, mentor support, and startup jobs.

Feature row 1:

- Title: Build your next 10 weeks with Builder 1.0
- Copy: Interest forms for the Summer 2026 Builder 1.0 cohort close Friday, May 29, 2026.
- CTA: Schedule Your Interest Call

Feature row 2:

- Title: Help shape Louisiana's startup data
- Copy: The 2026 Louisiana Startup Report is collecting founder input to help inform policy, funding, and resource decisions.
- CTA: Take the Survey

Feature row 3:

- Title: Find your next opportunity
- Copy: Startup Prize: Energy, OM Docs, FlyGuys news, mentor programming, and startup jobs are all moving this month.
- CTA: See This Month's Opportunities

Then add compact supporting blocks below for:

- Startup Prize: Energy
- OM Docs
- FlyGuys
- Resource recommendation
- Startup jobs

## Required Cleanup Before Mailchimp

Do not paste this HTML directly into Mailchimp without cleanup.

- Replace `Cloudlet` copy and imagery.
- Replace the fake date `March 30, 2030`.
- Replace `href="#"` CTA links.
- Replace `{{ view_in_browser }}`, `{{ update_preferences }}`, and `{{ unsubscribe }}` with the correct Mailchimp merge tags or builder footer blocks.
- Replace the placeholder address `123 Anywhere St.` and company number.
- Remove the trailing script block. Scripts do not belong in email templates.
- Do not rely on `<link rel="preload">`; many email clients will ignore it.
- Make sure all images are hosted in Mailchimp, Canva, or another stable public asset host.
- Add useful alt text to every image.
- Confirm mobile stacking for all two-column rows.

## Recommended Mailchimp Merge Tags

Use Mailchimp's built-in builder footer where possible. If editing code, use:

- View in browser: `*|ARCHIVE|*`
- Update preferences: `*|UPDATE_PROFILE|*`
- Unsubscribe: `*|UNSUB|*`
- Audience address: `*|HTML:LIST_ADDRESS_HTML|*`

## Design Notes

Good to keep:

- Large hero image.
- Big editorial headline.
- Alternating image/text feature rows.
- Strong single CTA.
- Clean white container.

Adjust for OM:

- Add OM or Innovate South logo in the top area.
- Use OM blue/green or Innovate South colors instead of all-black CTA styling when appropriate.
- Keep live text for deadlines, dates, eligibility, and links.
- Shorten modules so the issue stays scannable.
- Preserve the existing OM social/footer area unless a full redesign is intentional.

## Decision

Use this as a template option for special editions and lead-feature newsletters. Keep the original OM Startup Scoop format for regular monthly digest issues unless the issue has one clear central story.

