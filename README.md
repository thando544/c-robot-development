# Green Victoria Falls

A live **hotel and lodge green badge** for Victoria Falls. Visitors can see which stays follow the city’s 2030 sustainability rules. Operators claim their listing and keep the evidence current.

This is not an official City Council product. It is aligned with the *City of Victoria Falls Sustainability Monograph* (SDG 11 status by 2030): biogas, grey water, no-plastic, solar, green buildings, and low-carbon guest transport.

## What we are building first

A public badge per property, plus an operator dashboard.

**Guests** open a QR code or listing and see a level (Bronze / Silver / Gold), what the property actually does, and when it was last verified. A badge that is not updated goes stale.

**Hotels and lodges** claim their page, complete a short green checklist, and upload proof. They own that data. We do not scrape it from Booking or TripAdvisor.

**Later** the same records can feed a city map, community waste tools, and Council MRV. That is not v1.

## How property data works

| Data | Source |
| --- | --- |
| Name, type, licence, email | Zimbabwe Tourism Authority registered operators (Victoria Falls only) |
| Map pin, phone, website, photo | Google Places or OpenStreetMap |
| Biogas, grey water, solar, plastic, EVs, monthly figures | Claimed by the property |

Seed the directory, mark listings unclaimed, invite the ZTA contact. Green fields are never overwritten by an API.

## Badge levels

- **Bronze — committed:** waste separation, plastic limits, a named green contact, and at least one of solar water heating, grey water, or a dated biogas plan.
- **Silver — operating:** biogas or contracted organic-waste diversion, grey water or rainwater, solar on lights or geysers, guest-facing no-plastic, monthly data.
- **Gold — city-aligned:** metered biogas, grey water and solar, EV or shared-transfer option, numbers that can support later MRV.

## Why it exists

The monograph asks every arrival to see a low-carbon tourism city. Right now a guest cannot tell a lodge that dumps kitchen waste from one that runs a digester. Council does not need to approve v1. They become the legitimacy partner if this later becomes the compliance register.

## Status

Early product definition. Implementation has not started.
