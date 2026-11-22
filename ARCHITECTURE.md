# MIHU player-warp bot — Architecture

index.js starts the bot and registers commands. commands/ groups handlers by feature. database.js uses Node’s built-in SQLite support and imports existing data/bot-data.json on first launch. The database needs persistent storage.
