# alx-graphql-0x00

# Characters — GraphQL Queries (paginated)

This folder contains GraphQL queries to fetch paginated lists of characters from the Rick and Morty GraphQL API.

Each `characters-page-X.graphql` queries the `characters(page: Int)` field and requests the subfields:
- id
- name
- status
- image

Corresponding `characters-page-X-output.json` files should contain the API JSON response for each page.
