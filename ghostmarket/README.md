# GhostMarket: Broker Network v2.4.0

GhostMarket adds a persistent underground contract economy to HackHub. Open the **GhostMarket** desktop app, browse to **ghostmarket.onion**, or browse directly to the separate shopping site at **primewire.shop**.

This build includes the v2.4.0 overhaul: a first-run tutorial, a harsher heat danger curve, a separate **primewire.shop** shopping website, 64 purchasable marketplace items, applications, an admin reset button, a 10,000-rep rank ladder, more upgrades, a hidden admin panel, intel probes, wealth-aware contract stakes, faction standing, completion streaks, critical successes, and a Network screen. It keeps the in-memory session cache so the visible contract board remains stable even if SaveStorage is unavailable.

## Core loop

1. Choose one of six rotating contracts.
2. Select bank payment or a 10% bonus escrow payout.
3. Complete each operation stage with a careful, standard, or aggressive approach.
4. Build intel, protect streaks, and manage faction standing.
5. Manage heat, invest in permanent upgrades, and launder escrow funds back into your bank account.
6. Blow questionable amounts of money on Amazin PrimeWire gear, services, luxury nonsense, and consumables.

## Systems

- **Reputation** unlocks higher-paying, higher-risk contracts.
- **Heat** reduces success odds and decays while you lay low.
- **Heat danger** is nonlinear now: low heat is manageable, but high heat sharply increases failure chance.
- **Tutorial / Guide** explains contract choices, approaches, heat control, escrow, upgrades, PrimeWire, ranks, factions, and reset behavior.
- **Intel probes** can be bought from the board or Network screen to raise intel and reduce heat.
- **Amazin PrimeWire** now has its own website at `primewire.shop`.
- **Amazin PrimeWire** adds eleven marketplace categories: Hardware, Software, Services, Luxury, Consumables, Vehicles, Black Tier, Applications, Home Office, Entertainment, and Oddities.
- **Marketplace purchases** can improve success chance, payout, operation capacity, heat control, laundering fees, refresh speed, intel probe costs, and store discounts.
- **Consumables** can instantly add intel, reduce heat, boost reputation, or raise faction standing.
- **Permanent upgrades** now include ten tracks covering analysts, cleaners, brokers, safehouses, mixers, quartermasters, signal amplifiers, operations rooms, negotiators, and blackbox failovers.
- **Ranks** now climb all the way to 10,000 reputation, ending at Shadow Government Leader.
- **Secret admin panel** unlocks by clicking the GM logo seven times inside GhostMarket.
- **Admin reset** wipes GhostMarket progress without changing your main bank balance.
- **Reset progress** starts the tutorial again automatically.
- **Faction standing** changes as you complete or burn work for each operation category.
- **Wealth profile** raises the ceiling on contract stakes without letting bank balance become infinite payout scaling.
- **Critical successes** improve payout edge and add intel mid-operation.
- **Escrow** grants a 10% payout bonus, but cashing out charges a laundering fee and creates heat.
- **Upgrades** improve success odds, payouts, heat control, job capacity, refresh speed, and laundering fees.
- **GoMail notices** can be enabled from the Escrow screen with any `@gomail.com` address.

## Installation

Copy the `ghostmarket` folder into:

`Hackhub/mods/ghostmarket`

Then restart HackHub and enable the mod if prompted.

## Compatibility

GhostMarket uses its own isolated SaveStorage namespace and does not overwrite base-game quests, files, or other mods. Bank payouts and expenses use HackHub's official Content SDK.

## Recovery

If a bank payout throws an SDK error, GhostMarket leaves the contract active so the final stage can be retried safely.
