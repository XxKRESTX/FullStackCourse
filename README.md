# FullStackCourse
#0.4

browser->server: HTTP GET https://studies.cs.helsinki.fi/exampleapp/notes
server-->browser: notes
browser->server: HTTP GET https://studies.cs.helsinki.fi/exampleapp/main.css
server-->browser: main.css
browser->server: HTTP GET https://studies.cs.helsinki.fi/exampleapp/main.js
server-->browser: main.js

browser-->server: HTTP GET https://studies.cs.helsinki.fi/exampleapp/data.json
server-->browser: [{content: 'heh', date: '2022-05-09T04:25:43.772Z'}, ...]

#0.5

browser->server: HTTP GET https://studies.cs.helsinki.fi/exampleapp/spa
server-->browser: spa
browser->server: HTTP GET https://studies.cs.helsinki.fi/exampleapp/main.css
server-->browser: main.css
browser->server: HTTP GET https://studies.cs.helsinki.fi/exampleapp/spa.js
server-->browser: spa.js

#0.6

browser->server: HTTP GET https://studies.cs.helsinki.fi/exampleapp/spa
server-->browser: spa
browser->server: HTTP GET https://studies.cs.helsinki.fi/exampleapp/main.css
server-->browser: main.css
browser->server: HTTP GET https://studies.cs.helsinki.fi/exampleapp/spa.js
server-->browser: spa.js

browser-->server: HTTP GET https://studies.cs.helsinki.fi/exampleapp/data.json
server-->browser: [{content: 'heh', date: '2022-05-09T04:25:43.772Z'}, ...]

