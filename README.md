# Rosa — Trust-First Digital Rotating Savings

## Overview
Rosa is a trust-first digital platform that formalizes rotating savings groups (ROSCA / susu) by replacing informal coordination with transparency, governance, and accountability.

## Problem
Rotating savings groups are widely used but are often managed through WhatsApp and manual tracking, leading to poor visibility, missed contributions, and stress around payouts.

## Solution
Rosa digitizes group savings while preserving social trust through transparent contribution tracking, trust scores, group governance, and clear payout schedules.

## How It Works
1. Create or join a savings group
2. Define contribution amount, cycle duration, and payout order
3. Members contribute monthly (simulated)
4. Payments automatically update status and group chat
5. Trust scores adjust based on participation
6. Groups vote on decisions; unresolved issues can be escalated

## Architecture
**Frontend:** HTML, CSS, Vanilla JavaScript  
**Logic:** Trust score system, pot calculation, voting logic  
**Data:** In-memory / localStorage  
**Payments:** Simulated Paystack integration

\[
\text{Total Monthly Pot} = \text{Contribution Amount} \times \text{Number of Members}
\]

## Impact
Rosa reduces coordination friction, increases transparency, and enables scalable group savings without replacing the social trust that makes these groups work.

## Tech Stack
HTML • CSS • JavaScript • Paystack (demo)

## Future Work
- Backend services
- Real payment handling
- Advanced trust analytics
