# DCA Workshop

Voor de DCA workshop maken we gebruikt van deze [prep guide](https://github.com/DevOps-Academy-Org/dca-prep-guide).
Neem deze goed door aangezien hier precies is aangeven wat je moet kennen en waar die kennis te halen is. Per domein hebben we wat huiswerk wat je vooraf dient te maken wat bestaat uit een of meer labs en wat leesvoer. Tijdens de workshop lichten we vooral de wat onbekendere onderwerpen extra toe aangezien we uitgaan van enige ervaring en de workshop [certificeren](https://success.docker.com/certification) als doel heeft.


## Onderwerpen eerste avond

### Domain 1: Orchestration

Dit domein telt voor 25% mee in het examen maar is een onderdeel wat je als het goed is voor het grootste deel al kent. Doe vooral even het lab en kijk welke onderwerpen uit de prep guide je kan meenemen tijdens het lab.

Leesvoer: [Prep Guide](https://github.com/DevOps-Academy-Org/dca-prep-guide#domain-1-orchestration-25-of-exam)

Lab: [Swarm Mode Introduction for IT Pros](https://training.play-with-docker.com/ops-s1-swarm-intro/)

### Domain 2: Image Creation, Management, and Registry

Dit domein telt voor 20% mee in het examen maar is een onderdeel wat je als het goed is voor het grootste deel al kent. Nieuwe onderwerpen:

- Modify an image to a single layer
- Deploy a registry
- Configue a registry
- Sign an image in a registry (Docker Content Trust)

Leesvoer: [Prep Guide](https://github.com/DevOps-Academy-Org/dca-prep-guide#domain-2-image-creation-management-and-registry-20-of-exam)

Lab: Geen

### Domain 3: Installation and Configuration

Dit domein telt voor 15% mee in het examen en bevat een aantal zaken die je al eerder hebt gezien in Domain in. Nieuwe onderwerpen zijn de EE onderdelen Docker EE Engine, UCP en DTR. Omdat we op dit moment niet beschikken over een bruikbare licentie kunnen we geen lab ontwikkelen voor de Engine. Dit betekend domweg leren van de prep guide. UCP en DTR zijn te installeren op een eigen omgeving. De Docker for Desktop (Mac/Win) is standaard niet echt geschikt dus is het beter om een eigen omgeving op te spinnen op bijvoorbeeld AWS of Digital Ocean. Er is eventueel ook een kleine demo setup beschikbaar.

## Onderwerpen tweede avond

### Domain 4: Networking

Dit domain telt voor 15% mee. Een aantal items zullen bekend zijn, maar ook een aantal niet.

Nieuwe onderwerpen (niet behandelt in de lab)
- Describe the different types and use cases for the built-in network drivers
- Understand the Container Network Model and how it interfaces with the Docker engine and network and IPAM drivers
- Use Docker to load balance HTTP HTTPs traffic to an application
- Understand and describe the types of traffic that flow between the Docker engine registry and UCP controllers
- Describe the difference between host and ingress port publishing mode

Leesvoer: [Prep-Guide](https://github.com/DevOps-Academy-Org/dca-prep-guide#domain-4-networking-15-of-exam)

Lab: [Docker Networking Hands-on Lab](https://training.play-with-docker.com/docker-networking-hol/)


### Domain 5: Security

Dit domain telt voor 15% mee. Er is geen lab en als je nog geen ervaring met UCP hebt, dan zal het meeste nieuw voor je zijn.

Ze hebben de security onderwerpen in kleine stukjes verdeeld, zodat het een volwaardig domein lijkt. Dat valt allemaal reuze mee. Dit zijn de interessante punten om te bespreken:

- Describe the process of signing an image
- Configure RBAC in UCP
- Demonstrate creation of UCP client bundles
- Describe default engine security

Leesvoer: [Prep-Guide](https://github.com/DevOps-Academy-Org/dca-prep-guide#domain-5-security-15-of-exam)

Lab: Geen


### domain 6: Storage and Volumes

Dit domain telt voor 10% mee. Er is een lab over volumes, maar die is erg basic en dekt eigenlijk alleen `Describe how volumes are used with Docker for persistent storage` van de perp-guide. De docker docs over de `devicemapper` zijn opzich ook een lab die je kan doen.

Van de andere items zijn dit de meest interessante om te bespreken:

- Compare object storage to block storage and explain which one is preferable when available
- Describe how volumes are used with Docker for persistent storage
- Identify the steps you would take to clean up unused images on a filesystem also on DTR


Leesvoer: [Prep-Guide](https://github.com/DevOps-Academy-Org/dca-prep-guide#domain-6-storage-and-volumes-10-of-exam)

Lab:
- [Docker Volumes](https://training.play-with-docker.com/docker-volumes/)
- [Configure devicemapper (on CentOS)](https://github.com/DevOps-Academy-Org/dca-prep-guide/blob/master/Domain_6_Storage_and_Volumes/Demonstrate_how_to_configure_devicemapper.md)
