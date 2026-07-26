# AI Lead Segmentation Automation (Make.com)

## Problem
Businesses lose warm leads to slow, generic follow-up.

## Solution
A Make.com scenario that captures leads, segments them by interest,
and sends an AI-personalized welcome email per segment — with a
human-readable CRM record and delivery tracking.

## How it works
Form submission → lead captured to CRM with tag → Router splits by
interest → each segment gets a differently-toned AI email (Gemini) →
delivery confirmation flag set. Includes a fallback path for
unmatched segments.

## Stack
Make.com · Google Sheets · Gmail · Google Gemini API

## Notes
CRM step swaps directly for GoHighLevel / HubSpot / Airtable.
Blueprint included (sanitized). Demo video: [Loom link]
