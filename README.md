# vue_card_interactive
Vue+Scss Credit Card

#### Steps:

```
npm install       
```              

```
npm run serve       
```   

```
npm run build

```

```
npm run test:unit
```
## Previewing Locally

The **dist** directory is meant to be served by an HTTP server (unless you've configured publicPath to be a relative value), so it will not work if you open dist/index.html directly over file:// protocol. The easiest way to preview your production build locally is using a Node.js static file server, for example serve:

```node
npm install -g serve
// -s flag means serve it in Single-Page Application mode
// which deals with the routing problem below 
serve -s dist
```
