# Policies site (for Twilio campaign vetting)

Static privacy policy + terms pages to satisfy the sole-prop 10DLC campaign
application (and toll-free verification, if pursued). Host on GitHub Pages —
public URL in ~2 minutes.

## Setup
1. Create a NEW public repo (e.g. `shift-notify-policies`) — keep the
   callout-agent code repo private/separate.
2. Push these three files to the repo root: index.html, privacy.html, terms.html.
3. Repo → Settings → Pages → Source: "Deploy from a branch" → main / (root) → Save.
4. Wait for the URL: https://<username>.github.io/shift-notify-policies/
5. In the campaign form:
   - Privacy policy: https://<username>.github.io/shift-notify-policies/privacy.html
   - Terms:          https://<username>.github.io/shift-notify-policies/terms.html

## Before pushing — replace every placeholder (search for "["):
- [BRAND NAME AS REGISTERED] — must match the sole-prop brand name EXACTLY as
  entered in the Twilio registration (all three files, headers and footers).
- [CONTACT EMAIL] — a real monitored inbox.
- [CITY, STATE] and [STATE] — registrant's location (terms §11 governing law).

## Consistency rules (what vetting checks)
- Same brand name on the pages and in the registration.
- Opt-in story on the pages matches the campaign form (onboarding consent or
  text JOIN; consent not a condition of employment).
- STOP/HELP, "message frequency varies," "message and data rates may apply"
  appear on the pages AND in your sample messages.
- The privacy policy's mobile-information clause (§5) is the sentence
  reviewers scan for — do not reword it.
