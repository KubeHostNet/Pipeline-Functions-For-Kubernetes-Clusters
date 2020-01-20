# Pipeline Functions For Kubernetes Clusters  
  
Pipeline Functions For Kubernetes Clusters is an open-source collection of functions that can be 
integrated with any Pipeline tool to create, update, and destroy Kubernetes clusters created by 
KubeHostNet.  This project is a component of KubeHostNet, which will consume this.  
  
Pipeline Functions For Kubernetes Clusters is comprised of collections of Python Scripts and of 
Python Modules which in turn run Terraform commands on the cloud resources that are created and managed 
by KubeHostNet.  In this way, the code for performing basic tasks can be managed separately 
from your pipeline tool (Jenkins, Bamboo, Electric Flow, CircleCI, etc.) and you can thus more easily 
migrate between Pipeline tools.  
  
These functions and modules are designed to be consumed by elements of KubeHostNet, and thus 
clones of this repository are placed at different points in the code you can download from our other 
repositories.  
  
The primary development of Pipeline Functions For Kubernetes Clusters was done by
[Green River IT, Incorporated](http://greenriverit.com) in California.  It is released 
under the generous license terms defined in the [LICENSE](LICENSE.txt) file.  
  
## Support  
  
If you encounter any problems with this release, please create a 
[GitHub Issue](https://github.com/GreenRiverIT/Pipeline-Functions-For-Kubernetes-Clusters/issues).  
  
For commercial support please send us an email.  
    
## Dependencies  
  
This project is meant to be consumed by KubeHostNet.  
  