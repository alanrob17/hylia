---
title: Running the Hylia theme
date: '2021-08-02'
tags:
  - demo-content
  - blog
---

I couldn't get the Hylia theme working on my local server.

I started by trying to run the code that I had with the following command.

```js
  npm start
```

I ended up with an error in my terminal stating that it couldn't find the **dist/404.html** page. I later realised that the real error was that the webpages hadn't been created so I couldn't serve any HTML.

To get around this issue I had to run this command.

```js
  npm run-script production
```

This actually created the content from the markdown files in the **posts** folder.

Once I did this I could run the server.
