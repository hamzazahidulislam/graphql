
## Some Query Is here

```bash
query{
  movies(rating:8.5,limit:5){ 
    id
    title
    rating
    medium_cover_image
    language
  }
}
```

## Filter Movie by id
```bash
query{
  movie(id:25506){
    title
    rating
  }
  suggestions(id:25506){
    medium_cover_image
    rating
  }
}
```
