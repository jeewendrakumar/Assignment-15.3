# Assignment-15.3

Write a GraphQL query to fetch last 20 records of Book

{
  bookStore {
    books(last: 20) {
      edges {
        cursor
        node {
          id
          title
        }
      }
    }
  }
}
