### works with minikube

- Intalling:
  - $ curl -LO https://storage.googleapis.com/minikube/releases/latest/minikube-darwin-arm64
  - $ sudo install minikube-darwin-arm64 /usr/local/bin/minikube

- Cheat Sheets:
  - $ minikube start
  - $ minikube pause
  - $ minikube unpause
  - $ minikube stop
  - $ minikube addons list
  - $ minikube start -p aged --kubernetes-version=v1.26.1
  - $ minikube delete --all

  - $ alias ik="minikube kubectl --"
  - $ minikube kubectl -- get pods -A
