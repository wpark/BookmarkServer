# Bookmark Server

This is a *bookmark server* or URL-shortening service,
similar to `TinyURL.com` or `goo.gl`, but with no persistent storage.

This server accepts a URL and a short name, checks that the URL actually
works (returns an HTTP 200), then store it in a Python dictionary.



