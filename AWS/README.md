```sh
export AWS_DEFAULT_REGION=""
export AWS_SECRET_ACCESS_KEY=""
export AWS_ACCESS_KEY_ID=""
export NS=""
envsubst < node-explorer.yaml.tmpl | kubectl apply -n $NS -f -
```