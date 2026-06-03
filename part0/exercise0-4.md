```mermaid
  sequenceDiagram
    participant browser
    participant server
    browser->>server: POST https://studies.cs.helsinki.fi/exampleapp/new_note
activate server
server-->>browser: HTTP status code 302: URL redirect
Note right of browser: server asks browser
to perform new HTTP GET request to /notes
```
