This is a starter template for [Learn Next.js](https://nextjs.org/learn).

## Learned

### Page Navigation

Using `<Link>` enables client-side rendering. This means that the redirect is done with JS and is therefore faster than the normal browser refresh.

NextJS' Code Splitting allows the browser to only fetch the page needed. When a `<Link>` is in the browser viewport, NextJS automatically prefetches the code for the linked page. By the time you click the link, the code for the destination page will already be loaded in the background, and the page transition will be near-instant!

### Images

NextJS' Image component has integrated image Optimization and Resizing.

### CSS Modules

It automatically creates unique class names so we don't need to worry about class name collisions. Code Splitting is also working for Css Modules, only the minimal amount of CSS is loaded each time.

!!! When adding _app.js, you need to restart the server !!!

### getStaticProps

The method is run server-side and is never sent to client applications.

- In development (npm run dev or yarn dev), getStaticProps runs on every request.
- In production, getStaticProps runs at build time. However, this behavior can be enhanced using the fallback key returned by getStaticPaths


Where was I : https://nextjs.org/learn/basics/dynamic-routes/page-path-external-data
