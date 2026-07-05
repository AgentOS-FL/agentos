# AgentOS Engineering Guide

## Mission

AgentOS is the AI Operating System for Real Estate.

The MVP goal is simple:

An operator logs in and immediately knows what to do today.

## Project Lighthouse

Project Lighthouse is AgentOS v0.1.

Core scope:

- Home Workspace
- Ava Morning Brief
- Top Plays
- Business Pulse
- Contact Workspace basics
- Command
- Attention Center

## Engineering Rules

1. Business logic does not live only in the UI.
2. Ava never bypasses Nexus.
3. PostgreSQL is the source of truth.
4. Workspaces do not talk directly to each other.
5. Services communicate through events.
6. Every recommendation must be explainable.
7. Every feature must help create more opportunity.
8. Keep MVP simple.

## Product Standard

Every screen must answer:

- What changed?
- What matters?
- What should I do next?

## First Build Slice

Daily Success Loop:

1. Operator logs in.
2. Home Workspace loads.
3. Ava shows Morning Brief.
4. Top Plays appear.
5. Operator opens a contact.
6. Operator logs communication.
7. Timeline updates.
8. Ava updates future recommendations.
