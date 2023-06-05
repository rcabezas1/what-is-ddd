# Context Mapping

- Boundary
  - divides the responsability
  - solve different problems
- Bounded Context
  - Models
    - evolve independently
  - Interact
    - achieve goals
    - touchpoint between bounded context
    - contracts

## Cooperation

- Partnership
  - changes
    - coordinated
    - integration two-way
  - successfull integration
    - collaboration practices
    - high level commitment
    - frecuent sync
  - not good for
    - geographic distributed teams
    - communication challenges
- Shared Kernel
  - contract in a shared library (a.k.a shared kernel)
    - owned and referenced by multiple teams
    - each team can modify
      - can break other teams
        - high level commitment
        - high sync
    - breaks own principle
  - success
    - small
    - limited
    - multiple bounded context in one team

## Customer Suplier

- Relationship
  - Upstream
    - gives
    - suplier
  - Downstream
    - uses
    - consumer
- Types
  - Conformist
    - downstream conforms to the upstream model
    - downstream giveup autonomy
  - Anticorruption layer
    - dowstream doesn't conforms
    - transalation into own needs
    - not to conform
      - downstream bounded context contains core subdomain
      - upstream model is bad or inconvenient
        - legacy systems
      - suplier contratc changes often
  - Open-Host Service
    - protect consumer
      - suplier protect changes
      - best service possible
      - decouples implementation from the public interface
      - expose in an integration-oriented language
      - reverse of anticorruption layer
  - Separate ways
    - not collaboration
    - communication issues
      - hard time collaborating
      - cost effective
      - duplicate functionality
    - generic subdomains
      - duplicating less expensive than collaboration
    - model differences
      - conformist relathionshi not posible
      - ACL more expensive
        - cost-efective
    - avoid
      - core subdomains

## Context Map

- Visual representation
  - integration patterns between a system's bounded context
  - provides
    - High level design
      - overview of the systems
        - components
        - models
    - Communication patterns
      - communication between teams
    - Organization issues
      - insights
        - upstream
        - downstream
        - saparate ways same team
