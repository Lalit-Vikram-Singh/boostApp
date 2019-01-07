# Spinnaker pipeline definition 

This pipeline definition contains two stages first jenkinsjob and second deploy. 
Pipeline file contains a JSON, change 'PLACEHOLDER' string with an appropriate value according to your environment 


example

"account": "PLACEHOLDER"   --    "account": "my-k8s-account"
"account": "PLACEHOLDER"   --    "account": "opsmx-docker-registry"
"imageId": "PLACEHOLDER"   --    "imageId": "index.docker.io/opsmx11/restapp:boostapp"
"registry": "PLACEHOLDER"  --    "registry": "index.docker.io"
"tag": "PLACEHOLDER"       --    "tag": "boostapp"
"name": "PLACEHOLDER"      --    "name": "opsmx11-restapp"
"job": "PLACEHOLDER"       --    "job": "restApp_withdatadog"
"master": "PLACEHOLDER"    --    "master": "my-jenkins-master"
