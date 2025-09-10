# github-explorer

Github file explorer and editor built with plain client-side JS. It lets you navigate directories, make edits, add files/folders, and upload multiple files using a text input field and textarea. You need a github API token with repo access which gets stored in localStorage. Additionally, you can pass the `owner` in the querystring. The globe icon opens the file in a new tab using githack. It also has the ability to create, delete, and fork repos.

Integrated ChatGPT assistance feature, which displays a Help dialog when you select a portion of text within the textarea and press F1 or Escape.

Live demo:

https://raw.githack.com/jay23606/github-explorer/master/index.html

![screenshot](screenshot.png)

Uses GitHub REST and GraphQL endpoints:

https://docs.github.com/en/graphql/overview/explorer

https://docs.github.com/en/rest/guides/getting-started-with-the-rest-api
