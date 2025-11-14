# AI Workshop - OpenEdge ABL Project

This repository contains an OpenEdge ABL project demonstrating modern business entity patterns and UI development.

## Project Structure

- **src/business/** - Business entity classes implementing the Business Entity pattern
  - `CustomerEntity.cls` - Customer business entity with CRUD operations
  - `EntityFactory.cls` - Factory for creating business entities
  - `CustomerDataset.i` - Customer dataset definition

- **src/** - UI windows
  - `CustomerWin.w` - Customer management window
  - `ItemWin.w` - Item management window

- **dump/** - Database schema
  - `sports2000.df` - Sports2000 database schema definition

- **doc/** - Documentation
  - `business-entity-pattern.md` - Business entity pattern documentation

- **.windsurf/** - Windsurf IDE configuration
  - `rules/` - ABL syntax and coding rules
  - `workflows/` - Development workflows

## Database

This project uses the Sports2000 sample database. The schema is provided in `dump/sports2000.df`.

## Build

The project uses Apache Ant for building. See `build.xml` for build configuration.

## Development

This project was created as part of an AI Workshop demonstrating:
- Modern OpenEdge ABL development practices
- Business entity pattern implementation
- UI development with ABL windows
- AI-assisted development workflows
