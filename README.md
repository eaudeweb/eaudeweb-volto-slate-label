# Volto Slate Label

## Features

This Volto addon introduces a dynamic hover popup functionality that enhances content interactivity. When a user hovers over specific, pre-defined words or phrases in the text, a small popup appears, displaying additional information, explanations, or related content. This feature is ideal for providing tooltips, quick definitions, or contextual information directly within your Plone/Volto site, improving user experience and engagement.

## Volto version

This addon requires: `@plone/volto >= 18.0.0` (`volto-slate` part of Volto Core).

## Getting started

### Try Volto Slate Label with Docker

      git clone https://github.com/eaudeweb/eaudeweb-volto-slate-label
      cd eaudeweb-volto-slate-label
      make
      make start

Go to http://localhost:3000

### Add Volto Slate Label to your Volto project

1. Make sure you have a [Plone backend](https://plone.org/download) up-and-running at http://localhost:8080/Plone

   ```Bash
   docker compose up backend
   ```

1. Start Volto frontend

- If you already have a volto project, just update `package.json`:

  ```JSON
  "addons": [
      "eaudeweb-volto-slate-label"
  ],

  "dependencies": {
      "eaudeweb-volto-slate-label": "*"
  }
  ```

1. Install new add-ons and restart Volto:

   ```
   yarn
   yarn start
   ```

1. Go to http://localhost:3000

1. Happy editing!
