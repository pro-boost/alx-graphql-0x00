GraphQuest: Exploring and Implementing GraphQL

# Characters List by Page

This directory contains GraphQL queries to retrieve paginated lists of characters from the Rick and Morty API.

## Files

- `characters-page-1.graphql`: Query for page 1 of characters
- `characters-page-2.graphql`: Query for page 2 of characters
- `characters-page-3.graphql`: Query for page 3 of characters
- `characters-page-4.graphql`: Query for page 4 of characters
- `characters-page-[1-4]-output.json`: JSON output files containing the query results

## Query Structure

Each query follows this structure:

```graphql
query {
  characters(page: [PAGE_NUMBER]) {
    results {
      id
      name
      status
      image
    }
  }
}
```
