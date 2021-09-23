---
description: 'Review https://dev.to/sm0ke/react-berry-dashboard-360-degrees-review-4f8p'
---

# React Berry Dashboard



Hello Coders!

This article aims to provide a full review over [Berry Dashboard](https://berrydashboard.io/), an open-source **React Dashboard** designed by CodedThemes on top of `Material-UI`, the most popular React component library. **Berry Dashboard** can be downloaded directly from Github under the MIT license and used for unlimited hobby & commercial projects. For newcomers, `React` is the most popular JS library used to code user interfaces backed by Facebook.

> *Thanks for reading!* - Content provided by **[Admin Dashboards](https://www.admin-dashboards.com)**.

---

- Section #1 - **Berry Dashboard** General Presentation
- Section #2 - **How to compile** from sources
- Section #3 - Pages and Components provided by **Berry**
- Section #4 - **Full-stack** version [Berry React Node JS](https://appseed.us/product/react-node-js-berry-dashboard)

--- 

![Berry React - Login Page](https://dev-to-uploads.s3.amazonaws.com/uploads/articles/zo367tarpfhtk1hr0t0q.png)

---

## #1 - Berry General Presentation

Berry is a creative open-source admin dashboard template build using React and Material-UI library. It is a complete game-changer [React Dashboard](https://dev.to/sm0ke/react-dashboards-open-source-apps-1c7j) Template with an easy and intuitive responsive design as on retina screens or laptops.

---

- [Berry Dashboard](https://berrydashboard.io/) - product page
- [Berry Dashboard](https://github.com/codedthemes/berry-free-react-admin-template) - source code (published on Github)
- [Berry Dashboard](https://berrydashboard.io/free/dashboard/default) - LIVE Demo

---

This free product might be a good choice for your next project based on the modern UI aesthetics, rich set of UI components, modern tooling, and a simple, intuitive codebase structure.  

Berry uses the latest dependencies for React, Material-UI Library, Icons, Apex Charts, React-Redux, React-Router. For a complete snapshot, please access the [package.json](https://github.com/codedthemes/berry-free-react-admin-template/blob/main/package.json) published on Github.

---

## #2 - Compile from sources

Berry dashboard can be compiled and used directly from Github without a registration lock or any other constraint. All we need is a [minimal programming kit](https://docs.appseed.us/content/tutorials/minimal-programming-kit) properly installed in our workstation with all tools accessible in the terminal.

- `Nodejs` - used in Javascript-based products and tools
- `Yarn` - a popular package manager for NodeJS (better than NPM)
- `GIT` - a command-line tool used to download sources from Github
- A modern editor - `VSCode` or `Atom`

Once all tools are up & running we can compile Berry with a few commands typed in the terminal:

---

**Step #1** - Clone Sources from the public repository

```bash
$ git clone https://github.com/codedthemes/berry-free-react-admin-template.git
$ cd -free-react-admin-template
```

---

**Step #2** - Install Modules via NPM (or Yarn)

```bash
$ npm i
// OR
$ yarn 
```

---

**Step #3** - Start for development (with LIVE reload)

```bash
$ npm run start
// OR
$ yarn start
```

**Step #4** - Production build

```bash
$ npm run build
// OR
$ yarn build
```

At this point, we should see `Berry Dashboard` running in the browser:

---

![Berry React - Default Dashboard Page](https://dev-to-uploads.s3.amazonaws.com/uploads/articles/79q8h87ctq6fdwysredj.png)

---

## #3 - Pages and Components
 
The free version of Berry comes with 9 pre-built pages that might be enough even for commercial projects. The existing codebase can be extended with ease by adding new components and pages on top of existing ones - Provided Pages:

- Dashboard: 1 page
- Authentication: Login & Register
- Blank Page: 1 starter
- Utility pages: Typography, Color, Shadow, and Icons

---

![Berry Dashboard - Icons Page.](https://dev-to-uploads.s3.amazonaws.com/uploads/articles/2sccq4nxn1oppmvcd75a.png)

---

![Berry Dashboard - Colors Page.](https://dev-to-uploads.s3.amazonaws.com/uploads/articles/9z5xmu5x9y2izyzgwv5e.png)
 
--- 

> Berry Components - Colors

![Berry React - Primary Colors.](https://dev-to-uploads.s3.amazonaws.com/uploads/articles/py5ky72bdr819obpece7.png)

---

> Berry Components - Tabler Icons

![Berry React - Tabler Icons](https://dev-to-uploads.s3.amazonaws.com/uploads/articles/mx5vu2n8nnlyl0yfomug.png)
 
---

> Berry Components - Shadows

![Berry React - Shadow Components](https://dev-to-uploads.s3.amazonaws.com/uploads/articles/jg7w45opy4hzkvpclqrg.png)

---

## #4 - Berry Full-stack Version

For a complete full-stack experience **Berry Dashboard** can be used with a Node JS API backend (also free). In this section, we will build berry as a full-stack product where the React Interface redirects guest users to authenticate and expose the private pages (dashboard, UI pages, blank page) after a successful sign-in. The sources for both products (frontend and backend) are published on Github under the MIT license.

---

> **[React Node JS Berry](https://appseed.us/product/react-node-js-berry-dashboard) - product page** (full-stack version)

---

The full-stack version of Berry should be compiled in two steps: backend and frontend. Once we have both parts up & running, we can register new users, authenticate and access the private pages. This new version comes with a simple JWT (web tokens) authentication implemented and pre-configured to communicate with the Node JS API.  

---

> Compile & start the [Node JS Backend](https://github.com/app-generator/api-server-nodejs) - Open-source project

![Node JS API Server - Product Logo.](https://dev-to-uploads.s3.amazonaws.com/uploads/articles/zqsmqmisx9npe6yks7g5.png)
 
---

**Step #1** - Clone/download the sources

```bash
$ git clone https://github.com/app-generator/api-server-nodejs.git
$ cd api-server-nodejs
```

---

**Step #2** - Install dependencies via NPM or Yarn

```bash
$ npm i
// OR
$ yarn
```

---

**Step #3** - Run the SQLite migration via `TypeORM`
 
```bash
$ yarn typeorm migration:run
```

---

**Step #4** - Start the API server (development mode)
 
```bash
$ npm run dev
// OR
$ yarn dev
```

The API server will start using the `PORT` specified in `.env` file (default `5000`).

---

> Compile and start [Berry React](https://github.com/app-generator/react-berry-dashboard) (enhanced version)  
 
**Step #1** - Clone/download the sources

```bash
$ git clone https://github.com/app-generator/react-berry-dashboard.git
$ cd react-berry-dashboard
```

---

**Step #2** - Install dependencies via NPM or Yarn

```bash
$ npm i
// OR
$ yarn
```

---

**Step #4** - Start the API server (development mode)
 
```bash
$ npm run start
// OR
$ yarn start
```

Once the UI is up & running, we should see the login page. To pass the login we need to register a new user and authenticate.

---

![Berry React Full-stack - Login Page.](https://dev-to-uploads.s3.amazonaws.com/uploads/articles/7f58q26nf23xbykjl9fd.png)

---

The full-stack version is actively supported through common efforts of `AppSeed` and `CodedThemes`. For more information or support please access the product page: [React Node JS Berry](https://appseed.us/product/react-node-js-berry-dashboard).

---

> Thanks for reading! For more resource, please access:

---

- Free [React Dashboards](https://dev.to/sm0ke/react-dashboards-open-source-apps-1c7j) - a popular article published here on Dev.to
- [Open-Source Admin Dashboards](https://appseed.us/admin-dashboards/open-source) - index provided by AppSeed 


