# Bounty Contract

A simple **bounty escrow contract** written in Cairo for Starknet. This contract allows bounty creators to lock funds, claimers to submit claims, and governance (bounty creators) to approve or reject those claims. Funds are released upon approval, refunded on rejection/cancel/expiry, and events are emitted for each state change.

## Features
- **Create Bounty** – lock funds in escrow.
- **Claim Bounty** – submit a claim for a bounty.
- **Approve / Reject Claim** – governance can decide claim outcomes.
- **Cancel Bounty** – creator can cancel before approval.
- **Get Bounty** – fetch single bounty info.
- **Get All Bounties** – fetch all bounties.
- **Admin Withdrawal** – governance can withdraw in emergencies.
- **Event Logging** – every state change is tracked with events.
