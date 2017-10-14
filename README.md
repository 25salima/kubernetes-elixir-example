# kubernetes-elixir-example
Elixir application into Kubernetes Cluster

### Create project
```
mix phx.new kubernetes-elixir-example --app kubernetes_elixir_example --database postgres --no-brunch --no-html --binary-id
```

### Set up your database configuration
1. copy dev secret template file
```
cp config/dev.secret.exs.example config/dev.secret.exs
```
2. update username and password to authorize your database connection
