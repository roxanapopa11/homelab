	# LOGS 
	
	=====
	
	29-08-2024
	
	* Tried to install k3s but was unsuccessful. I think it may have been because I already had minikube installed on my homelab laptop. Maybe I should've looked into completely removing minikube from the system.
	* I also played around the networking configuration and I think I messed something up.
	
	30-08-2024
	
	* Decided to reinstall Ubuntu server on the laptop that I use as a homelab. I think that in the future I'd like to find other ways to fix issues that arise. A fresh install will not be a feasible option in the future when the homelab grows, but it's okay for now.
	* Successfully installed k3s following the steps described here: https://docs.k3s.io/quick-start.
	
	There were some issues with my user (roxana) not having permission to read the /etc/rancher/k3s/k3s.yaml file. I solved this by following the steps from here: https://devops.stackexchange.com/questions/16013/k3s-the-connection-to-the-server-localhost8080-was-refused-did-you-specify-t
	
	* I'm still not sure whether I must use a static IP address for my homelab or not, seeing that things look like they are working fine and I am able to ssh into the homelab. This is something that I need to research.