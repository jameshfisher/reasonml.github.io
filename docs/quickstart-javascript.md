---
title: Quickstart
---

```sh
npm install -g bs-platform
bsb -init my-first-app -theme basic-reason
```

Then, run it as usual:

```sh
cd my-first-app
npm run start
```

It runs in watch mode, so any changes to files will be picked up and compiled.

At this point, what's left simply follows the familiar JavaScript workflow. For example, with [`node`](https://nodejs.org/en/):

```sh
> node src/Demo.bs.js
Hello, BuckleScript and Reason!
```

That's all!

- Read more about how we compile to JavaScript through our partner project, [BuckleScript](https://bucklescript.github.io).
- Alternatively, **to start a [ReasonReact](//reasonml.github.io/reason-react/docs/en/installation.html) app**, try `bsb -init my-react-app -theme react`.
- Head over to [Editor Setup](global-installation.md) to get the Reason plugin for your favorite editor!
