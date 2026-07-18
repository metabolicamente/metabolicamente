# Metabolicamente — Project Brief
*Last updated: 2026-07-11*

## What it is
Consulting business: psychiatry with an emphasis on nutrition ("metabolic psychiatry").
Philosophy reference: https://youtu.be/hCyvqRq5YmM (shares the philosophy, business not in the video).
Considering a subscription model (undecided).

## Team & timeline
- Felipe + Igor (business partner). Igor built the Lovable prototype.
- 1 doctor onboarded; Igor meets a 2nd doctor early August → prototype must be ready before then.
- MVP launch: November. Marketing push: October.
- Prototype in English first (current Lovable prototype is in Portuguese).

## Prototype (Lovable)
- Project: "Metabolicamente" — https://lovable.dev/projects/48c18538-74ae-418d-a1cd-127341734ee7 (owned by Igor, shared with Felipe)
- Current state: dark green/cream landing page, "Psiquiatria Metabólica — Uma nova abordagem para a saúde mental", single login adapting to 3 roles.
- Code export: Igor connects GitHub sync (GitHub icon in project toolbar) → shared repo → clone locally.

## Product: 3 POVs (role-based dashboards)
1. **Doctor POV**
   - Schedule + upcoming sessions/appointments
   - Patient health overview: progress over time, nutrition tracking, lab results, ketone levels
   - Way to flag/track whether patients are doing well or poorly
2. **Nutritionist POV** — similar to doctor's
3. **Patient POV**
   - Own health markers, track results over time
   - Next appointments with doctor and nutritionist
   - Future: AI summary at top of dashboard

## Design direction
- Modern, inviting, warm, competent
- Goal: best-in-class UX; eventually a mobile app too
- Deep research on healthcare dashboard UX best practices still to be done

## Build plan (agreed 2026-07-11)
1. Prototype phase: iterate in Lovable; connect GitHub for backup
2. MVP phase: clone repo, build in Claude Code (auth, roles, data, scheduling)
3. Cowork for research, marketing, business docs
- Backend: Supabase (Lovable native). Mind LGPD (Brazil) for patient data.

## Decisions
- Demo will be in ENGLISH (decided 2026-07-11)
- Terminology (from research): "appointment" for scheduling, "session" for the encounter, "patient" not client, "care team", "care plan"
- Waiting on Igor to connect Lovable → GitHub

## Open questions
- Subscription vs per-session pricing (research suggests ladder: entry visit → membership → maintenance tier)

## Research
- Full UX research report: METABOLICAMENTE_UX_RESEARCH.md (2026-07-11)
