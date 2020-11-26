# bundling-reexports

Seems like [some people think that a re-export appears in prod bundles](https://twitter.com/iamakulov/status/1331551351214645251).
Even though they appear in development bundles, they will be removed from production bundles.
I re-created to layout shown in the tweet and only imported `Button`.
The final bundle (`dist/index.js`) only contains Button (search for `data-testid`) but no Icon.
