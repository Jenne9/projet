# OPENCTI - AWS

Pour mon projet de fin d'études, j'ai choisi de déployer la solution OpenCTI sur AWS [(lien)](https://github.com/OpenCTI-Platform/opencti). C'est une plateform de Cyber Threat Intelligence qui aide les entreprises à se renseigner sur les menaces et à s’en protéger efficacement.

Pour ce faire, j'ai d'abord créé des rôles et des politiques sur AWS. Ensuite, j'ai automatisé la création de VPC, de groupes de sécurité, de sous-réseaux, de tables de routage et de passerelles, ainsi que la mise en place du cluster avec le service EKS d'AWS.

J'ai utilisé Kubernetes et Helm pour le déploiement. J'ai également mis en place un contrôleur Ingress Nginx, configuré le DNS avec Route 53, et installé Cert-Manager pour la création automatique de certificats TLS. Enfin, j'ai implémenté le monitoring et la supervision des services avec la stack Grafana Prometheus. 

Le tout a été automatisé à l'aide d'Ansible.

# OPENCTI - AWS

For my final year project, I chose to deploy the OpenCTI solution on AWS [(link)](https://github.com/OpenCTI-Platform/opencti). It is a Cyber Threat Intelligence platform that helps companies gather information about threats and protect themselves effectively.

To accomplish this, I first created roles and policies on AWS. Then, I automated the creation of VPCs, security groups, subnets, routing tables, and gateways, as well as the setup of the cluster using AWS EKS.

I used Kubernetes and Helm for the deployment. Additionally, I implemented an Nginx Ingress controller, configured DNS with Route 53, and installed Cert-Manager for automatic TLS certificate creation. Finally, I set up monitoring and service supervision using the Grafana Prometheus stack. 

All of this was automated using Ansible.
