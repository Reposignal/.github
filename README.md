# Reposignal

**A calm, issue-first way to discover meaningful open-source work.**

Reposignal helps contributors find real work—not noise—and helps maintainers signal intent without pressure, metrics, or performative participation.

It treats issues as **work units**, repositories as **context**, and contributors as **humans**, not stats.

---

## Why Reposignal Exists

Finding meaningful open-source work is harder than it should be.

Most discovery today is driven by:

* Repository popularity
* Stars and forks
* Activity volume

None of these reliably answer the question contributors actually have:

> *“Is there something here I can reasonably work on?”*

Reposignal flips the model.

Issues come first.
Repositories provide context.
Discovery is driven by **what kind of work exists**, not how famous a project is.

---

## What Reposignal Is

Reposignal is:

* **Issue-first**
  Discovery starts from issues, not repositories.

* **Context-aware**
  Issues are surfaced with repository signals such as languages, frameworks, domains, and maintainer intent.

* **Opt-in for maintainers**
  Maintainers explicitly control whether and how their repositories appear.

* **Anonymous-first for contributors**
  Exploration works without login. Preferences are optional. Nothing is tracked.

* **Calm by design**
  No pressure loops. No performance framing. No optimization for engagement.

Reposignal is a **reference surface**, not a requirement.
Use it when it helps. Ignore it when it doesn’t.

---

## What Reposignal Is Not

Reposignal does **not**:

* Rank contributors
* Score performance
* Gamify participation
* Track contribution history
* Optimize for activity or growth
* Judge success or failure

It does not try to “improve” open source.

It tries to make **finding work less stressful**.

---

## For Contributors

Reposignal helps you:

* Discover issues that match your comfort level
* Understand repository context before you click through
* Explore anonymously, at your own pace
* Decide *whether* something is worth your time

You are never measured.
You are never compared.
You are never nudged to “do more”.

---

## For Maintainers

Reposignal lets maintainers:

* Signal which issues are ready for outside contributors
* Pause or disable discovery at any time
* Classify issues without public dashboards
* Keep contribution surfaces intentional

Reposignal respects maintainer boundaries.

If discovery is paused, it stays paused.
If something is off, it stays off.

---

## How the System Works (High Level)

* Maintainers opt repositories into discovery
* Issues can be classified and tagged
* Contributors browse via filters (difficulty, language, domain, etc.)
* All ranking and eligibility logic lives on the backend
* The frontend only reflects system state—nothing is inferred client-side

Reposignal is designed so that **intent flows in one direction**:
maintainers → system → contributors.

---

## Open Source

Reposignal is open source.

The system is split into multiple repositories:

* GitHub App (Probot)
* Backend API
* Frontend web application

Each part is independently auditable and intentionally scoped.

---

## Design Values

Reposignal is built on a few simple principles:

* **Restraint over scale**
* **Clarity over metrics**
* **Signals over noise**
* **Trust over optimization**
* **Humans over systems**

These values are enforced in code, not just copy.

---

## Status

Reposignal is under active development.

Expect iteration, refinement, and removal of features that don’t serve the core goal.

---

If you’re curious, explore the repositories in this organization.
If you’re skeptical, that’s healthy—Reposignal is designed to be optional.

No dashboards.
No pressure.
Just work, when it makes sense.
