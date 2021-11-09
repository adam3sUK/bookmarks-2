`As a user
To visit my favorite web pages easily
I would like to see a list of my bookmarks`

# Bookmark domain model

![Uploading Screenshot 2021-11-09 at 10.37.03.png…]()

User-->client:Click "Show bookmarks" button

client-->server:GET "/bookmarks"

server-->client:200 response return "bookmarks.erb"

client-->User:Show formatted HTML "bookmarks.erb"