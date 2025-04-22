Components of the Maestro Scalable Platform
- Maestro Hyperscale Orchestrator (MHO)
	- Central component of a Maestro solution.
	- Acts as a load balancer and network switch.
- Security Gateway Modules (SGMs)
	- Dedicated security appliances.
	- Combine the translation capabilities of Gateways and the security functions of next-generation firewalls (NGFWs).
- Security Group (SG)
	- Set of network interfaces and individual SGMs assigned to a logical group.
	- Form an active/active cluster that is segregated from other SGs.
	- Essentially responsible for the firewall processing all traffic.
- Single Management Object (SMO) in SmartConsole
	- Consists of individual security appliances that work together with traffic load shared between them.
	- Represents individual members of a cluster as a single cluster object.

