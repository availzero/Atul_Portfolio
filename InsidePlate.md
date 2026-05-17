# InsidePlate - A Meal Prep & Health Tracker App
<br><br>
<img width="433" height="245" alt="Screenshot 2026-05-16 at 09 29 11" src="https://github.com/user-attachments/assets/9457eca1-feba-43c4-9004-123717cdd8bb" />
<br><br>

**InsidePlate** is an AI-assisted meal prep and macro tracking product built for users who want practical nutrition guidance without the friction of manual planning, repetitive logging, or generic diet advice.

The product is currently in development moving towards full release, with MVP ready.

## Product Thesis

Most nutrition apps ask users to do too much work: search meals manually, estimate portions, build plans from scratch, and interpret progress alone. InsidePlate is designed around a simpler promise:

**Help users know what to eat, log what they ate, and understand whether they are on track.**

The product combines meal planning, recipe discovery, food logging, progress tracking, and AI assistance into one mobile-first experience. The strategy is not to make AI the product by itself, but to use AI where it removes real user friction.

## Target Users

InsidePlate is aimed at health-conscious users who want structure but do not want a complex coaching program.

Primary user segments:

- Busy professionals trying to plan meals ahead of the week.
- Fitness-focused users tracking calories and macros.
- Users who want quick food logging through photos or guided review.
- Indian-market users who need affordable subscription pricing and familiar food planning workflows.
- Beginners who need simple progress signals instead of dense nutrition dashboards.

## User Problems

InsidePlate focuses on five product problems:

1. Meal planning is time-consuming.
2. Food logging is tedious and easy to abandon.
3. Generic recipe suggestions do not respect user goals or preferences.
4. Progress data is often disconnected from daily behavior.
5. AI-powered nutrition products can become costly or unreliable if every interaction depends on paid model calls.

## Product Solution

InsidePlate gives users a guided nutrition loop:

```text
Set goals
  -> Plan meals
  -> Log food
  -> Review progress
  -> Adjust the next plan
```

The product supports this loop through:

- A Today dashboard for daily action.
- A Plan view for weekly meal structure.
- A Recipes area for discovery and planning.
- A Progress area for behavior tracking and trends.
- A Profile and subscription surface for goals, account state, and premium access.
- Admin tools for launch readiness, usage monitoring, and product operations.

## Product Scope

### Scope

The MVP is scoped around the behaviors needed to validate repeat usage:

- Daily macro and meal dashboard.
- Meal logging with review before save.
- Recipe search and filters.
- Add recipes to specific days and meal slots.
- Generate or regenerate meal plans.
- Track daily water, steps, sleep, and workouts.
- Gate premium behavior behind subscription entitlements.
- Provide admin visibility into readiness, usage, and subscriber state.

### Out Of Scope For MVP

To protect launch focus, several items are intentionally deferred:

- Full public recipe marketplace.
- Social sharing or community features.
- Wearable integrations.
- Advanced coach marketplace.
- Full backend billing analytics automation.
- Public launch without legal, QA, and backend readiness checks.

## Product Decisions

### AI As A Friction Reducer

AI is used where it meaningfully reduces work: image-based meal understanding, meal plan generation, chat assistance, and recommendation support. The product avoids making every recipe lookup or simple interaction dependent on AI.

### Cost Control As A Product Constraint

The product was designed with strict development and operating cost awareness. Recipe data is served from local/internal sources first, and paid AI or external recipe APIs are treated as fallback paths. This supports a low-price subscription strategy without sacrificing margins.

### Review Before Automation

Meal logging includes a review step so users can confirm serving, meal slot, notes, and detected details before saving. This improves trust and gives the user control over AI-assisted outputs.

### Admin Tools Before Public Launch

InsidePlate includes owner-facing tools for release checklist tracking, subscriber management, feature flags, and usage/cost monitoring. This reduces launch risk and makes the product easier to operate after release.

## Core User Journeys

### 1. Plan A Week

