# Trackers

This directory contains research and documentation relating to item and location trackers for the Ocarina of Time remake randomizer.

Tracker research aims to establish how randomized items, locations, progression, and player state may be represented, displayed, managed, and shared across tracker applications.

## Scope

Tracker research may include:

- Location tracking.
- Item tracking.
- Inventory representation.
- Check status.
- Progress tracking.
- Dungeon tracking.
- Map-based tracking.
- Accessibility information.
- Tracker interfaces.
- Tracker data formats.
- Integrations with other applications.
- Multiworld support, where applicable.

## Directory Structure

- **[data/](data/README.md)** – Tracker-facing data representations and data requirements.
- **[interfaces/](interfaces/README.md)** – Tracker layouts, display conventions, and interaction concepts.
- **[integrations/](integrations/README.md)** – Research relating to tracker interoperability and external integrations.
- **[features/](features/README.md)** – Tracker functionality and feature research.

## Tracker Principles

Tracker research should prioritize consistency, interoperability, and the reuse of shared location and item identities.

Trackers may implement different interfaces or features, but their underlying representations should ideally remain compatible with shared randomizer data.

## Relationship to Other Domains

- **Locations:** Trackers represent individual checks and their collection status.
- **Items:** Trackers represent inventory, item ownership, and progression.
- **Logic:** Trackers may display accessibility or progression information.
- **Data:** Shared data conventions may support interoperability between trackers and other applications.
- **Testing:** Tracker behavior and data compatibility should be validated.

## Research Guidelines

- Document tracker features and behavior.
- Identify data requirements.
- Distinguish tracker-specific functionality from shared data requirements.
- Document external integrations and their limitations.
- Record relevant references and examples.
- Avoid assuming that all tracker implementations share the same architecture.

## Future Development

Tracker research may eventually support shared tracker data, interoperable applications, map-based interfaces, and automated progress tracking.

The repository is intended to document and coordinate research rather than require a single tracker implementation.
