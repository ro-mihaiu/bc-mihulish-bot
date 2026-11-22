# MIHU player-warp bot — Product requirements

Community members use Discord commands for verification, rewards and shop interactions. Staff can run moderation commands. Persistent records need to survive restarts and upgrades from the older JSON format.

## Acceptance check

In a test guild, check one member action and a restricted staff action. For a storage change, reopen a disposable database and compare the saved record.
