# Few steps need to follow to deply the application
- Create app namespace
'''bash
$ kubectl create namespace app
'''
- Deploy Jenkin inside app namespace
- Access Jenkins
- Create pipelines using Jenkins file for app1, app2
- Also deploy infra from k8s.yaml
- Deploy nginx using deploy.yaml inside nginx directory