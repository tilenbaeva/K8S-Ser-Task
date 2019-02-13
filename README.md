# K8S-Service-Task

I have given a task to practice services and etc. in Kubernetes. 
Here is 5 tasks from A to D. Every single yaml file is in separate directory. 

TaskA. Create a Replicaset off of nginx container with 3 replicas.
       Expose Replicaset at port 81, use NodePort service with name "k8-service".
       
TaskB. Create a ReplicationController "nginx-test", expose it with NodePort service. 
       Service should listen on port 80, name of the service has to be "nginx-svc".
      
TaskC. Ensure a single instance of Pod ubuntu is running on each node of the Kubernetes cluster 
       where ubuntu also represents the image name which has to be used. Do not 
       override any taints currently in place. (Use DaemonSets and the name "ubuntu=dns")
       as DaemonSet name.
       
TaskD. Check to see how many nodes are ready (not including nodes tainted NoSchedule)

TaskE. Create a ReplicaSet as follows:
       * Name: nginx-dns
       * Exposed via a service: nginx-dns
       * Ensure that the service & pod are accessible via their respective DNS records
       * The container(s) within any Pod(s) running as a p[art of this ReplicaSet should use the nginx image. 
       Next, use the utility nsllokup to look up the DNS resocrds of the service & pod and write the output
       to service-dns.tc\xt and pod-dns.txt respectively.
       
       
