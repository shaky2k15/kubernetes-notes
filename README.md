# kubernetes-notes
Collection of all kubernetes related links , tools and notes 

### Installation and Setup
+ Mac
	+ https://matthewpalmer.net/kubernetes-app-developer/articles/guide-install-kubernetes-mac.html
	
### Installation Issue Fixes
+ If you encounter this error "Cannot bind to some ports due to permission denied" then apply command
 `sudo -E kubectl port-forward  sa-frontend 88:80`
 
 
 ### Useful commands
+ To check the profile :
 `minikube profile list`
 + To start minikube with desired vm :
 `minikube start --vm-driver=virtualbox` (During testing observed it picks up hyperkit vm by default)
 
 ### Documentation
 + Docs: https://minikube.sigs.k8s.io/docs/start/
