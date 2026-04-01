# Marketing Skills for Claude

A collection of marketing skills designed for **Claude Projects** on claude.ai. Drop these into any project as knowledge files and Claude becomes a marketing strategist who already knows your business.

Built for marketers, small business owners, freelancers, and founders who use Claude — not developers in a terminal. Works with any business type: service providers, product companies, local businesses, e-commerce, agencies, creators, and SaaS.

Built by [David Hevesi](https://studiohevesi.com).

---

## What Are Skills?

Skills are markdown files that give Claude specialized marketing knowledge, frameworks, and workflows. When you add them to a Claude Project as knowledge files, Claude can:

- Apply proven marketing frameworks without you needing to explain them
- Reference your business context across every conversation
- Follow structured processes instead of giving generic advice
- Self-review its own output before presenting it to you

**No terminal. No code. No installation commands.** Just download a `.md` file and drag it into your Claude Project.

---

## How to Use

### Step 1: Download the skill(s) you want

Click into any skill folder below and download the `SKILL.md` file.

### Step 2: Add to your Claude Project

1. Open [claude.ai](https://claude.ai)
2. Create a new Project (or open an existing one)
3. Click **"Add knowledge"** in the project settings
4. Upload the `SKILL.md` file(s)

### Step 3: Start using it

Just talk to Claude naturally. The skill is always active in that project.

```
"Help me define my business context"
→ Uses business-context skill

"Write homepage copy for my website"
→ Uses copywriting skill

"Create a 5-email welcome sequence"
→ Uses email-marketing skill

"Audit my website for SEO issues"
→ Uses seo-strategy skill
```

---

## How Skills Work Together

The `business-context` skill is the foundation. **Set it up first.** Every other skill checks for it before asking questions, so you never have to re-explain your business.

```
                    ┌─────────────────────────┐
                    │    business-context      │
                    │  (set up first — every   │
                    │  other skill reads this) │
                    └────────────┬────────────┘
                                 │
        ┌────────────┬───────────┼───────────┬────────────┐
        ▼            ▼           ▼           ▼            ▼
  ┌──────────┐ ┌──────────┐ ┌──────────┐ ┌──────────┐ ┌──────────┐
  │ Content  │ │ SEO &    │ │ Growth & │ │Strategy  │ │  Brand   │
  │ & Copy   │ │   Web    │ │ Clients  │ │          │ │  Voice   │
  ├──────────┤ ├──────────┤ ├──────────┤ ├──────────┤ ├──────────┤
  │copywritng│ │seo-      │ │lead-gen  │ │marketing-│ │brand-    │
  │email-mktg│ │strategy  │ │client-   │ │strategy  │ │voice     │
  │social-   │ │website-  │ │  comms   │ │audience- │ │          │
  │content   │ │  optim   │ │          │ │research  │ │          │
  │          │ │          │ │          │ │competitr │ │          │
  └──────────┘ └──────────┘ └──────────┘ └──────────┘ └──────────┘
```

---

## Available Skills

### Foundation
| Skill | Description | Status |
|---|---|---|
| [business-context](skills/business-context) | Capture your business identity, audience, positioning, voice, and goals. Every other skill references this. | ✅ Available |
| [brand-voice](skills/brand-voice) | Define and maintain consistent brand voice and communication style across all outputs. | ✅ Available |

### Content & Copy
| Skill | Description | Status |
|---|---|---|
| [copywriting](skills/copywriting) | Full-process marketing copywriting — from research to draft to self-edit to final. Headlines, CTAs, value props, service descriptions. | ✅ Available |
| [email-marketing](skills/email-marketing) | Welcome sequences, nurture campaigns, cold outreach, re-engagement, newsletters. | ✅ Available |
| [social-content](skills/social-content) | Platform-specific content creation with calendar framework. Instagram, LinkedIn, TikTok, X. | ✅ Available |

### SEO & Web Presence
| Skill | Description | Status |
|---|---|---|
| [seo-strategy](skills/seo-strategy) | Technical SEO, on-page optimization, keyword research, AI search optimization, and local SEO. | ✅ Available |
| [website-optimization](skills/website-optimization) | Page conversion optimization, site structure, user flow, trust building, mobile experience. | ✅ Available |

### Growth & Client Acquisition
| Skill | Description | Status |
|---|---|---|
| [lead-generation](skills/lead-generation) | Lead magnets, opt-in strategy, landing pages, partnerships, referral systems. | ✅ Available |
| [client-communication](skills/client-communication) | Proposals, follow-ups, project updates, review requests, testimonial collection, re-engagement. | ✅ Available |

### Strategy & Research
| Skill | Description | Status |
|---|---|---|
| [marketing-strategy](skills/marketing-strategy) | 90-day marketing plans, channel selection, budget allocation, goal setting, KPI frameworks. | 🔜 Coming soon |
| [audience-research](skills/audience-research) | Deep customer research — review mining, competitor audience analysis, survey design, language patterns. | 🔜 Coming soon |
| [competitor-analysis](skills/competitor-analysis) | Full competitive landscape — positioning gaps, pricing comparison, messaging differentiation. | 🔜 Coming soon |

---

## What Makes These Different

**Built for claude.ai, not the terminal.** Most marketing skill repos assume you're a developer running commands. These are designed for people who use Claude through the chat interface and Projects.

**Works for any business type.** Not just SaaS. Service providers, local businesses, e-commerce, freelancers, agencies, creators — the skills adapt their frameworks based on your business type.

**Fewer skills, more depth.** 12 skills that each cover a complete workflow (research → plan → execute → review), not 33 shallow skills that give you principles without process.

**Built-in self-review.** Every skill includes a step where Claude evaluates its own output against quality criteria before presenting it to you.

**Real business context.** The foundation skill captures brand voice, current marketing situation, anti-audience, competitive landscape, and customer language — not just product features.

---

## Roadmap

- [x] `business-context` — Foundation skill
- [x] `copywriting` — Marketing copy
- [x] `brand-voice` — Voice consistency
- [x] `email-marketing` — Email campaigns & sequences
- [x] `social-content` — Social media content
- [x] `seo-strategy` — Search optimization
- [x] `website-optimization` — Conversion & UX
- [x] `lead-generation` — Lead acquisition
- [x] `client-communication` — Client-facing comms
- [ ] `marketing-strategy` — Strategic planning
- [ ] `audience-research` — Customer research
- [ ] `competitor-analysis` — Competitive intelligence

---

## Contributing

Found a way to improve a skill? Have an idea for a new one? PRs and issues are welcome.

See [CONTRIBUTING.md](CONTRIBUTING.md) for guidelines.

---

## License

[MIT](LICENSE) — Use these however you want.
