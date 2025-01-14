# volto-slate-label

## Features

![Label Block](https://raw.githubusercontent.com/eea/volto-slate-label/master/docs/slate-label.png)

## Volto version

This addon requires: `@plone/volto >= 18.0.0` (`volto-slate` part of Volto Core).

## Getting started

### Try volto-slate-label with Docker

      git clone https://github.com/eaudeweb/eaudeweb-volto-slate-label
      cd eaudeweb-volto-slate-label
      make
      make start

Go to http://localhost:3000

### Add eaudeweb-volto-slate-label to your Volto project

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
