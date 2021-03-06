---
layout: guide
title: Introduction
---

{::options toc_levels="1..3" /}
* ToC
{:toc}

## What is LitElement?

LitElement is a simple base class for creating fast, lightweight web components that work in any web page with any framework.

LitElement uses [lit-html](https://lit-html.polymer-project.org/) to render into shadow DOM, and adds API to manage properties and attributes. Properties are observed by default, and elements update asynchronously when their properties change. 

To build an app out of LitElement components, check out [PWA Starter Kit](https://pwa-starter-kit.polymer-project.org/).

## Quick start 

Install:

```bash
npm install --save @polymer/lit-element
```

Import:

```js
import { LitElement, html } from '@polymer/lit-element';
```

[Download a sample LitElement project](https://github.com/PolymerLabs/start-lit-element).

## Next steps

* [Getting Started](/guide/start): Set up LitElement and create a component.
* [Templates](/guide/templates): Write templates with lit-html syntax.
* [Properties](/guide/properties): Manage properties and attributes.
* [Lifecycle](/guide/lifecycle): Work with the LitElement lifecycle API.

