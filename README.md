# minimal-reproduction-helm-values-image-versions

Minimal reproduction git repo for values.yaml used by helm with multiple images in Array 

issue : https://github.com/renovatebot/renovate/issues/15988
discussion: https://github.com/renovatebot/renovate/discussions/15976

Based on values.yaml in https://github.com/prometheus-community/helm-charts/tree/main/charts/kube-prometheus-stack 
which has a list of containers with docker image references
