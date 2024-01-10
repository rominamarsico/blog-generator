# Blog by Mohamad Ramadan

Made by Romina Marsico

## Start local dev server
Run `npm run dev` to start the local development server and see the results at: http://localhost:4321/

## Add a new blog post entry
In this project, you will find the following file structure. Put your new .mdx or .md files inside the blog folder.
The file name will be used as slug. 

```text
├── src/
│   └── content/
│       └── blog/
```

Don't forget to insert the following at the top of your newly created file:

```text
---
title: 'The quick brown fox jumps over the lazy dog'
description: 'Lorem Ipsum'
pubDate: '2023-11-07'
updatedDate: '2023-11-08'
---
```

Title, description and pubDate are required fields. Anything else is optional.

