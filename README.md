# react-hackernews


HackerNews clone built with React, ReactRouter &amp; Redux, with full page server-side rendering

<p align="center">
  <a href="https://react-hacknews-clone.herokuapp.com/" target="_blank" rel="noopener noreferrer">
    <img width="720" alt="react-hackernews" src="https://user-images.githubusercontent.com/8336744/45299799-387bba80-b53f-11e8-8ba1-d2a5b1d9f201.png">
    <br>
    Live Demo
  </a>
</p>

## Features

> Note: in practice, it is unnecessary to code-split for an app of this size (where each async chunk is only a few kilobytes), nor is it optimal to extract an extra CSS file (which is only 1kb) -- they are used simply because this is a demo app showcasing all the supported features. In real apps, you should always measure and optimize based on your actual app constraints.

- Server Side Rendering
  - react + react-router + redux working together
  - Server-side data pre-fetching
  - Client-side state & DOM hydration
  - Automatically inlines CSS used by rendered components only
  - Preload / prefetch resource hints
  - Route-level code splitting
  - custom dynamic title for SEO
- Progressive Web App
  - App manifest
  - Service worker
  - 100/100 Lighthouse score
- Experience
  - Hot-reload in development
  - CSS extraction for production



## Architecture Overview

<img width="973" alt="screen shot 2016-08-11 at 6 06 57 pm" src="https://cloud.githubusercontent.com/assets/499550/17607895/786a415a-5fee-11e6-9c11-45a2cfdf085c.png">

## Build Setup

**Requires Node.js 7+**

```bash
# install dependencies
npm install # or yarn

# serve in dev mode, with hot reload at localhost:4000
yarn dev

# build for production
yarn build

# If you care about node_modules size
yarn run prune

# serve in production mode
yarn start
```

## License

MIT
