 # URL Shortener
#
A simple and efficient URL shortener built with Go Fiber and Redis.
#
#

# Features
Shorten long URLs into concise, unique short URLs.
High-performance URL retrieval and redirection.
Custom or random URL generation.
RESTful API for URL shortening and redirection.
#
# Technologies
Go: The main programming language.
Go Fiber: Lightweight, high-performance web framework.
Redis: In-memory database for storing URL mappings.
#
# How It Works
A long URL is submitted to the API.
A short URL (random or custom) is generated.
The short URL is stored in Redis alongside the original URL.
Accessing the short URL redirects the user to the original URL.
