# govuk-frontend-template-spec

A set of Jest unit tests, extracted from [govuk-frontend](https://github.com/alphagov/govuk-frontend), to ensure ports meet the same template tests.

## Usage

`npm install -d govuk-frontend-template-spec`

See https://github.com/penx/govuk-frontend-react and search for `govuk-frontend-template-spec` for more details.

## Where is the code?

If using the GitHub repository, the code is extracted from [govuk-frontend](https://github.com/alphagov/govuk-frontend) by running `npm run build`. This is then included in the bundle when publishing to npm.

## Why?

[govuk-frontend](https://github.com/alphagov/govuk-frontend) provides templates using [nunjucks](https://github.com/mozilla/nunjucks). I'm creating [a set of React components that aim to have feature parity with govuk-frontend](https://github.com/penx/govuk-frontend-react) and wanted to extract the govuk-frontend unit tests to validate this. This may also be useful for ports of the templates to other languages.

Also see:
- https://github.com/alphagov/govuk-frontend/issues/1095
- https://github.com/govuk-react/govuk-react/issues/450
- https://github.com/govuk-react/govuk-react/issues/76
