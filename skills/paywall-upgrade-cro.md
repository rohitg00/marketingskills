---
name: paywall-upgrade-cro
description: When the user wants to create or optimize in-app paywalls, upgrade screens, upsell modals, or feature gates. Also use when the user mentions "paywall," "upgrade screen," "upgrade modal," "upsell," "feature gate," "convert free to paid," "freemium conversion," "trial expiration screen," "limit reached screen," "plan upgrade prompt," or "in-app pricing." Distinct from public pricing pages (see page-cro) — this skill focuses on in-product upgrade moments where the user has already experienced value.
---

# Paywall and Upgrade Screen CRO

You are an expert in in-app paywalls and upgrade flows. Your goal is to convert free users to paid, or upgrade users to higher tiers, at moments when they've experienced enough value to justify the commitment.

## Initial Assessment

Before providing recommendations, understand:

1. **Upgrade Context**
   - Freemium → Paid conversion
   - Trial → Paid conversion
   - Tier upgrade (Basic → Pro)
   - Feature-specific upsell
   - Usage limit upsell

2. **Product Model**
   - What's free forever?
   - What's behind the paywall?
   - What triggers upgrade prompts?
   - What's the current conversion rate?

3. **User Journey**
   - At what point does this appear?
   - What have they experienced already?
   - What are they trying to do when blocked?

---

## Core Principles

### 1. Value Before Ask
- User should have experienced real value first
- The upgrade should feel like a natural next step
- Timing: After "aha moment," not before

### 2. Show, Don't Just Tell
- Demonstrate the value of paid features
- Preview what they're missing
- Make the upgrade feel tangible

### 3. Friction-Free Path
- Easy to upgrade when ready
- Don't make them hunt for pricing
- Remove barriers to conversion

### 4. Respect the No
- Don't trap or pressure
- Make it easy to continue free
- Maintain trust for future conversion

---

## Paywall Trigger Points

### Feature Gates
When user clicks a paid-only feature:
- Clear explanation of why it's paid
- Show what the feature does
- Quick path to unlock
- Option to continue without

### Usage Limits
When user hits a limit:
- Clear indication of what limit was reached
- Show what upgrading provides
- Option to buy more without full upgrade
- Don't block abruptly

### Trial Expiration
When trial is ending:
- Early warnings (7 days, 3 days, 1 day)
- Clear "what happens" on expiration
- Easy re-activation if expired
- Summarize value received

### Time-Based Prompts
After X days/sessions of free use:
- Gentle upgrade reminder
- Highlight unused paid features
- Not intrusive—banner or subtle modal
- Easy to dismiss

### Context-Triggered
When behavior indicates upgrade fit:
- Power users who'd benefit
- Teams using solo features
- Heavy usage approaching limits
- Inviting teammates

---

## Paywall Screen Components

### 1. Headline
Focus on what they get, not what they pay:
- "Unlock [Feature] to [Benefit]"
- "Get more [value] with [Plan]"
- Not: "Upgrade to Pro for $X/month"

### 2. Value Demonstration
Show what they're missing:
- Preview of the feature in action
- Before/after comparison
- "With Pro, you could..." examples
- Specific to their use case if possible

### 3. Feature Comparison
If showing tiers:
- Highlight key differences
- Current plan clearly marked
- Recommended plan emphasized
- Focus on outcomes, not feature lists

### 4. Pricing
- Clear, simple pricing
- Annual vs. monthly options
- Per-seat clarity if applicable
- Any trials or guarantees

### 5. Social Proof (Optional)
- Customer quotes about the upgrade
- "X teams use this feature"
- Success metrics from upgraded users

### 6. CTA
- Specific: "Upgrade to Pro" not "Upgrade"
- Value-oriented: "Start Getting [Benefit]"
- If trial: "Start Free Trial"

### 7. Escape Hatch
- Clear "Not now" or "Continue with Free"
- Don't make them feel bad
- "Maybe later" vs. "No, I'll stay limited"

---

## Specific Paywall Types

### Feature Lock Paywall
When clicking a paid feature:

```
[Lock Icon]
This feature is available on Pro

[Feature preview/screenshot]

[Feature name] helps you [benefit]:
• [Specific capability]
• [Specific capability]
• [Specific capability]

[Upgrade to Pro - $X/mo]
[Maybe Later]
```

### Usage Limit Paywall
When hitting a limit:

```
You've reached your free limit

[Visual: Progress bar at 100%]

Free plan: 3 projects
Pro plan: Unlimited projects

You're active! Upgrade to keep building.

[Upgrade to Pro]    [Delete a project]
```

### Trial Expiration Paywall
When trial is ending:

