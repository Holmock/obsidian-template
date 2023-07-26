---
creation date: <% tp.file.creation_date() %>
modification date: <% tp.file.last_modified_date("YYYY-MM-DD dddd HH:mm:ss") %>
---

<< [[<% tp.date.now("YYYY-MM-DD", -1) %>]] | [[<% tp.date.now("YYYY-MM-DD", 1) %>]] >>

# <% tp.file.title %>

<% tp.web.daily_quote() %>
