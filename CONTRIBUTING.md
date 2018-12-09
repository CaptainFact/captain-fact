# Repositories

- [captain-fact-api](https://github.com/CaptainFact/captain-fact-api): Elixir / Phoenix / Absinthe backend
- [captain-fact-frontend](https://github.com/CaptainFact/captain-fact-frontend): React frontend
- [captain-fact-extension](https://github.com/CaptainFact/captain-fact-extension): Browser extension, built with React and WebExtensions
- [captain-fact-overlay-injector](https://github.com/CaptainFact/captain-fact-injector): Video overlay injector, built with Preact

# Getting started

To setup the dev environment, please refer to the different repositories instructions
from their `README.md`. The general rule here is:

- You don't need to clone the API to work on the frontend, there's a `docker-compose.yml` ready.

- All projects are configured with smart defaults so you can start all of them
  on your local machine and they will behave properly.

# About code contributions

- Code must be formatted, either with `mix.format` for the API or using prettier
  for npm projects.

- We value clear commits messages, clear branches names, detailed pull requests

- Want to help but don't know where to start with? Look for the
  [`good first issue`](https://github.com/CaptainFact/captain-fact/issues?q=is%3Aopen+is%3Aissue+label%3A%22good+first+issue%22)
  label.
