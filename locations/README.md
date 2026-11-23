# Locations

This directory contains research and documentation relating to individual item-bearing locations (checks) in the Ocarina of Time remake.

Locations represent the specific instances in the game where randomized items may be obtained. This directory aims to establish a comprehensive catalog of these checks, their identities, characteristics, classifications, and verification status.

## Directory Structure

- **[catalog/](catalog/README.md)** – The master catalog of individual locations and their identifying information.
- **[areas/](areas/README.md)** – Documentation and organization of locations by area.
- **[types/](types/README.md)** – Classification of locations by check type.
  
## Scope

Location research may include:

- Identifying individual item-bearing checks.
- Documenting check names and descriptions.
- Establishing the areas in which checks are located.
- Identifying check types and classifications.
- Documenting original rewards, when known.
- Recording conditions or circumstances associated with checks.
- Investigating discrepancies between sources.
- Establishing and documenting location verification status.

## Terminology

**Location:** An individual item-bearing instance in the game that can be collected or checked.

**Check:** Common player-facing terminology referring to a location or the act of collecting its item.

The term *location* is used as the primary organizational and data terminology throughout this repository. The term *check* may be used interchangeably in informal documentation.

## Relationship to Other Domains

- **Logic:** Determines the requirements for accessing or obtaining items at locations.
- **Items:** Defines the items that may be associated with locations.
- **Trackers:** Uses location identities and metadata to represent player progress.
- **Testing:** Verifies location existence, behavior, and associated logic.

## Research Guidelines

When documenting locations:

- Use consistent terminology.
- Distinguish verified information from assumptions.
- Document evidence and references when possible.
- Avoid duplicating canonical location definitions across other directories.
- Report discrepancies and unresolved questions.

## Verification

Location information should be documented with an appropriate verification status when applicable.

See [verification documentation](verification/README.md) when that directory is established.

## Future Development

This directory may eventually contain structured location data suitable for randomizer logic, tracker integrations, validation tools, and other applications.

Formal data schemas and canonical ID conventions should be established after sufficient research has been conducted to identify recurring requirements.
