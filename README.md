# Python HTTP Server

A minimal HTTP server built with Python using `asyncio`. This project is designed to be lightweight, extendable, and educational for understanding the internals of HTTP request handling.

## Features

- Support for HTTP methods: `GET`, `POST`, `PUT`, `DELETE`, `PATCH`
- Simple routing system with support for path parameters (e.g., `/hello/:word`)
- Modular handler system using class inheritance
- Built-in request parsing and response generation
- No external dependencies or frameworks

## How to Run

```bash
python -m http.server
```

> the server is will start and listen on http://0.0.0.0:4239

This project is licensed under [GNU GPLv3](LICENSE).

Built with ❤️ by Mohammadreza Aghababei

