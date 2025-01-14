# Volto Slate Label

## Features

This Volto addon introduces a dynamic hover/click popup functionality that enhances content interactivity. When a user hovers over specific, pre-defined words or phrases in the text, a small popup appears, displaying additional information, explanations, or related content. This feature is ideal for providing tooltips, quick definitions, or contextual information directly within your Plone/Volto site, improving user experience and engagement.

## Volto version

This version requires: `@plone/volto >= 16.0.0.alpha.15` (`volto-slate` part of Volto Core).

## Getting started

### Add Volto Slate Label to your Volto project

Make sure you have a [Plone backend](https://plone.org/download) up-and-running at http://localhost:8080/Plone

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
