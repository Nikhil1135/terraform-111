check if terraform is installed or not = terraform -- version
https://developer.hashicorp.com/terraform/install?product_intent=terraform

To know which distribution of OS you are using  == cat /etc/os-release

init = It initializes the workspace
      dowmload the required providers.
      downloads modules used in code
      define backend.
      ----------


plan = shows the state of infrastructure and code
       shows what already is created , will be updated and what will delete.



apply =  syncs the code with the infrastructre.
         any changes done with the infrastructure, Apply will update it.


destroy  = To destroy the infrastructure.

validate = To validate the code