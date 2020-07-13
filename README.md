# ghqlclient

Github Graph Client made with Flutter on Linux.

Did not finish this code lab because I saw the following error when running
`flutter pub run build_runner build --delete-conflicting-outputs`.

```bash
[SEVERE] gql_build:data_builder on lib/third_party/github_graphql_schema/schema.public.graphql (cached):

AssetNotFoundException: github_graphql_client|lib/third_party/github_graphql_schema/schema.public.graphql
[SEVERE] gql_build:data_builder on lib/src/github_gql/github_queries.graphql (cached):

AssetNotFoundException: github_graphql_client|lib/third_party/github_graphql_schema/schema.public.graphql
[SEVERE] gql_build:var_builder on lib/src/github_gql/github_queries.graphql (cached):

AssetNotFoundException: github_graphql_client|lib/third_party/github_graphql_schema/schema.public.graphql
[SEVERE] gql_build:var_builder on lib/third_party/github_graphql_schema/schema.public.graphql (cached):

AssetNotFoundException: github_graphql_client|lib/third_party/github_graphql_schema/schema.public.graphql
[SEVERE] Failed after 36ms
```

The code in this repository is based on the
[Flutter Github Graphql Client](https://codelabs.developers.google.com/codelabs/flutter-github-graphql-client/index.html#0)
tutorial.
