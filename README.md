# MuK REST OpenAPI Specification
[![Build Status](https://travis-ci.org/muk-it/muk_docs_rest.svg?branch=master)](https://travis-ci.org/muk-it/muk_docs_rest)

## Links

- Documentation(ReDoc): https://muk-it.github.io/muk_docs_rest/
- SwaggerUI: https://muk-it.github.io/muk_docs_rest/swagger-ui/
- Look full spec:
    + JSON https://muk-it.github.io/muk_docs_rest/swagger.json
    + YAML https://muk-it.github.io/muk_docs_rest/swagger.yaml
- Preview spec version for branch `[branch]`: https://muk-it.github.io/muk_docs_rest/preview/[branch]

## Working on specification
### Install

1. Install [Node JS](https://nodejs.org/)
2. Clone repo and `cd`
    + Run `npm install`

### Usage

1. Run `npm start`
2. Checkout console output to see where local server is started. You can use all [links](#links) (except `preview`) by replacing https://muk-it.github.io/muk_docs_rest/ with url from the message: `Server started <url>`
3. Make changes using your favorite editor or `swagger-editor` (look for URL in console output)
4. All changes are immediately propagated to your local server, moreover all documentation pages will be automagically refreshed in a browser after each change
**TIP:** you can open `swagger-editor`, documentation and `swagger-ui` in parallel
5. Once you finish with the changes you can run tests using: `npm test`
