# Mailchimp Build Guide

## Recommended Path

Use Mailchimp's regular email builder and assemble the newsletter with content blocks. This is easier to edit, safer for non-technical review, and less brittle than a code-your-own template.

## Campaign Setup

- Campaign name: `Innovate South 2026 Recap Launch`
- From name: `Innovate South` or `Opportunity Machine`
- Reply-to: choose the monitored event or OM inbox
- Audience: Innovate South / Opportunity Machine community list
- Tags or segment: event attendees, founders, mentors, investors, partners, civic partners

## Subject And Preview Text

Recommended subject:
`Inside Innovate South 2026: founders, capital, AI, and Acadiana's next chapter`

Recommended preview text:
`A full editorial recap of the sessions, founders, investors, and ecosystem moments that shaped Innovate South 2026.`

## Builder Sections

1. Logo image
   - Use `images/innovate-south-logo-top-color.png`
   - Link to the full recap URL with `utm_content=logo`

2. Hero image
   - Use `images/hero-applause.jpeg`
   - Add alt text: `Audience applauding at Innovate South 2026`

3. Lead text
   - Copy from `newsletter/launch-email.md`

4. Button
   - Text: `Read the full recap`
   - URL: use the hero CTA URL from `newsletter/utm-links.csv`

5. Five feature blocks
   - Opening Note
   - AI-Native Culture
   - Capital and the Goldilocks Round
   - Community as Infrastructure
   - Tech Tank 2026

6. Closing button
   - Text: `Read and share the full recap`
   - URL: use `final_cta` from `newsletter/utm-links.csv`

7. Footer
   - Keep Mailchimp's default unsubscribe and mailing-address footer.

## Testing

Before sending:

- Preview desktop and mobile.
- Send a test email.
- Click every CTA.
- Confirm the full recap loads from the public GitHub Pages URL.
- Confirm links with hashes open the intended section.
- Confirm no default placeholder text remains.
- Confirm required Mailchimp footer content is present.

Mailchimp's own guidance recommends previewing and testing because email clients render HTML differently, and Mailchimp requires the `*|UNSUB|*` merge tag in emails.