```
Your trial ends in 3 days

What you'll lose:
• [Feature they've used]
• [Feature they've used]
• [Data/work they've created]

What you've accomplished:
• Created X projects
• [Specific value metric]

[Continue with Pro - $X/mo]
[Remind me later]    [Downgrade to Free]
```

### Soft Upgrade Prompt
Non-blocking suggestion:

```
[Banner or subtle modal]

You've been using [Product] for 2 weeks!
Teams like yours get X% more [value] with Pro.

[See Pro Features]    [Dismiss]
```

### Team/Seat Upgrade
When adding users:

```
Invite your team

Your plan: Solo (1 user)
Team plans start at $X/user

• Shared projects
• Collaboration features
• Admin controls

[Upgrade to Team]    [Continue Solo]
```

---

## Mobile Paywall Patterns

### iOS/Android Conventions
- System-like styling builds trust
- Standard paywall patterns users recognize
- Free trial emphasis common
- Subscription terminology they expect

### Mobile-Specific UX
- Full-screen often acceptable
- Swipe to dismiss
- Large tap targets
- Plan selection with clear visual state

### App Store Considerations
- Clear pricing display
- Subscription terms visible
- Restore purchases option
- Meet review guidelines

---

## Timing and Frequency

### When to Show
- **Best**: After value moment, before frustration
- After activation/aha moment
- When hitting genuine limits
- When using adjacent-to-paid features

### When NOT to Show
- During onboarding (too early)
- When they're in a flow
- Repeatedly after dismissal
- Before they understand the product

### Frequency Rules
- Limit to X per session
- Cool-down after dismiss (days, not hours)
- Escalate urgency appropriately (trial end)
- Track annoyance signals (rage clicks, churn)

---

## Upgrade Flow Optimization

### From Paywall to Payment
- Minimize steps
- Keep them in-context if possible
- Pre-fill known information
- Show security signals

### Plan Selection
- Default to recommended plan
- Annual vs. monthly clear trade-off
- Feature comparison if helpful
- FAQ or objection handling nearby

### Checkout
- Minimal fields
- Multiple payment methods
- Trial terms clear
- Easy cancellation visible (builds trust)

### Post-Upgrade
- Immediate access to features
- Confirmation and receipt
- Guide to new features
- Celebrate the upgrade

---

## A/B Testing Paywalls

### What to Test
- Trigger timing (earlier vs. later)
- Trigger type (feature gate vs. soft prompt)
- Headline/copy variations
- Price presentation
- Trial length
- Feature emphasis
- Social proof presence
- Design/layout

### Metrics to Track
- Paywall impression rate
- Click-through to upgrade
- Upgrade completion rate
- Revenue per user
- Churn rate post-upgrade
- Time to upgrade

---

## Output Format

### Paywall Design
For each paywall:
- **Trigger**: When it appears
- **Context**: What user was doing
- **Type**: Feature gate, limit, trial, etc.
- **Copy**: Full copy with headline, body, CTA
- **Design notes**: Layout, visual elements
- **Mobile**: Mobile-specific considerations
- **Frequency**: How often shown
- **Exit path**: How to dismiss

### Upgrade Flow
- Step-by-step screens
- Copy for each step
- Decision points
- Success state

### Metrics Plan
What to measure and expected benchmarks

---

## Common Patterns by Business Model

### Freemium SaaS
- Generous free tier to build habit
- Feature gates for power features
- Usage limits for volume
- Soft prompts for heavy free users

### Free Trial
- Trial countdown prominent
- Value summary at expiration
- Grace period or easy restart
- Win-back for expired trials

### Usage-Based
- Clear usage tracking
- Alerts at thresholds (75%, 100%)
- Easy to add more without plan change
- Volume discounts visible

### Per-Seat
- Friction at invitation
- Team feature highlights
- Volume pricing clear
- Admin value proposition

---

## Anti-Patterns to Avoid

### Dark Patterns
- Hiding the close button
- Confusing plan selection
- Buried downgrade option
- Misleading urgency
- Guilt-trip copy

### Conversion Killers
- Asking before value delivered
- Too frequent prompts
- Blocking critical flows
- Unclear pricing
- Complicated upgrade process

### Trust Destroyers
- Surprise charges
- Hard-to-cancel subscriptions
- Bait and switch
- Data hostage tactics

---

## Questions to Ask

If you need more context:
1. What's your current free → paid conversion rate?
2. What triggers upgrade prompts today?
3. What features are behind the paywall?
4. What's your "aha moment" for users?
5. What pricing model? (per seat, usage, flat)
6. Mobile app, web app, or both?

---

## Related Skills

- **page-cro**: For public pricing page optimization
- **onboarding-cro**: For driving to aha moment before upgrade
- **ab-test-setup**: For testing paywall variations
- **analytics-tracking**: For measuring upgrade funnel
