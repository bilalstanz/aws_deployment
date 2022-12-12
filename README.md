# aws_deployment
Contains Kustomize yaml manifests for awx operator &amp; object deployment


kubectl kustomize . | kubectl --kubeconfig <path_to_k3s.yaml>  apply -f -

- re run it twice to install awx after operator is done
