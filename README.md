# SvelteKit-Webextension-Template

A starter template to build Svelte powered browser extensions, with a pre-configured SvelteKit build system that lets you get started instantly. Based on the steps in [this article](https://javascript.plainenglish.io/making-a-chrome-extension-with-svelte-2fefb3769c).

## Setup

1. Use this repo as a template and create a new one for your own project.
2. clone a local copy of your created repo
3. Run
``` 
npm install
npm run build
```
4. Load the /build folder as an unpacked extension in chrome from the chrome extension settings page. (You may have to enable chrome developer mode, if you haven't already)
5. The extension should auto update usually. But as a general practise, refresh the extension from Chrome's extensions setings page, each time you run ``` npm build ```
6. Publish to chrome web store once ready, as per the steps in their dev docs.
   

