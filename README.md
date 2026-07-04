<div align="center">

<img src="https://capsule-render.vercel.app/api?type=blur&color=0:000000,100:0a0a12&height=180&section=header&text=ADITHYAN%20JAGADEESWARAN&fontSize=34&fontColor=e8e8ed&fontAlignY=45&desc=Founder%20%40%20Valsia%20%C2%B7%20Building%20Secure%20AI%20Systems&descAlignY=62&descSize=15&descColor=8b8bf5&animation=fadeIn" width="100%"/>

<br/>

<a href="https://github.com/kiyotakaaKira">
  <img src="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=400&size=20&duration=3500&pause=1200&color=8B8BF5&center=true&vCenter=true&width=600&lines=Founder+%40+Valsia;AI+Infrastructure+%26+Agentic+Systems;Security-First+Backend+Engineering;Chennai%2C+India" alt="Typing SVG" />
</a>

<br/><br/>

<sub>
<a href="https://portfolio-nfdc.vercel.app/">Portfolio</a> &nbsp;·&nbsp;
<a href="https://www.linkedin.com/in/adithyan-jagadeeswaran/">LinkedIn</a> &nbsp;·&nbsp;
<a href="mailto:your-email@example.com">Email</a> &nbsp;·&nbsp;
Chennai, India
</sub>

<br/><br/>

<img src="https://img.shields.io/badge/CURRENT_MISSION-Building_Valsia-000000?style=flat-square&labelColor=0a0a12&color=8B8BF5" alt="mission"/>

</div>

<br/>

## Founder Manifesto

I don't build AI systems to demonstrate that I can. I build them because most AI products today skip the part that actually matters — what happens when the system is wrong, attacked, or trusted with something it shouldn't be.

My work sits at the intersection of two disciplines that are usually kept apart: **building intelligent systems** and **breaking them on purpose**. I design agentic AI products the way a security engineer would — assuming failure, assuming misuse, assuming an adversary is already inside the loop. That's not caution for its own sake. It's what separates a demo from a product people can rely on.

Right now that means building **Valsia**, an AI-powered skill-to-employability engine, and shipping **CIT-Sentinel**, a real-time academic risk-detection platform running on live infrastructure with an actual dataset behind it — not a mockup. Both exist because I'd rather ship something that works under real conditions than something that only works in a pitch.

<br/>

## Products

<table>
<tr>
<td width="50%" valign="top">

### Valsia
**AI-powered skill-to-job conversion engine**

**Mission** — Convert scattered, unvalidated skills into a clear, employable career path with a measurable readiness score.

**Architecture** — Next.js frontend, containerized backend, local LLaMA-class inference over Docker Compose for on-prem/private deployment (no external API dependency required).

**Stack** — `Next.js` `TypeScript` `Docker` `Local LLM (LLaMA/GGUF)`

**Status** — `Phase 1 MVP — active`

**Engineering Challenge** — Running inference entirely offline forced tight constraints on model size vs. output quality, and keeping the skill-gap scoring logic explainable rather than a black box.

**Business Impact** — Positions skill development as a pipeline with a measurable output (job-readiness), not a content-consumption product.

