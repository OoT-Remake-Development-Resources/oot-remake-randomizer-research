# Logic

This directory contains research and documentation relating to the logic systems used to determine accessibility, progression, and item requirements in an Ocarina of Time remake randomizer.

Logic research aims to establish how the game world, items, events, and player capabilities interact to determine which locations are accessible and which progression paths are possible.

## Directory Structure

- **[world/](world/README.md)** – Research relating to world structure, regions, connections, and traversal.
- **[requirements/](requirements/README.md)** – Research relating to the conditions and prerequisites for accessing locations and progressing through the game.

Additional logic categories may be established as research develops.

## Scope

Logic research may include:

- Location access requirements.
- Item requirements and capabilities.
- Region connectivity.
- Entrance and traversal requirements.
- Events and progression dependencies.
- Dungeon progression.
- Optional tricks.
- Glitch-based logic.
- Logic difficulty and rulesets.
- Game completion requirements.

## Logic Principles

Logic documentation should distinguish between observed game behavior and randomizer-specific assumptions or rules.

Research should identify:

- What is required for an action or location to be accessible.
- Whether a requirement is mandatory or optional.
- Relevant items, abilities, events, or conditions.
- Known alternative paths or methods.
- Assumptions and limitations.
- Evidence and verification status.

## Relationship to Other Domains

- **Locations:** Logic determines the requirements associated with individual checks.
- **Items:** Logic uses item capabilities and properties to determine progression.
- **Settings:** Configuration determines which rules or requirements are enabled.
- **Testing:** Logic behavior should be tested against documented scenarios.
- **Trackers:** Tracker applications may use logic information to provide accessibility or progression information.

## Research Guidelines

- Document requirements as clearly and precisely as possible.
- Separate verified behavior from assumptions.
- Record relevant game conditions and testing circumstances.
- Identify alternative methods when applicable.
- Avoid duplicating location and item identities.
- Document unresolved questions and discrepancies.

## Future Development

Logic research may eventually be translated into a formal randomizer logic engine.

The structure and implementation of that engine should remain flexible until sufficient research has established the requirements.
