sequenceDiagram
    participant browser
    participant server

    browser->> server: Post https://studies.cs.helsinki.fi/exampleapp/notes
    actiatve server
    server ->> browser: Saved new note to notes
    deactivate server 
    
