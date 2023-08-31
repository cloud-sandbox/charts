# charts

jfrog rt u your-helm-chart-package.tgz helm-local
helm repo add helm-virtual http://10.1.16.114:32775/artifactory/helm-virtual --username admin --password password
helm repo update

    - helm plugin install https://github.com/chartmuseum/helm-push
    - helm repo add --username=${DOCKER_REGISTRY_USER} --password=$(cat "$DOCKER_REGISTRY_PASSWORD") ${HELM_PROJECT} https://${DOCKER_REGISTRY}/chartrepo/${HELM_PROJECT}
    - helm package .
    - helm cm-push . ${HELM_PROJECT}
