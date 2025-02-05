# A link list for everything I think cool, useful and easy forget >o< .
Can't remember everything.

## A Comprehensive Guide to Font Loading Strategies
- https://www.zachleat.com/web/comprehensive-webfonts/
- load font strategy. very detail. 

## puppeteer-webperf
- https://github.com/addyosmani/puppeteer-webperf
- `puppeteer` web perf testing, lot of examples.

## The most accurate way to schedule a function in a web browser
- https://medium.com/teads-engineering/the-most-accurate-way-to-schedule-a-function-in-a-web-browser-eadcd164da12
- excellent study for `setTimeout`, `requestAnimationFrame`, `worker`
- tl;tr
    - The `setTimeout` function is okay, but overall, for a 250ms theoretical timeout, the real/effective timeout value ranges from 251ms to 1.66+s.
    - As of October 2020, the most accurate way of scheduling a function/callback is using the `setTimeout` function in a `Web Worker`, in a cross-origin iframe.
    - The `requestAnimationFrame` function is the **least accurate** and requires to be inside the viewport, otherwise the real timeout can go up to several seconds, or even minutes.

## monaco-editor
- https://github.com/Microsoft/monaco-editor
- A browser based code editor which powers VS Code

## bestofjs
- https://bestofjs.org/
- javascript library collection

## pure css background 
- https://www.magicpattern.design/tools/css-backgrounds
- beautiful css background examples

## microsoft language Term translation
- https://www.microsoft.com/zh-tw/language/Search?&searchTerm=iterator&langID=129&Source=true&productid=0

## markdown-here
- https://github.com/adam-p/markdown-here
- `markdown`, `extension`, Google Chrome, Firefox, and Thunderbird extension that lets you write email in Markdown and render it before sending.

## material web-components
- https://github.com/material-components/material-components-web-components

## tweakpane
- https://github.com/cocopon/tweakpane
- `control panel`, Compact GUI for fine-tuning parameters and monitoring value changes 
- demo: https://cocopon.github.io/tweakpane/
- react: https://github.com/pmndrs/use-tweaks

## prosemirror
- New York Time's open source `collaborative WYSIWYM editor`
- https://github.com/ProseMirror/prosemirror
  - https://prosemirror.net/docs/guide/
- ref
  - Oak: https://www.youtube.com/watch?v=LEoWPdQh27c
    - backend: firestore as sub/pub, firebase to store something else (simple backend logic, simple architecture)
    - `redux`, `redux-saga`
  - We Built Collaborative Editing for Our Newsroom’s CMS. Here’s How.
    - https://open.nytimes.com/we-built-collaborative-editing-for-our-newsrooms-cms-here-s-how-415618a3ec49
    - more Oak implement detail
  - Building a Text Editor for a Digital-First Newsroom
    - https://open.nytimes.com/building-a-text-editor-for-a-digital-first-newsroom-f1cb8367fc21
  - tiptap
    - https://tiptap.dev/markdown-shortcuts
    - a renderless rich-text editor for Vue.js

## gifshot
- https://github.com/yahoo/gifshot
- `js library`, create animated GIFs from media streams, videos, or images. 

## New York Time's engineer culture & hiring process
- Diversity, Inclusion and Culture: How to Build Great Teams
  - https://open.nytimes.com/diversity-inclusion-and-culture-steps-for-building-great-teams-ca157bd98c07
- Engineers at The New York Times
  - https://open.nytimes.com/how-we-hire-front-end-engineers-at-the-new-york-times-e1294ea8e3f8
- How We Designed Our Front-End Engineer Hiring Process
  - https://open.nytimes.com/how-we-designed-our-front-end-engineer-hiring-process-9b8f20cc31fb
- We’re Making Changes to Our Front-End Engineering Application Process
  - https://open.nytimes.com/were-making-changes-to-our-front-end-engineering-process-abfc9654693d


## Pancake 
- https://github.com/Rich-Harris/pancake
- demo: https://pancake-charts.surge.sh/
- intro: https://dev.to/richharris/a-new-technique-for-making-responsive-javascript-free-charts-gmp
- `chart library`
- charting library for `Svelte`. Pancake is designed with server-side rendering in mind, meaning you can create beautiful responsive charts that may not even need JavaScript to render. Here's how.

