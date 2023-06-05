# Managing complexity with bounded context

## Inconsistent models

- different meanings in two departments
  - UL has to be consistent
  - DE mental model
  - Prefix
    - Conversations don't use it
  - Bounded context
    - divide UL
    - assign each to specific context
  
## What is

- Single meaning UL
- Model boundaries
  - Applicability of UL

## Scope

- strict applicability context
- define the scope of UL
- dividing domain into smaller problems
- size
  - wider
    - harder to keep consistency
  - smaller
    - more integration

## Bounded Context VS Subdomains

- subdomains
  - types of subdomains
  - part of the business
  - how organization works
- bounded context
  - strategic design decision
  - smaller manageable problems
- interplay
  - subdomains are discovered
  - bounded context are designed

## Physical boundaries

- should be implemented in a separate solution
  - implemented
    - technology stack beneficiary
  - evolved
  - versioned

## Ownership boundaries

- Peacefull consistent of the teams
- No two teams can work on the same bounded context
- Bounded contextjust one team
- Single team own multiple bounded context