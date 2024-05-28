# client
Central repository for Catalog App helm charts



helm registry login acrarolibotnonprod.azurecr.io

helm package helm

helm push client-1.9.0.tgz oci://acrarolibotnonprod.azurecr.io/helm/client