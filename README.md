> **Portfolio showcase** — the complete implementation is kept private to protect intellectual property. This public repository intentionally contains documentation only. A live demo or private code review can be provided for a serious project discussion.

# Bacteria Run

2D canvas runner game originally created as an embedded gamification module inside a larger business application.

This repository is an extracted portfolio snapshot focused on the game itself. CRM adapters, company data and account-specific persistence were removed.

## Highlights
- custom TypeScript game loop and physics
- canvas renderer
- multiple stages and obstacle systems
- animated character rigs assembled from separate sprite parts
- water and background animation pipeline
- vehicle and character customization
- shop and menu UI
- graphics-quality modes
- automated tests for movement, collision, level progression and game rules
- Python asset-processing tools

## Structure
- src/game/ — game logic, rendering and UI modules
- public/images/bacteria-run/ — game assets
- tools/ — asset processing utilities

The original version was integrated into a React CRM application, so this snapshot is primarily a code and architecture showcase rather than a turnkey standalone release.

## Usage and licensing

This repository is source-available for portfolio evaluation. You may inspect the code and run an unmodified local copy for evaluation, but commercial use, redistribution, republishing and derivative distribution are not permitted without written permission. See [LICENSE.md](LICENSE.md).

