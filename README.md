# [Backstage](https://backstage.io)

This is an example app that bundles the mta plugin in it.
The mta info can be seen as a tab inside the app component.

## Installation

Checkout the main branch from the repo

## Configuration

In the configuration file [app-config.yaml](app-config.yaml) you need to configure MTA url and the MTA token.

## Running the app

The app requires a backstage front end and backend.
To start the app go to the main directory from a terminal and run:

```sh
yarn install
yarn start
```

In addition, To start the backend go to the main directory from another terminal and run:

```sh
yarn workspace backend start
```

To access backstage ui go to http://localhost:3000/

Press the create button.
Press the Register Existing Component button.
Go through the wizard:
In the select URL input: https://github.com/tmihalac/my-app/blob/main/catalog-info.yaml
Press import and View Component button.
Go to the MTA tab to see the MTA info.

