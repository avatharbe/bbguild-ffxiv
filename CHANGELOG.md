# Changelog

## 2.0.0-a1 02/03/2026
  - [NEW] Initial release as standalone phpBB extension
  - [NEW] Extracted from bbGuild core as part of the game plugin architecture
  - [NEW] Implements `game_provider_interface` — registers FFXIV with bbGuild via tagged services
  - [NEW] `ffxiv_installer` extends `abstract_game_install` with clean array-based table names
  - [NEW] `ffxiv_provider` supplies game metadata (Grand Companies, Lodestone URLs)
  - [CHG] Installer uses `$this->table()` helper instead of direct property access
  - [NOTE] Data covers A Realm Reborn — Heavensward/Stormblood/Shadowbringers/Endwalker/Dawntrail content planned
  - [NEW] Game images served from plugin directory
