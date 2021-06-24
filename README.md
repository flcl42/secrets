Part 1 Kubernets

Task is to dockerize and deliver a python3 application with two environments using kubernets.
1. Dockerize the python3 application (server.py, see run-server.sh also)
1. Application consumes two secrets:
   - file via absolute path /secret/secret.txt
   - environment variable SECRET
1. Corresponding files can be taken from secret-files directory
1. SECRET environment variable may just have DEV or PROD as value
1. Create local kubernets cluster and deliver application there
1. Make application locally available at two domains:
   - dev.secrets.local
   - secrets.local


Part 2 Azure - optional

The task should be done using azure devops
1. Register free account at https://dev.azure.com/
1. Clone this repository to Azure Repos
1. Ask me for VPS hosting, install kubernets there
1. Use domains
   - dev.secrets.flcl.me
   - secrets.flcl.me
1. Add two pipelines at Azure, that allow to publish updates of `server.py`