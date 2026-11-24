First Shortlist · standalone landing page for recruitment teams
================================================================

What it is
----------
A single-page website (index.html + assets/style.css, no build step) that
Sehar sends to recruitment teams instead of her generic portfolio link.
It speaks only to recruiters, in their language: their pain, the fix, and
what they get. All copy is plain English, no invented clients, results,
testimonials or numbers. The only number on the page is the time-math
example, labelled as an example.

Sections
---------
- Hero: "The first shortlist, without opening every CV." plus two CTAs.
- Pain: "Does this sound familiar?" with the three real pains a recruiter
  told Sehar in chat (CVs can say anything; sessions on different dates;
  team does the chasing), plus the time-math example.
- How it works: three steps (CVs in, candidate voice intro, shortlist
  ready in a sheet) with simple CSS/SVG visuals.
- Mid CTA: "See it on one of your roles." with both CTAs again.
- What you get: time back, shortlist built on what candidates say,
  sessions scheduled, team meets finalists only.
- To start: "one role, and its criteria" plus the note that everything
  is set up around how the team hires (not a fixed template), plus the
  paid line "We start with one role as a small paid trial."
- Final CTA: terracotta panel "Start with one role." with the two big
  CTAs, the single line "No pitch. I will show it live on one of your
  roles." and the byline "Built and set up by Gul Sehar."
- Footer: email, LinkedIn, WhatsApp.

CTAs
----
Both buttons appear in three places (hero, mid CTA, final CTA) and in a
sticky bottom bar on mobile. Destinations, unchanged:
- Chat on WhatsApp: https://wa.me/923153647191
- Book 15 minutes: https://calendly.com/alphafluxai/ai-consulation

Design
------
Editorial Terracotta, same as Sehar's portfolio: warm beige paper #F6F1E8,
surface #EFE7D8, ink #1C1917, terracotta accent #C14A24, dark panel
#211A14 with cream text #F5EFE6. System font stack. Mobile-first,
no horizontal overflow at 390px or 1440px.

How the voice intro works (behind the scenes only, never on the page)
---------------------------------------------------------------------
The short voice intro runs on Vapi. A candidate opens a link, a voice
agent asks two or three screening questions for that role, the candidate
answers by voice (30 to 60 seconds), and the answers land in the
shortlist sheet. The page itself never mentions Vapi, n8n, GoHighLevel
or any tool name. It sells the outcome, not the tools.

Status
------
Built and render-verified 2026-11-24 (v2: final CTA, paid line, byline,
dedupe, spacing polish, tablet breakpoint). LIVE on Vercel:
https://1st-shortlist.vercel.app/ (repo alphafluxai-blip/pehli-shortlist,
main branch; Vercel auto-deploys on push). NOT on Netlify.
