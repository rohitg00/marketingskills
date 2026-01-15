# Marketing Skills for Claude Code

A collection of AI agent skills focused on marketing tasks. Built for technical marketers and founders who want Claude Code (or similar AI coding assistants) to help with conversion optimization, copywriting, SEO, analytics, and growth engineering.

## What are Skills?

Skills are markdown files that give AI agents specialized knowledge and workflows for specific tasks. When you add these to your project, Claude Code can recognize when you're working on a marketing task and apply the right frameworks and best practices.

## Available Skills

| Skill | Description | Triggers |
|-------|-------------|----------|
| [page-cro](skills/page-cro.md) | Conversion optimization for any marketing page | "optimize [page]," "CRO," "page isn't converting" |
| [page-copywriting](skills/page-copywriting.md) | Write or improve marketing copy | "write copy," "rewrite," "headlines," "CTA copy" |
| [signup-flow-cro](skills/signup-flow-cro.md) | Optimize signup and registration flows | "signup optimization," "registration form" |
| [onboarding-cro](skills/onboarding-cro.md) | Improve user activation and onboarding | "onboarding," "activation," "first-run experience" |
| [form-cro](skills/form-cro.md) | Optimize lead capture and contact forms | "form optimization," "lead form," "contact form" |
| [popup-cro](skills/popup-cro.md) | Create/optimize popups and modals | "popup," "modal," "exit intent" |
| [paywall-upgrade-cro](skills/paywall-upgrade-cro.md) | In-app paywalls and upgrade screens | "paywall," "upgrade screen," "feature gate" |
| [email-sequence](skills/email-sequence.md) | Build email sequences and drip campaigns | "email sequence," "drip campaign," "nurture" |
| [seo-audit](skills/seo-audit.md) | Audit technical and on-page SEO | "SEO audit," "technical SEO," "not ranking" |
| [programmatic-seo](skills/programmatic-seo.md) | Build SEO pages at scale | "programmatic SEO," "template pages," "pages at scale" |
| [competitor-alternatives](skills/competitor-alternatives.md) | Competitor comparison and alternative pages | "vs page," "alternative page," "[X] vs [Y]," "competitor comparison" |
| [schema-markup](skills/schema-markup.md) | Add structured data and rich snippets | "schema," "JSON-LD," "structured data" |
| [analytics-tracking](skills/analytics-tracking.md) | Set up tracking and measurement | "tracking," "GA4," "GTM," "events" |
| [ab-test-setup](skills/ab-test-setup.md) | Plan and implement A/B tests | "A/B test," "split test," "experiment" |
| [free-tool-strategy](skills/free-tool-strategy.md) | Plan engineering-as-marketing tools | "free tool," "calculator," "lead gen tool" |

## Installation

### Option 1: Copy Individual Skills (Recommended)

Copy just the skills you need into your project's `.claude/skills/` directory:

```bash
# Create skills directory if it doesn't exist
mkdir -p .claude/skills

# Copy specific skills you want
curl -o .claude/skills/page-cro.md https://raw.githubusercontent.com/YOUR_USERNAME/marketingskills/main/skills/page-cro.md
curl -o .claude/skills/seo-audit.md https://raw.githubusercontent.com/YOUR_USERNAME/marketingskills/main/skills/seo-audit.md
```

### Option 2: Clone All Skills

Clone the entire repo and copy the skills folder:

```bash
git clone https://github.com/YOUR_USERNAME/marketingskills.git
cp -r marketingskills/skills .claude/
```

### Option 3: Git Submodule

Add as a submodule for easy updates:

```bash
git submodule add https://github.com/YOUR_USERNAME/marketingskills.git .claude/marketingskills
```

Then reference skills from `.claude/marketingskills/skills/`.

### Option 4: Fork and Customize

1. Fork this repository
2. Customize skills for your specific needs
3. Clone your fork into your projects

## Usage

Once installed, just ask Claude Code to help with marketing tasks:

```
"Help me optimize this landing page for conversions"
→ Uses page-cro skill

"Write homepage copy for my SaaS"
→ Uses page-copywriting skill

"Set up GA4 tracking for signups"
→ Uses analytics-tracking skill

"Create a 5-email welcome sequence"
→ Uses email-sequence skill
```

You can also invoke skills directly:

```
/page-cro
/email-sequence
/seo-audit
```

## Skill Categories

### Conversion Optimization
- `page-cro` - Any marketing page
- `signup-flow-cro` - Registration flows
- `onboarding-cro` - Post-signup activation
- `form-cro` - Lead capture forms
- `popup-cro` - Modals and overlays
- `paywall-upgrade-cro` - In-app upgrade moments

### Content & Copy
- `page-copywriting` - Marketing page copy
- `email-sequence` - Automated email flows

### SEO & Discovery
- `seo-audit` - Technical and on-page SEO
- `programmatic-seo` - Scaled page generation
- `competitor-alternatives` - Comparison and alternative pages
- `schema-markup` - Structured data

### Measurement & Testing
- `analytics-tracking` - Event tracking setup
- `ab-test-setup` - Experiment design

### Growth Engineering
- `free-tool-strategy` - Marketing tools and calculators

## Contributing

Found a way to improve a skill? PRs welcome.

1. Fork the repo
2. Edit the skill file(s)
3. Submit a PR with a clear description of what you improved

### Skill File Structure

Each skill follows this format:

```markdown
---
name: skill-name
description: One-line description for skill selection
---

# Skill Name

[Full instructions for the AI agent]
```

## License

MIT - Use these however you want.

## Author

Built by [Corey Haines](https://corey.co) for the marketing-minded builder who'd rather prompt than point-and-click.

Need hands-on marketing help? Check out [Conversion Factory](https://conversionfactory.co) — Corey's agency for conversion optimization, landing pages, and growth strategy.
