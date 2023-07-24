
# SnippetBox

The source code developed while following the book
[Let's Go, 2nd Edition by Alex Edwards](https://www.github.com/octokatherine)

## Deployment

To run this project run

```bash
  go mod tidy
  cd tls
  go run /usr/local/go/src/crypto/tls/generate_cert.go --rsa-bits=2048 --host=localhost
  cd ..
  go run ./cmd/web
```


## Features

- Configuration and error handling
- Database-driven responses
- Dynamic HTML templates
- Middleware
- Advanced routing
- Processing forms
- Stateful HTTP
- Security improvements
- User authentication
- Using request context
- Optional Go features
- Testing

