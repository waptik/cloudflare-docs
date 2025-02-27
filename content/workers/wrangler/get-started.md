---
pcx-content-type: how-to
title: Get started
weight: 1
---

{{<Aside type="note">}}

Wrangler has launched a new version. If you are looking for the Wrangler 1 documentation, you can find it [here](/workers/wrangler/cli-wrangler/install-update/).

{{</Aside>}}

## Get started with Wrangler

`wrangler` is a command line tool for building [Cloudflare Workers](https://workers.cloudflare.com/).

## Quick Start

```bash
npx wrangler init my-worker
# try it out
cd my-worker && npx wrangler dev
# and then publish it
npx wrangler publish
# visit https://my-worker.<your workers subdomain>.workers.dev
```

## Installation

{{<Aside>}}

If you previously had [Wrangler 1](/workers/wrangler/cli-wrangler/) installed globally, uninstall it first by running:

```bash
$ npm uninstall -g @cloudflare/wrangler
```

{{</Aside>}}

Install Wrangler globally:

```bash
$ npm install -g wrangler
```
