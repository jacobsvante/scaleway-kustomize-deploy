# Scaleway Kustomize Deploy Github Action

Deploy to Scaleway using a Kustomize config.

## Inputs

### secret-key

Scaleway secret key
Required: true

### cluster-id

Scaleway Cluster ID.
Can be retrieved with `scw k8s cluster list name=$CLUSTER_NAME -o template="{{.ID}}"`.
Required: true

### region

Scaleway region (e.g. "fr-par")
Required: true

### docker-namespace

Scaleway Docker registry namespace (e.g. "my-namespace")
Required: true

### kustomization-base-dir

Path to base kustomize directory
Required: true
Default: "kustomize/base"

### kustomization-dir

Path to the kustomize directory to apply / deploy
Required: true

### create-k8s-namespace

Create Kubernetes namespace if it does not exist
Required: true
Default: "true"

### image-name

Docker image name (e.g. `my-app`)
Required: true

### image-tag

Docker image tag to deploy (e.g. `0.9.14`)
Required: true

### age-secret-key

Secret key to decrypt deploy secrets with
Required: false

### encrypted-filename

Filename/subpath inside `kustomization-dir` to a file with age encrypted secrets to decrypt
Required: true
Default:" secrets.env"

### decrypted-filename

Filename/subpath inside `kustomization-dir` to which the age encrypted secrets will be decrypted to
Required: true
Default: "secrets.env.dec"

### create-image-pull-secret

Create an image pull secret named "rg.`$region`.scw.cloud"
Required: true
Default: "true"
