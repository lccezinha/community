### Queries

#### All links

```json
query {
  allLinks {
    id,
    description,
    url
  }
}
```

#### Get a link

```json
query {
  getLink(id: 1) {
    url,
    description
  }
}
```

### Mutations

#### Create link

```json
mutation {
  createLink(
    url: "site.com",
    description: "Random"
  ) {
    id,
    description
  }
}
```
