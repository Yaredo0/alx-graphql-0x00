
# GraphQL Character Queries

This directory contains GraphQL queries to fetch specific characters from the Rick and Morty GraphQL API.

## Endpoint
https://rickandmortyapi.com/graphql

## Objective
- Fetch a specific character by ID using the `character(id: ID!)` field.
- Include the following fields: `id`, `name`, `status`, `species`, `type`, `gender`.

## Files
- character-id-1.graphql / character-id-1-output.json
- character-id-2.graphql / character-id-2-output.json
- character-id-3.graphql / character-id-3-output.json
- character-id-4.graphql / character-id-4-output.json
## Task 1: Paginated List of Characters

Objective: Fetch a paginated list of characters using the `characters(page: Int)` field.

### Fields
- `id`
- `name`
- `status`
- `image`

### Files
- characters-page-1.graphql / characters-page-1-output.json
- characters-page-2.graphql / characters-page-2-output.json
- characters-page-3.graphql / characters-page-3-output.json
- characters-page-4.graphql / characters-page-4-output.json