# todo-app-config

This repository contains the configuration files for the Todo app.

Link to the [Todo app code repository](https://github.com/SakuJuuH/todo-app-code.git)

## Deployment

To deploy the Todo app in a staging environment, run:

```shell
kubectl apply -f ./overlays/staging/
```

To deploy in a production environment, run:
```shell
kubectl apply -f ./overlays/production/
```

Note: The application is highly dependent on Google Cloud Artifact Registry, so deploying might not work out of the box.