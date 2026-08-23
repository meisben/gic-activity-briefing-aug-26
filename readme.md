# Work Experience Brief — Girls into Coding Climate Activity

**Placement:** 3 weeks · **Dates:** [FILL IN]  
**Supervisor:** Ben MC — WhatsApp anytime, flexible; 30–60 min check-in [FILL IN cadence]  
**Budget:** £600 total (Max), ~£100/kit max, 6 kits (aim lower, keep spares budget)

---

## 1. The mission

Design, build and document a new Girls into Coding workshop activity on the theme of climate. It must combine **software** with a **physical build**, and be deliverable to **6 girls aged 10–14** with mixed experience — some complete beginners, some returners.

Everything is open source. You keep full credit, can share it in your portfolio, and are welcome to help deliver it at a real event (subject to DBS — flag early if interested, the lead time is the bottleneck).

## 2. Choose one of three

Three worked-up concepts. **Pick one [by end of day 2] and tell me. Create a parts list and I'll send you the budget to order.** Three weeks is tight, recommend keep as simple as possible.

### Option A — Climate Beacon

Each girl builds a desk light — frame, diffuser, LED ring on a micro:bit — that glows a colour driven by live UKHSA weather-health alert data. The alert risk score is a 1–16 scale from impact × likelihood, which maps cleanly to green-through-red.

*Strongest on:* live real-world data. *Weakest on:* least hands-on making of the three, and depends on an alert actually being active.

### Option B — Keep Your Cool

Girls build a model room from card and test shading, insulation and ventilation against a heat lamp, with the micro:bit logging temperature. Whose room stays coolest? Software is data logging and plotting.

*Strongest on:* making, materials, and head-to-head competition — closest to how our other activities feel. Cheapest. *Weakest on:* least "software engineering" of the three.

### Option C — Warming Stripes Lamp

An LED strip in a built frame showing Ed Hawkins-style warming stripes from a century of real UK annual temperature data. The coding is genuine data work: parse, normalise, map to colour.

*Strongest on:* prettiest takeaway object, and completely immune to network and seasonality problems since the data ships with the repo. *Weakest on:* no live data.


## 3. Things that may help

- **A micro:bit has no internet.** Anything live needs a laptop running Python that fetches and pushes to the micro:bit over USB serial or radio. Applies to A and the hybrid — decide the architecture early.
- Platform is micro:bit by default (it's what our other activities use). Deviate only with a reason, and flag it on day 2 with your choice.
- Whichever you pick: **it has to work with no internet.** Live data can be the stretch, never the dependency.

## 4. Deliverables

1. **Hugo site** with the activity instructions, in the style of our existing activities — fork the wind turbine repo for structure.
2. **Code repo** — the micro:bit code and any laptop-side bridge, commented for a beginner reader.
3. **Bill of materials** — every part, supplier link, unit price, total per kit.
4. **Mentor notes** — how to run the session, timings, common failure points, what to do when a kit breaks.
5. **Risk assessment** — soldering, tools, heat, small parts, electrical.
6. **A working physical build**, tested end to end.

## 5. Milestones

| | Goal | Gate |
|---|---|---|
| **Week 1** | Choose, then prototype | **Day 2: option chosen, parts ordered.** By Friday: architecture decided, BOM drafted, rough build working on the bench |
| **Week 2** | Build and code | Working on a real kit; instructions drafted |
| **Week 3** | Document and hand over | Site live; risk assessment done; tested on a non-expert; handover call |

**Week 1, days 1–2 — orientation and decision:**

- Watch the National Emergency Briefing long-form expert briefings online at [nebriefing.org](https://www.nebriefing.org/expert-briefings)
- Read through our existing activities: the [wind turbine](https://meisben.github.io/gic_windTurbine_website/) and [volume meter](https://meisben.github.io/gic_volumeMeter_website_live/) sites and repos
- Write down your ideas about the activity that you want to create
- Decide what materials and tools you might like to use

## 6. How we'll work

I'm on annual leave for part of this but available throughout on a flexible basis. **WhatsApp me freely — don't sit blocked.** Send a short end-of-day note: what you did, what's next, what's stuck. We'll do a longer call at each week's gate.

Assume you'll need to be fairly independent. That's the main reason the options are pre-worked rather than open-ended.

## 7. Definition of done

A GIC mentor who has never seen this activity can pick up the site, the kit and the mentor notes, and run it for 6 girls without asking you anything.

## 8. The bit people underestimate

The hard part isn't the code. It's writing instructions an 11-year-old can follow without help, and finding the ten small ways the build fails in a real room. Leave real time in week 3 for testing on someone who isn't an engineer.
