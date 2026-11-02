# Volet 3 — Workflow Blueprint

These are proposed workflow specifications, not workflows activated in HubSpot. The currently connected HubSpot tools expose marketing-email creation and editing, but no workflow create/edit/enroll action. Configure these manually in HubSpot only if the portal subscription and permissions expose Workflows.

## B2C workflows

### B2C-01 — New Traveler Welcome
- Enrollment: new B2C contact; valid marketing consent for the relevant subscription; not suppressed.
- Action: send Welcome to Your Travel Journey (automated email).
- Delay: 3 days.
- Branch: profile completed / clicked relevant account link.
- Follow-up: helpful platform guide; otherwise stop or send one reminder.
- Exit: unsubscribe, hard bounce, or customer-service/legal suppression.

### B2C-02 — Seasonal Travel Inspiration
- Enrollment: contact matches an approved country/language/persona segment and is eligible for marketing.
- Action: send The Perfect Seasonal Escape (batch campaign or scheduled automation, depending on campaign design).
- Branch: clicked destination link / no click.
- Follow-up: relevant destination content only where verified destination data exists.
- Frequency cap: avoid overlapping seasonal sends.

### B2C-03 — Inactive Traveler Reactivation
- Enrollment: no qualifying interaction for 90 days (only if reliable activity data exists).
- Exclusions: recent booking if a verified booking field/integration exists; unsubscribed and suppressed contacts.
- Action: send We Miss Your Travel Spirit.
- Delay: 7 days.
- Branch: clicked / no interaction.
- Follow-up: at most one final reminder, then unenroll.

### B2C post-stay follow-up
- Trigger: verified completed-stay event from a connected booking source.
- Actions: send Your Travel Memories, request review, then optionally suggest a future trip.
- Blocker: no completed-stay property/event was verified in the current CRM audit. Do not activate until a real source is connected.

## B2B workflows

### B2B-01 — New Partner Onboarding
- Enrollment: contact is B2B and relationship status indicates new partner/onboarding stage.
- Action: send Welcome to Your Partner Journey.
- Delay: 3 days.
- Branch: required property/listing information complete / incomplete.
- Follow-up: send listing setup guidance if incomplete.
- Exit: partner becomes inactive, unsubscribes, or is handled by a human owner.

### B2B-02 — Property Presentation Improvement
- Enrollment: partner segment + identified listing/content need, or incomplete property information.
- Action: send Make Your Property Stand Out.
- Delay: 7 days.
- Branch: click or reply / no engagement.
- Follow-up: create a task for the assigned commercial owner when appropriate.

### B2B-03 — Seasonal Partner Activation
- Enrollment: eligible partner segment, relevant destination/season, approved campaign window.
- Action: send Get Ready for the Next Travel Season.
- Branch: click / no click.
- Follow-up: create sales task for qualified engagement; avoid interpreting opens alone as intent.

### B2B-04 — Inactive Partner Reactivation
- Enrollment: no qualifying partner activity for agreed period, with reliable activity data.
- Action: send We'd Love to See You Back.
- Delay: 7 days.
- Branch: reply/click / no response.
- Follow-up: create a task for the commercial owner; stop automated contact after the defined sequence.

## Global safeguards
- Confirm marketing consent and subscription type before enrollment.
- Exclude unsubscribed, hard-bounced, legally suppressed and recently contacted records.
- Apply frequency caps across all workflows.
- Use only verified booking, search, listing-performance and engagement data.
- Do not use academic simulation fields as factual behavioral evidence.
- Test with internal contacts and preview records before activating.
- Maintain a human review step for B2B commercial follow-up.
