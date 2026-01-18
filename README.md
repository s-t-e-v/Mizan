# ⚖️ Mizan

## Project Overview

### Overarching Goal

Design and experiment with an **alternative monetary and financial system** that is **fully compliant with Islamic finance**, breaking away from **riba (interest)** and speculative capitalism, while remaining **secure, functional, and viable** for real economic activity.

The system is based on **mutual credit and risk-sharing**, and aims to promote **productive investment, sane money circulation, and social justice**, within a voluntary community or alliance of companies.

---

## Initial Setup (Simulation First)

Focus on **trade only**.

* 10 agents (people or companies)
* 1 mutual credit ledger (balances always net to zero)

### Each agent has:

* A balance (starts at 0)
* A credit limit (e.g. −100 to +100)
* A simple behavior rule:

  * Buy something randomly
  * Sell something randomly
  * Try to rebalance if too negative

### Questions to observe:

* Do balances oscillate or drift?
* Does one agent accumulate permanently?
* Does circulation slow down?
* What happens if one agent stops contributing?