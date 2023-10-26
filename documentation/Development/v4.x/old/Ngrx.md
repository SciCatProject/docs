# State Management in Angular

Almost all external requests made by the client (SciCat Frontend) are done so via `NGRX effects` within the state management components.

Loopback within the backend provies a generated SDK that is used by the frontend to define all requests to the API. The SDK folder should not be edited because it will just overwrite it when a new one is generated.

The SDK is updated by running the following in the backend source code root:
`./node_modules/.bin/lb-sdk server/server.js  ../frontend/src/app/shared/sdk`
and this is necessary when making any changes to endpoints in the backend.

[NGRX](https://ngrx.io/) is Redux for Angular and is heavily used in the client to manage state.


