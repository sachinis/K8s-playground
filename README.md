# K8s-playground
Testing k8s yaml files to be used with
$ kubectl apply -f deploy.yaml

1) k8s Yaml files have 4 keywords api-version, kind, metadata and spec

You can get all the supported "kind" values with the following command
$ kubectl api-resources

2) You can get all supported "apiVersion" values with the following command
$ kubectl api-versions

3) To get all the keys that each "kind" supports
$ kubectl explain services --recursive
$ kubectl explain deployment --recursive

to only see spec values
$ kubectl explain services.spec

4) Good kubernetes resource
https://github.com/DeekshithSN/kubernetes
