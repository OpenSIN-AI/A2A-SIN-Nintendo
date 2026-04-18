# A2A-SIN-Nintendo Boundaries

## Role
`A2A-SIN-Nintendo` owns Nintendo platform messaging integration, Switch Online workflows, and Nintendo-specific contracts.

## This repo should own
- Nintendo Switch Online messaging routing, coordination, and automation flows
- Nintendo evidence, recovery, auth, and session handling
- Nintendo contracts used by downstream automation agents
- runbooks tied to Nintendo platform interaction and monitoring

## This repo must not own
- unrelated gaming or social platform logic
- organization SSOT docs or architecture canon
- downstream business logic unrelated to Nintendo ownership

## Hard rules
- Keep changes scoped to Nintendo messaging integration and monitoring.
- Move non-Nintendo behavior back to the repos that own it.
- Keep reusable contracts focused on console chat coordination and monitoring.
