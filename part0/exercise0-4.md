```mermaid
  sequenceDiagram
    participant browser
    broser->>server: POST https://studies.cs.helsinki.fi/exampleapp/new_note
activate server
server-->>browser: HTTP status code 302: URL redirect
```
