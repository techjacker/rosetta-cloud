|Component		|AWS VMs on EC2 / ISOs			 |Kubernetes										|Serverless (AWS lambda)    		|
|---------------|--------------------------------|--------------------------------------------------|-----------------------------------|
|Entrypoint     |Load Balancer/nginx ec2 instance|Ingress		 									|API Gateway						|
|IP assignment  |NAT instance in public subnet	 |Pods assigned unique IPs via Overlay Network		|Lambda ARN	assigned to API endpoint|
