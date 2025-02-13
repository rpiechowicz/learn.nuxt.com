---
ogImage:
  props:
    title: Nuxt Tutorial
    excerpt: Hello
    colorMode: dark
    description: An interactive tutorial for learning Nuxt
---

# Welcome to Nuxt Tutorial!

[🚧 Working in Progress](https://github.com/nuxt/learn.nuxt.com#todolist){.text-orange}

This is an interactive tutorial that is composed with guides and challenges to help you learn [Nuxt](https://nuxt.com/docs/) and its concepts step by step.

## What's Nuxt?

Nuxt is a free and [open-source framework](https://github.com/nuxt/nuxt) with an intuitive and extendable way to create type-safe, performant and production-grade full-stack web applications and websites with [Vue.js](https://vuejs.org). Nuxt has no vendor lock-in, allowing you to deploy your application [**everywhere, even on the edge**](https://nuxt.com/blog/nuxt-on-the-edge).

## Getting Started

With this tutorial, we assume you are already familiar with the basic concept of HTML, CSS, JavaScript. Nuxt is a full-stack framework built on top of [Vue](https://vuejs.org), we also include a simple Vue tutorial to help you get started quickly.

Start learning by click the topics below:

::div{.flex.flex-wrap.gap-2}
:content-card{to="/vue/intro" title="Vue Basics" description="If you are not familiar with Vue, we recommend you to learn the basics of Vue first." icon="i-logos-vue"}
:content-card{to="/concepts/intro" title="Nuxt Concepts" description="If you are not familiar with Vue, we recommend you to learn the basics of Vue first." icon="i-logos-nuxt-icon"}
::

## Case Studies

Once you are already familiar the concepts of Vue and Nuxt, we provided some case studies to help you understand how to use Nuxt in real-world applications:

::div{.flex.flex-wrap.gap-2}
:content-card{to="/" wip title="GitHub Profile" description="Build an website to generate custom user profile from GitHub" icon="i-ph-user-circle-duotone"}
:content-card{to="/" wip title="ECommerce" description="Build a basic ECommerce site with product display, cart and login" icon="i-ph-shopping-cart-duotone"}
::

## About This Playground

This playground itself is also built with Nuxt. It uses:

- [WebContainers](https://webcontainers.io/) to create a fully-featured Node.js environment in your browser to run Nuxt dev server.
- [Nuxt Content](https://content.nuxt.com/) to provide content management for the playground.
- [Monaco Editor](https://microsoft.github.io/monaco-editor/) to provide a code editor with syntax highlighting and code completion.
- [Volar](https://github.com/volarjs/volar.js) to provide Vue and TypeScript language support for Monaco Editor.

You can find the [source code on GitHub](https://github.com/nuxt/learn.nuxt.com) to learn more about how this playground is built.
