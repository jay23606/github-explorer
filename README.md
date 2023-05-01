# github-explorer

Vanilla JS github file explorer/editor using a text input field and an "up" button to navigate directories and a textarea to make edits.

To add files just type the name of the file you want in the text input field (can also create directories this way).

Also added a feature to upload multiple files.

Requires github API token with repo access to be entered which is stored in localStorage.

Can also pass owner in the querystring, for example: 

index.html?owner=jay23606

index.html?owner=jay23606/chat-gpt-voice/html

The globe icon will open the file up in a new tab using githack (serve the page basically)

Uses GitHub REST and GraphQL endpoints:

https://docs.github.com/en/graphql/overview/explorer

https://docs.github.com/en/rest/guides/getting-started-with-the-rest-api

![screenshot](screenshot.png)
