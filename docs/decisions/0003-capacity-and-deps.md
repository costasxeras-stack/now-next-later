# 0003: Capacity and dependencies decide the quarter

**Status:** accepted, 0.1.0

## Context

A ranked list is not a plan. Plans fail on capacity and order.

## Decision

Fill each quarter in score order up to capacity, never before dependencies, and flag pinned items that break the order.

## Tradeoff

- The fill rule is simple and greedy
- Makes trade-offs visible when something is pinned
