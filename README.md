# [Backstage](https://backstage.io)

This is your newly scaffolded Backstage App, Good Luck!

To start the app, run:

```sh
yarn install
yarn dev
```

## Generate Clients

Generate with `npx autorest README.md --tag=petstore`

```yaml $(tag) == 'petstore'
# https://petstore.swagger.io
input-file: https://petstore.swagger.io/v2/swagger.yaml
typescript: true
output-folder: plugins/petstore-client
generate-metadata: false
```