## bytemd
- https://github.com/bytedance/bytemd
- `Markdown editor` component built with Svelte. **bytedance** publish. looks high quality. support any framework 
- demo: https://bytedance.github.io/bytemd/

## How to provide your own in-app install experience
- https://web.dev/customize-install/
- `PWA`, javascript to detect PWA status. 
- ref
  - better promotion install PWA: https://web.dev/promote-install/#browser-promotion

## worker
- https://developers.cloudflare.com/workers/
- cloudflare's serverless solution. worker is relay on **V8**, not k8s or container base.
- `serverless`, `kv worker` (key/value store), `JAMstack`, `static site`
- ref
  - https://medium.com/@zackbloom/isolates-are-the-future-of-cloud-computing-cf7ab91c6142
  - https://www.youtube.com/watch?v=HK04UxENH10&list=ULSZUq9n1HTEc&index=417

## blurhash
- https://github.com/woltapp/blurhash
- A very **compact** representation of a **placeholder for an image**.
  - typescript: https://github.com/woltapp/blurhash/tree/master/TypeScript
  - react component: https://woltapp.github.io/react-blurhash/
- other ref:
  - https://jmperezperez.com/medium-image-progressive-loading-placeholder/
  - https://engineering.fb.com/android/the-technology-behind-preview-photos/  fb engineering

## 11ty, Eleventy
-  https://www.11ty.dev/docs/
- Eleventy is a simpler static site generator.

## squoosh
- https://squoosh.app/
  - https://github.com/GoogleChromeLabs/squoosh
  - talk: https://www.youtube.com/watch?v=ipNW6lJHVEs
- `image` compress, resize, `PWA`, `offline`, `WebAssembly` 

## markdown-it
- https://www.npmjs.com/package/markdown-it
- `markdown` `npm` `nodejs`
- A nodejs lib turn content into `html`. Have lots of plugins

## Github markdown **API**
- https://developer.github.com/v3/markdown/
- `markdown` `github`
- github markdown API, turn your content into `markdown` or `GitHub Flavored Markdown (gfm)` format

## github-markdown-css
- https://github.com/sindresorhus/github-markdown-css
- `markdown` `github` `css`
- github's markdown style. If you want code syntax highlighted, use GitHub Flavored Markdown rendered from [GitHub's /markdown API](https://developer.github.com/v3/markdown/).


## micromark
- https://github.com/micromark/micromark
- `markdown`
- the **smallest** commonmark compliant **markdown parser**

## microsoft language
- https://www.microsoft.com/zh-tw/language/Search?&searchTerm=iterator&langID=129&Source=true&productid=0
- technical term `translation` search engine
  - https://www.microsoft.com/zh-tw/language/  <- lots of international guideline

## one line layout (web.dev)
- https://web.dev/one-line-layouts/
- lots of `grid`, `flex` examples (most of them are responsive example) 

## JavaScript counters the hard way - HTTP 203
- https://www.youtube.com/watch?v=MCi6AZMkxcU&list=PLNYkxOF6rcIAKIQFsNbV0JDws_G_bnNo9&index=1

## font load STRATEGIES
- 網頁加載字型Web Font FOIT& FOUT與效能測試: https://medium.com/lucys-design-life/%E7%B6%B2%E9%A0%81%E5%8A%A0%E8%BC%89%E5%AD%97%E5%9E%8Bfoit-fout%E8%88%87%E6%95%88%E8%83%BD%E6%B8%AC%E8%A9%A6-cb0b03daad60
- Font Loading Performance 📉 6 Experiments with FOUT & FOIT: https://www.youtube.com/watch?v=vTf9HRTWKtM
- A COMPREHENSIVE GUIDE TO FONT LOADING STRATEGIES: https://www.zachleat.com/web/comprehensive-webfonts

## localhost use https (and test `__Host-` cookie)
- https://web.dev/when-to-use-local-https/
- https://web.dev/how-to-use-local-https/
  1. 修改 host file ，如 mysite.example 指回 127.0.0.1
  2. 用 mkcert  建 CA
  3. 用 CA 起 https server
  4. Chrome 要調整 #allow-insecure-localhost
  5. 用 mysite.example 來測試
