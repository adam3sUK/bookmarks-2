`As a user
To visit my favorite web pages easily
I would like to see a list of my bookmarks`

# Bookmark domain model

<img width="1229" alt="Screenshot 2021-11-09 at 10 42 17" src="https://user-images.githubusercontent.com/75947453/140900410-26f585d9-6191-4f89-a9bc-479a378e7d6c.png">

User-->client:Click "Show bookmarks" button

client-->server:GET "/bookmarks"

server-->client:200 response return "bookmarks.erb"

client-->User:Show formatted HTML "bookmarks.erb"