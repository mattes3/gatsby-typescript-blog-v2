# gatsby-typescript-blog
(Originally created by Gatsby starter for creating a blog:

`gatsby new gatsby-typescript-blog https://github.com/gatsbyjs/gatsby-starter-blog#v2`

I renamed `blog-post.js` to `blog-post.tsx` to start developing in Typescript. However, I found two compile time errors that I could not get rid of.

## You'll see the errors here

Open `src/templates/blog-post.tsx` (e.g. with Visual Studio Code) to see these error messages:

![](blog-post-typescript-error.png)

Cmd-click on `Link` to open the Typescript definition file for the `Link` tag, and you'll find another error message:

![](index-d-ts-error.png)
