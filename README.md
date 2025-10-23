# Pando

> _“In the pursuit of knowledge, every day something is added. In the pursuit of wisdom, every day something is dropped.”_ — Lao Tzu

## Much Ado About Nothing

This is a project about nothing. But nothing is something.

Clarity comes not in the presence of something, but in the absence of it. That’s why we say “crystal clear” — a crystal is transparent because there’s _nothing_ clouding it.

This project is also called _De nada_ — which literally translates to “it’s nothing,” though we use it to say “you’re welcome.” A gift to myself, and potentially to others.

## The Hypothesis

After 25+ years working on and for the web, I believe:

### 99% of any web-based business is the same

The parts beneath the surface — accounts, content systems, payments, media delivery, data models — are largely interchangeable, regardless of brand or category.

Whether you’re building e-commerce with shopping carts and payment systems, content management systems with editorial workflows, or modern AI-enabled tools for desk workers, the underlying architecture is fundamentally identical.

### Most digital innovation is rearrangement

From e-commerce to AI tooling, every technological era repackages the same underlying architecture for a new audience. New terms emerge — “agents,” “agentic,” “automation” — but beneath the buzzwords, it’s often just traditional software in new packaging.

### A shared core can unify it all

If the web’s primitives are the same, then each project should stem from a single, extensible root — a living system that adapts, not rebuilds.

### That’s what Pando is

A framework to prove the shared core theory, where every product or service can sprout from the same organism yet evolve on its own.

Named after [Pando](<https://en.wikipedia.org/wiki/Pando_(tree)>), the massive aspen grove in Utah — a single organism with thousands of genetically identical trees sharing one root system, spanning over 100 acres and estimated to be thousands of years old.

## Structure

This monorepo contains interconnected projects that share a common foundation:

- **aspen** — Core framework and shared primitives
- **highwest** — Web application suite
- **jenapps** — Application collection
- **nothing-cli** — Command-line interface tools
- **nothing-static** — Static site generation and delivery

Each project is a submodule that can evolve independently while remaining connected to the shared root.

## Philosophy

The goal is to solve for the 99% — to create an extensible common core that eliminates redundant rebuilding while allowing each project to grow in its own direction.

It’s about stripping away until only the essential remains.

It’s about doing less to achieve more.

It’s about nothing, and everything.

## Getting Started

Clone this repository with all submodules:

```bash
git clone --recurse-submodules git@github.com:mattborn/pando.git
```

Or if you’ve already cloned it:

```bash
git submodule update --init --recursive
```

## License

MIT
