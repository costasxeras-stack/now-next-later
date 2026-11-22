# Case study: Now Next Later

## The question

Roadmaps in portfolios are usually a static picture of boxes and dates. A real roadmap is a set of bets under constraints: a strategy, limited capacity, dependencies, and scores that are only estimates. I wanted a roadmap where those constraints are live, using my own app Spend Lens as the startup, so a reader can see how the plan changes and where judgement overrules the numbers.

## Approach

I wrote the strategy before the backlog, then listed 16 initiatives that serve the three bets plus foundations. Each got a problem statement, a target metric and my estimates. I built the planning rule (score order, capacity, dependencies) and checked how the plan changes under each framework. The most useful output was the place where I disagree with the scores.

## Findings

### 1. Scoring pushes the strategic bet to Later (from my own estimates)

Under RICE, ICE and value divided by effort, with my default estimates and 26 person-weeks a quarter, shared budgets for couples land in Q3 or Q4. Cheap, certain habit work fills Q1. I would pin shared budgets to Next and run interviews first to raise its confidence or drop it.

## Decisions

### Now, Next, Later instead of dates

Dates on a 12-month roadmap for a new product are guesses that turn into promises.

**Decision:** Use three horizons. Only Now has scope. Next and Later show direction and problems.

Full record: [decisions/0001-now-next-later.md](decisions/0001-now-next-later.md)

### Three scoring frameworks side by side

One framework hides its bias. RICE favours reach, ICE ignores it, value and effort ignores confidence.

**Decision:** Let the reader switch and see which items move. Items that move a lot have uncertain inputs.

Full record: [decisions/0002-three-frameworks.md](decisions/0002-three-frameworks.md)

### Capacity and dependencies decide the quarter

A ranked list is not a plan. Plans fail on capacity and order.

**Decision:** Fill each quarter in score order up to capacity, never before dependencies, and flag pinned items that break the order.

Full record: [decisions/0003-capacity-and-deps.md](decisions/0003-capacity-and-deps.md)

### Write down where I overrule the score

The strategic Couples bet scores low because it is big and uncertain.

**Decision:** Keep the scored order for Now, pin the key couples item to Next, and reduce uncertainty with research first.

Full record: [decisions/0004-judgement-over-score.md](decisions/0004-judgement-over-score.md)

## What I learned as a PM

- Scoring frameworks favour small certain work over big strategic bets
- Capacity is the constraint most roadmaps leave out
- Writing the problem and the metric for each item makes weak items obvious

## Limits

- All inputs are estimates
- The fill rule is greedy and does not split work across quarters
- One team, no cross-team dependencies

## What I would do next

1. Replace estimates with data after Spend Lens has [n] users
2. Add confidence ranges and show which items change horizon
3. Link each initiative to a one-page brief

## My role

I framed the problem, made the product calls, checked every number and wrote the conclusions. 
