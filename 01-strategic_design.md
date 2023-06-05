# Strategic Design

## Structure

- Chapter 1
  - patterns
  - company's business domains
    - core
    - generic
    - supporting
- Chapter 2
  - ubiquitous language
- Chapter 3
  - bounded context
- Chapter 4
  - Interaction between teams

## Analyzing Business Domains

### Business domain

- The service the company provide to its clients
- Can operate multiple domains
- Could change over time

### Subdomain

- What is
  - Achieve domain's goals and targets
  - Fine-grained area of business activity
  - Multiple subdomains to provide service
  - Company departments
  - Organizational Units
  - Technical
    - interralated use cases

- Types
  - Core
    - Differently from its competitor
    - Complexity and rate of changes
      - complex
      - entry barriers
        - hard to copy
      - change
        - innovation
        - new features
        - ROI
        - ahead competitors
    - Implementation concerns
      - in house
      - unwise to outsource
      - stategic investment
        - i.e: unmaintainable codebase
      - Technical
        - Maintainability
        - Evolution
        - Advanced engenieering techniques
    - Nature
      - Not necessarily technical
  - Generic
    - complex
    - hard to implement
    - Not competitive edge
    - No innovation needed
    - All companies same way
    - Implementation concerns
      - already solved problems
  - Supporting
    - support company's core business
    - Complexity and rate of changes
      - simple
        - ETL
        - CRUD
      - do not change often
      - no businees value in evolving
    - Implementation concerns
      - no ready-made
      - implement subdomains itself
      - no highly skills engenieering
      - outsourcing

### Domain experts

- Who are
  - Knowledge of inticacies of business
  - knowledge authorities in subdomain
  - represent the business
  - business problems
  - Neither analysts that gater requierements nor engenieers designing system
  - People with requirements
  - End users
  - Scopes
    - Whole business
    - Specific subdomain
  