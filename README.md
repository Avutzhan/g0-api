# g0-api
review of power of golang on rest api stuff

### Bookdata-api

run app
```bigquery
$ go run .
```

The App has a few Endpoints

All api endpoints are prefixed with /api/v1

To reach any endpoint use baseurl:8081/api/v1/{endpoint}

```bigquery
Get Books by Author
"/books/authors/{author}" 
Optional query parameter for ratingAbove ratingBelow limit and skip

Get Books by BookName
"/books/book-name/{bookName}"
Optional query parameter for ratingAbove ratingBelow limit and skip


Get Book by ISBN
"/book/isbn/{isbn}"

Delete Book by ISBN
"/book/isbn/{isbn}"

Create New Book
"/book"


```