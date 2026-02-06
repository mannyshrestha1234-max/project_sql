# Copilot Instructions for project_sql

## Project Overview
**project_sql** is a SQL-based project. This is a newly initialized repository with foundational guidance for AI-assisted development.

## Architecture & Structure
- Project focuses on SQL queries, schemas, and database operations
- Suggested structure (to be populated as project grows):
  - `/migrations/` - Database schema migrations with version control
  - `/queries/` - SQL scripts organized by function (reports, analytics, operations)
  - `/schemas/` - Database table definitions and relationships
  - `/tests/` - SQL testing and data validation scripts
  - `README.md` - Project documentation and setup instructions

## Key Conventions
- **SQL Style**: Use uppercase for SQL keywords (`SELECT`, `FROM`, `WHERE`)
- **File Naming**: Use lowercase with underscores for SQL files (e.g., `user_analysis.sql`)
- **Migrations**: Name migrations with timestamps: `YYYY-MM-DD-HHmmss_description.sql`
- **Comments**: Add meaningful comments for complex queries, especially business logic
- **DRY Principle**: Extract common query patterns into views or stored procedures

## Database Development Workflow
1. Create migrations for schema changes (never modify existing migrations)
2. Write queries in separate files with clear naming
3. Document all table relationships and data dependencies
4. Test queries against realistic data before committing

## Common Tasks
- **Add a new table**: Create migration file in `/migrations/`, then document in schema
- **Write a report**: Create `.sql` file in `/queries/reports/` with query and expected output
- **Modify schema**: Create new migration (never alter existing ones)

## Integration Points
- Currently no external database configured; will be added to project documentation as setup progresses
- Update this file when adding database connections, ETL processes, or external APIs

## Getting Started for AI Agents
- Review the README.md for project-specific setup instructions
- Check `/migrations/` for current schema state
- Examine existing queries in `/queries/` to understand patterns before writing new ones
- Always run migrations in order when setting up new environments
