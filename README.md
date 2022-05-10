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



