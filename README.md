# FS-chapter0
## Exercise 0.4
```
browser->server: HTTP POST https://studies.cs.helsinki.fi/exampleapp/new_note
browser->server: HTTP GET https://studies.cs.helsinki.fi/exampleapp/notes
server-->browser: HTML code
browser->server: HTTP GET https://studies.cs.helsinki.fi/exampleapp/main.css
server-->browser: main.css
browser->server: HTTP GET https://studies.cs.helsinki.fi/exampleapp/main.js
server-->browser: main.js

note over browser:
browser starts executing js-code
that requests JSON data from server
end note

browser->server: HTTP GET https://studies.cs.helsinki.fi/exampleapp/data.json
server-->browser: [Object { content: "asad", date: "2022-05-10T08:26:34.036Z" }, ...]

browser->server: HTTP GET https://studies.cs.helsinki.fi/exampleapp/favicon.ico
```
![FS0 4](https://user-images.githubusercontent.com/51020697/167661912-c939f5b3-8a0a-4be9-9892-a328efdaaecb.png)

## Exercise 0.5

```
browser->server: HTTP GET https://studies.cs.helsinki.fi/exampleapp/spa
server-->browser: HTML code
browser->server: HTTP GET https://studies.cs.helsinki.fi/exampleapp/main.css
server-->browser: main.css
browser->server: HTTP GET https://studies.cs.helsinki.fi/exampleapp/spa.js
server-->browser: spa.js

note over browser:
browser starts executing js-code
that requests JSON data from server 
end note

browser->server: HTTP GET https://studies.cs.helsinki.fi/exampleapp/data.json
server-->browser: [Object { content: "1234345", date: "2022-05-10T08:27:12.917Z" }, ...]


browser->server: HTTP GET https://studies.cs.helsinki.fi/exampleapp/favicon.ico
```
![FS0 5](https://user-images.githubusercontent.com/51020697/167664584-2e6af0f6-878e-474f-8383-1afaabb4b8db.png)

## Exercise 0.6

```
browser->server: HTTP POST https://studies.cs.helsinki.fi/exampleapp/new_note_spa
```
![FS0 6](https://user-images.githubusercontent.com/51020697/167665224-83c1e804-d27e-47cd-88a2-07afb93b1377.png)



