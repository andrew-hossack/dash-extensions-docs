The `dash-extensions` package can be divided in four main pillars,

* The [`enrich` module](pages/getting-started/enrich), which contains various enriched versions of Dash components
* A number of custom components, e.g. the [`Websocket` component](pages/components/websocket), which enables push notifications and real-time communication
* The [`javascript` module](pages/getting-started/javascript), which contains functionality to ease the interplay between Dash and JavaScript
* The `snippets` module, which contains a collection of utility functions (documentation limited to source code comments)

The `enrich` module enables a number of _transforms_ that add functionality and/or syntactic sugar to Dash. Examples include

* Making it possible to target an `Output` by multiple callbacks via the [MultiplexerTransform](pages/transforms/multiplexer-transform)
* Enabling logging from within Dash callbacks via the [LogTransform](pages/transforms/log-transform)
* Improving app performance via the [ServersideOutputTransform](pages/transforms/serverside-output-transform)

When possible, the usage of transforms and custom Dash components is illustrated via one (or more) code examples with the actual code running below. Hence, it should be possible to copy-paste the code and run it right away.