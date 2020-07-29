# Laeka Blockchain Pet Insurance Product

This project showcases the use of blockchain in pet insurance domain for claim processing and traçability. In this application, we have four participants, namely insurance, validator, Vet service and the pet owner. Furthermore,
each participant will own its own peer node. The insurance peer is the insurance company providing the insurance for the products and it is responsible for processing the claims. Validator peer is responsible for verifying the therapy claims. Vet Service peer is responsible for providint the efficient health care for the pets while pet woner peer join the ecosystem by choosing and can customize his personnal pet Insurance product.

## Application Workflow Diagram
![Workflow](https://github.com/Laeka-Pets/Laeka/blob/Laeka-Pets-patch-1/images/app-arch.PNG)

1. The blockchain operator creates  Kubernetes cluster (<b>32CPU, 32RAM, 3 workers recommended</b>) and an Hyperledger Fabric network.
2. The operator installs and instantiates the smart contract on the network.
3. The Node.js application server uses the Fabric SDK to interact with the deployed network.
4. The React UI uses the Node.js application API to interact and submit transactions to the network.
5. The user interacts with the insurance application web interface to update and query the blockchain ledger and state.



## Featured technologies
* [Hyperledger Fabric v1.4](https://hyperledger-fabric.readthedocs.io) is a platform for distributed ledger solutions, underpinned by a modular architecture that delivers high degrees of confidentiality, resiliency, flexibility, and scalability.
* [Node.js](https://nodejs.org) is an open source, cross-platform JavaScript run-time environment that executes server-side JavaScript code.
* [React](https://reactjs.org/) A declarative, efficient, and flexible JavaScript library for building user interfaces.
* [Docker](https://www.docker.com/) Docker is a computer program that performs operating-system-level virtualization. It was first released in 2013 and is developed by Docker, Inc.
* [Kubernetes](https://kubernetes.io/) Kubernetes (K8s) is an open-source system for automating deployment, scaling, and management of containerized applications.
## How does it work ?

![Global view](https://github.com/Laeka-Pets/Laeka/blob/Laeka-Pets-patch-1/images/Global%20arch.jpg)

![Subscribe process](https://github.com/Laeka-Pets/Laeka/blob/Laeka-Pets-patch-1/images/subscribe%20process.jpg)


![Therapy Process](https://github.com/Laeka-Pets/Laeka/blob/Laeka-Pets-patch-1/images/therapy%20process%20english.jpg)

![Claim Process](https://github.com/Laeka-Pets/Laeka/blob/Laeka-Pets-patch-1/images/Claim%20process.jpg)


## License

