# Commands used for the task 5

## Diagram

**[Internet]**

   &downarrow;&uparrow;

**[Load Balancer]**

   &downarrow;&uparrow;

**[Firewall / Security Group]**

   &downarrow;&uparrow;

**[Ingress Controller]**

   &downarrow; &uparrow;  

**[Kubernetes Nodes]**

   &downarrow;&uparrow;

**[Kubernetes Pods]**


## Explaination

1. **Loadbalancing:**

   * Setup a loadbalancer to distribute traffic among the nodes.
   * Configure SSL Termination (HTTPS) to ensure encryption

2. **Firewall / Security Group:**

   * Allow traffics on specific ports(e.g 80,443)
   * Configure Web Application Firewall

3. **Ingress Controller:**

   * Deploy an Ingress controller that defines the routing rules for the HTTP webservice with the backend configuration
   * Configure SSL Termination (HTTPS) to ensure encryption
   * Deploy as Deamonset

4. **Kubernetes Nodes:**

   * Deploy Servers as nodes
   * Configure auto-scaling of the nodes

5. **Kubernetes Pods:**

   * Ensure that the deployment has multiple pod replicas
   * Distribute pods across nodes
   * Implement network policies to control pod-to-pod traffic

