# Volet 3 — Email Design System

## Brand direction
- Deep blue: #003B95
- Primary blue: #0071C2
- Accent yellow: #FEBB02
- Background: #F2F6FA
- Body text: #1A1A1A
- Email canvas: 600px maximum, single column, mobile-first.
- Typography: Arial / Helvetica fallback for broad email-client support.
- CTA: solid primary blue, white bold text, 4px radius.
- Hero: full-width editorial photograph, no text baked into image.
- Header: brand wordmark text placeholder only. Replace with an approved official logo asset if available; do not fabricate the Booking.com logo.
- Footer: must use HubSpot's subscription/unsubscribe module and approved legal/company details.

## Image asset map
### B2C
- The Luxury Experience Seeker → `https://raw.githubusercontent.com/manelkrichene/marketingisgtuniscrmbooking/main/The%20Luxury%20Experience%20Seeker.jpg`
- The Budget Optimizer → `https://raw.githubusercontent.com/manelkrichene/marketingisgtuniscrmbooking/main/The%20Budget%20Optimizer.jpg`
- The Business Traveler → `https://raw.githubusercontent.com/manelkrichene/marketingisgtuniscrmbooking/main/The%20Business%20Traveler.jpg`
- The Family Trip Planner → `https://raw.githubusercontent.com/manelkrichene/marketingisgtuniscrmbooking/main/The%20Family%20Trip%20Planner.jpg`
- The Spontaneous Explorer → `https://raw.githubusercontent.com/manelkrichene/marketingisgtuniscrmbooking/main/The%20Spontaneous%20Explorer.jpg`

### B2B
- Hotel & Resort Partners → `https://raw.githubusercontent.com/manelkrichene/marketingisgtuniscrmbooking/main/Hotel%20%26%20Resort%20Partners.jpg`
- Guesthouses & Property Managers → `https://raw.githubusercontent.com/manelkrichene/marketingisgtuniscrmbooking/main/Guesthouses%20%26%20Property%20Managers.jpg`
- Travel Agencies & Tour Operators → `https://raw.githubusercontent.com/manelkrichene/marketingisgtuniscrmbooking/main/Travel%20Agencies%20%26%20Tour%20Operators.jpg`
- Activities, Experiences & Leisure Providers → `https://raw.githubusercontent.com/manelkrichene/marketingisgtuniscrmbooking/main/Activities%2C%20Experiences%20%26%20Leisure%20Providers.jpg`

## Implementation notes
- The HTML files in this repository are design prototypes, not yet published HubSpot templates.
- Replace the example CTA URL with a verified destination URL before sending.
- Confirm image URLs are publicly accessible to email clients.
- Use HubSpot personalization_token() syntax and safe fallbacks for empty properties.
- Do not claim access to booking history, search history, performance or availability unless those fields are actually connected.
- Do not send until subscription eligibility, sender, footer, links, rendering and recipient segment have been checked.
