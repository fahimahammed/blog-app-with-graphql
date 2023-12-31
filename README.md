# Blog App 

This documentation outlines the functionality and implementation of a GraphQL blog app built using TypeScript, PostgreSQL, and Prisma. The app allows users to create, publish, and view blog posts, manage their profiles, and implement an authentication system.

## Technology: 
- GraphQL (Apollo Server)
- Prisma
- TypeScript

  
## Example Usage

```gql
query {
  posts {
    id
    title
    content
    author {
      id
      name
      email
    }
  }
}
```

```gql
mutation {
  signup(name: "Fahim", email: "fahim@ph.com", password: "123456") {
    token
    userError
  }
}
```
