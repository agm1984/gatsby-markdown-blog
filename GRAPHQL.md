# GraphQL Example Queries

> All files

``` graphql
{
  allFile {
    edges {
      node {
        id
      }
    }
  }
}
```

> All posts

``` graphql
{
  allMarkdownRemark {
    edges {
      node {
        frontmatter {
          title
          path
          date
          author
          _PARENT
          parent
        }
      }
    }
  }
}
```