The user sets preferences and generates a meal plan. They can add recipes to specific days, replace a meal, regenerate a day, or regenerate the week. The intended outcome is a practical plan the user can follow without starting from a blank page.

### 2. Log A Meal

The user logs food manually, from search, from recipe detail, or through the camera flow. Before saving, they review serving and meal-slot details. The intended outcome is faster logging with enough control to build trust.

### 3. Check Today

The user opens the Today view to understand planned meals, logged meals, calorie progress, macros, and health signals. The intended outcome is quick daily orientation.

### 4. Review Progress

The user reviews recent trends for water, steps, sleep, workout minutes, and nutrition progress. The intended outcome is reflection that leads to better planning.

### 5. Manage Subscription

The user sees premium gates, subscription status, and plan options. The intended outcome is clear value exchange for paid features such as more scans or advanced planning.
<br><br>
<img width="433" height="245" alt="Screenshot 2026-05-16 at 09 29 20" src="https://github.com/user-attachments/assets/dffd1913-a018-4f74-a08a-4c15e7bb03e6" />
<br><br>
## Success Metrics

Product success should be evaluated through behavior, retention, and monetization signals.

Potential MVP metrics:

- Activation rate: users who complete setup and create or view a plan.
- First-week retention: users who return after their first planning or logging session.
- Meal logging frequency: logged meals per active user per week.
- Planning engagement: plans generated, edited, or regenerated per user.
- Recipe engagement: searches, filter usage, recipe detail views, and add-to-plan actions.
- Premium intent: paywall views, restore attempts, upgrade taps, and gated-feature attempts.
- Cost health: AI calls, recipe API calls, Firestore usage, and fallback frequency.
- Trust signal: percentage of AI-assisted logs edited before save.

## Go-To-Market Positioning

InsidePlate can be positioned as:

**A practical meal prep and macro tracking app that uses AI to reduce planning and logging effort.**

Differentiators:

- AI-assisted, not AI-dependent.
- Meal planning and tracking in one loop.
- Photo-assisted logging with user review.
- Cost-aware architecture that supports affordable pricing.
- Admin and release tooling built into the product from early stages.
- Indian-market subscription awareness.

## Launch Readiness

InsidePlate is not yet positioned as a full product launch.

Before launch, the priority checklist is:

- Configure pricing.
- Finalize privacy policy, terms, and health disclaimer.
- Confirm recipes scope and attribution strategy.
- Approve production deployment budget and rollback plan.
- Replace local admin data with production-backed sources where needed.

## Roadmap

### Near Term

- Finish release-readiness QA.
- Tighten subscription purchase and restore flows.
- Validate backend security and deploy only approved services.
- Improve recipe filtering with protein and deeper dietary constraints.
- Expand progress insights from static summaries into more actionable coaching.

### Mid Term

- Expand the recipe corpus with attribution-safe sources.
- Connect subscriber management to production RevenueCat and backend data.
- Add billing and usage dashboards from real provider sources.
- Improve plan personalization based on logged behavior.
- Add stronger onboarding for goals, cuisine preferences, allergies, and budget.

### Later

- Support wearable or health-platform integrations.
- Add grocery-list generation.
- Add household or family meal planning.
- Introduce more market-specific recipe packs.
- Explore coaching or expert-reviewed plan templates.

## Product Manager Summary

InsidePlate is a product case study in turning an AI nutrition idea into a structured, launch-aware MVP. The strongest product choices are the focus on a repeatable user loop, cost-aware AI usage, review-before-save trust design, subscription gating, and owner-facing operational tooling.

The project demonstrates product thinking across user segmentation, MVP scoping, pricing constraints, release readiness, metrics, AI risk, and roadmap planning.
<br><br>
<img width="433" height="245" alt="Screenshot 2026-05-16 at 09 29 51" src="https://github.com/user-attachments/assets/0aa50b65-15ea-4ee2-9718-4a4aed6643ea" />
<br><br>