[`Live`](https://valsia-1-kappa.vercel.app) · [`Repository`](https://github.com/kiyotakaaKira/valsia-1)

</td>
<td width="50%" valign="top">

### CIT-Sentinel
**AI-driven student retention & dropout-prevention platform**

**Mission** — Predict academic dropout risk weeks before it becomes irreversible, and route the right intervention to the right role automatically.

**Architecture** — React/Vite frontend talking to an Express + MongoDB Atlas backend over REST, with Server-Sent Events pushing live score updates to six role-based dashboards. A `pre-save` hook recalculates a weighted risk score on every data mutation.

**Stack** — `React` `TypeScript` `Node.js` `Express` `MongoDB Atlas` `Llama 3.2 (Ollama)` `Claude API fallback`

**Status** — `Deployed — functional with live data`

**Engineering Challenge** — Keeping six dashboards (Student → Chairman) in sync in real time without polling everything, and designing a scoring formula that's transparent enough for a teacher to trust it.

**Business Impact** — Modeled against a 560-student dataset across 4 departments; designed to cut intervention response time from 4–6 weeks to under one.

[`Live`](https://cit-sentinal.vercel.app) · [`Repository`](https://github.com/kiyotakaaKira/cit-sentinel-v2)

</td>
</tr>
</table>

<br/>

## Engineering Expertise

<table>
<tr>
<td width="33%" valign="top">

**AI Systems**
Agentic architectures, LLM orchestration, local + cloud inference fallback design, prompt-as-contract patterns

</td>
<td width="33%" valign="top">

**Backend & Distributed Systems**
REST API design, real-time sync via SSE, role-based access control, schema-driven data integrity

</td>
<td width="33%" valign="top">

**Cybersecurity & AI Security**
Threat modeling, agent security, network fundamentals, zero-trust reasoning applied to AI pipelines

</td>
</tr>
<tr>
<td width="33%" valign="top">

**Cloud Infrastructure**
MongoDB Atlas, Vercel deployment pipelines, containerized services with Docker Compose

</td>
<td width="33%" valign="top">

**Computer Vision**
Applied CV for monitoring and detection use cases within AI product prototypes

</td>
<td width="33%" valign="top">

**System Design**
Designing for explainability and auditability first — score formulas, activity logs, and audit trails as first-class features, not afterthoughts

</td>
</tr>
</table>

<br/>

## Founder Timeline

```
2026   ── CIT-Sentinel deployed with live MongoDB Atlas backend, 560-student dataset,
           real-time SSE sync, and dual AI inference (Llama 3.2 + Claude fallback)

2025   ── Co-founded Valsia — shipped Phase 1 MVP of the Skill Mentor module
       ── Selected across national hackathon circuits: RIFT, Vortexa, SDG Hackathon,
           Aiventra, Resilient, DevFusion, ET Hackathon, SAHAI, HackOrbit,
           Bharatiya Antariksh Hackathon
       ── Began formal study in AI & Data Science, Chennai Institute of Technology

Ongoing ── Practicing offensive security fundamentals (Linux, networking, CTF-style
           problem solving) to inform how I secure the systems I build
```

<br/>

## Current Focus

- Scaling **Valsia** past MVP into a production-ready skill-to-job engine
- Hardening AI infrastructure — fallback inference, rate limiting, prompt-injection resistance
- Designing secure agentic systems from first principles rather than bolting on security later
- Deepening backend and distributed-systems fundamentals through shipped work, not tutorials
- Contributing to open source as a way of stress-testing my code against strangers' standards

<br/>

## GitHub Analytics

<div align="center">

<img height="160" src="https://github-readme-stats.vercel.app/api?username=kiyotakaaKira&show_icons=true&theme=dark&hide_border=true&bg_color=00000000&title_color=8B8BF5&icon_color=8B8BF5&text_color=c4c4cc"/>
<img height="160" src="https://github-readme-streak-stats.herokuapp.com/?user=kiyotakaaKira&theme=dark&hide_border=true&background=00000000&ring=8B8BF5&fire=8B8BF5&currStreakLabel=8B8BF5"/>

<br/>

<img src="https://github-readme-activity-graph.vercel.app/graph?username=kiyotakaaKira&theme=slate-dark&hide_border=true&bg_color=00000000&color=8B8BF5&line=8B8BF5&point=e8e8ed"/>

<br/>

<img src="https://github-profile-trophy.vercel.app/?username=kiyotakaaKira&theme=darkhub&no-frame=true&row=1&column=6&margin-w=12"/>

</div>

<br/>

## Engineering Principles

> Every system I ship gets asked the same three questions before it's "done": What happens when this is wrong? What happens when someone attacks it? What happens when it has to work without me watching it? A product that hasn't answered those is a prototype wearing a product's clothes.

<br/>

<div align="center">

---

<a href="https://portfolio-nfdc.vercel.app/">Portfolio</a> &nbsp;·&nbsp;
<a href="https://www.linkedin.com/in/adithyan-jagadeeswaran/">LinkedIn</a> &nbsp;·&nbsp;
<a href="https://github.com/kiyotakaaKira">GitHub</a> &nbsp;·&nbsp;
<a href="mailto:your-email@example.com">Email</a>

</div>
