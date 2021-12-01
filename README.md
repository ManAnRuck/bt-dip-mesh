# GraphQL API Gateway for Bundestag Dip API

### How to dev

```
yarn install
yarn dev
```

visit [http://localhost:4000](http://localhost:4000)

Get `API-Key` from from https://dip.bundestag.de/über-dip/hilfe/api
and add as `api-token` on webinterface to your **REQUEST HEADERS** below the query

example:

```json
{
  "api-token": "YOUR-API-KEY"
}
```
