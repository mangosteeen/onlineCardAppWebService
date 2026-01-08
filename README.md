Routes

GET /allcards

Retrieve all card records from the database.

{
  "movie_title": "Interstellar",
  "poster_url": "https://example.com/interstellar.jpg"
}

POST /addcard

Add a new card to the database.

[
  {
    "id": 1,
    "movie_title": "Interstellar",
    "poster_url": "https://example.com/interstellar.jpg"
  }
]
