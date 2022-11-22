## ローカルのImageを利用したい場合は以下を行う必要がある
$ kind load docker-image nginx-demo-proxy:latest --name kind

マニフェストに `imagePullPolicy: Never`の追記

## Kind
参考になる: https://kun432.hatenablog.com/entry/local-kubernetes-with-kind

## ingressの作成
以下で行った
https://raw.githubusercontent.com/kubernetes/ingress-nginx/nginx-0.30.0/deploy/static/mandatory.yaml
https://raw.githubusercontent.com/kubernetes/ingress-nginx/nginx-0.30.0/deploy/static/provider/cloud-generic.yaml

