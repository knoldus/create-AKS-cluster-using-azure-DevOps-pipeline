# Prerequisites:
* azure DevOps portal.
* Create pool and deploy agent in your local or azure Vm.
* service conncetion or install azure-cli inside your agent.
* terraform code 
   use git-hub repo or clone the repo --> https://github.com/Yogesh0777/terraform-aks 

* and use the starter pipeline.

# Aks cluster

Using tech-hub to create resource group and the AKS cluster to use the script in the azure devops pipeline.
steps:-
 * go to the azure devops pipeline
 * add the git hub repo
 * use starter pipeline
 * add the pipeline script and yaml 
 * and add the agent pool in the pipeline yaml.
   ex. pool: Default 
 * save and run.
 * see the logs inside the agent, pipeline successful or not

AKS cluster is cretaed inside the azure portal.