Advantages of virtual machines:
-Make computing more efficient
	-Do not need full resources of a single machine
-Using many VM’s on a physical machine helps to reduce stranded capacity
	-VM’s use only what they require 
	-Stranded capacity can be alleviated by using multiple servers, but VM’s provide better isolation than multitasking
-Little lead time between requesting VM and using VM
	-Easy to create VM and then delete VM when task is completed
-VM’s are programmable (API used to create, start, stop, modify and destroy VM’s, can write software to preform functions on large scale, not possible with physical machines)
Advantages of containers:
-Less wasteful with resources
	-Fine-grained level usage, like processes
-Processes in a container are isolated
	-Issues within processes won’t affect other processes
-Very lightweight
	-Do not require entire operating systems
	-Containers are self-contained and own their copy of packages/shared libraries/other supporting files
	-Multiple containers cannot have dependency/version conflicts
-Many containers can coexist on the same machine

Why would you select a physical machine over a VM?
One scenario where you might chose to use a virtual machine rather than a virtual machine is working in a job that prioritizes security and performance. Financial service application may use physical machines over virtual machines because the resources on the machine are more readily available, and it’s more secure (single server contained on secure hardware, and less people using it). 

How would cloud aid microservices?
Cloud computed applications can be built using microservice architecture. Since cloud computing relies on sharing resources and achieving coherence, using microservices which are multiple components that are loosely coupled, makes the most sense. Cloud computing is still relatively new technology, so updating, modifying and changing features is an extremely important part of it. Microservices allows for this to happen. 
Microservices also allows for cloud computing to have collections of independent services. It also allows for easier management of databases, code, and integrations. Microservices allow for breaking up services to perform single functions. The services are able communicate easily with each other via the microservice architecture.
