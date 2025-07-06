# API Overview (Simplified)
The MoviesDatabase API lets you:

Search and explore movies, TV shows, and actors

Get detailed info, ratings (like Rotten Tomatoes), trailers, and cast

Filter by quality, genre, or rating

Use pagination, sorting, and personalized recommendations

Fetch streaming links and parental guides

Every response has a results object; paginated endpoints also include page, next, and entries.

# 🔗 Key Endpoints
Endpoint	What It Does
/movie_details.json	Get full info on a movie by ID or title
/search_by_person.json	Find movies by actor or director
/movie_recommendations.json	Get suggested movies based on genre or rating
/streaming_services.json	See where a movie is available to stream legally

Use this for quick 3D movie list:

bash
Copy
Edit
GET https://api.rapidapi.com/your-api-path/list_movies?quality=3D

# 🔐 Authentication
No API key is required — it’s free to use immediately.

# ⚠️ Errors
Code	Meaning
400	Bad request (missing info)
404	Not found (movie/person missing)
500	Server error

# 🚀 Usage Limits
100 requests/minute

10 requests/second

