# Platform Operation Task Ideas

- [Platform Operation Task Ideas](#platform-operation-task-ideas)
	- [Operationial Checklists](#operationial-checklists)
		- [Infrastructure Deployment & Configuration checklist](#infrastructure-deployment--configuration-checklist)
		- [Operational task checklist](#operational-task-checklist)
	- [Testing](#testing)
	- [Certificate & Secret Management](#certificate--secret-management)
	- [Environment Health Observability](#environment-health-observability)
	- [Cost Management](#cost-management)
	- [Security](#security)

- [Certificate & Secret Management](#certificate--secret-management)

- [Environment Health Observability](#environment-health-observability)

- [Cost Management](#cost-management)

- [Security](#security)

## Operationial Checklists
### Infrastructure Deployment & Configuration checklist
- Approach
	- ARM
	- Azure control Plane
- Is the deployment repeatable
- Do we avoid  configuration drift
- Disaster Recovery, can we use this as part of


### Operational task checklist
- Can tasks be automated using runbooks (on demand / scheduled / webhook) of functions
- Is autoschaling configured
- Are AKS scale operations configured ( pod & node )
- Are there gaps in observability
- Is data governance set up
- Can we update configuration settings without rebuilding / redeploying

## Testing
- Different tests & what can we automate, make part of the release
	- Simulation testing
	- Load Testing
	- Stress Testing
	- Resilience testing : can the application recover gracefully from failures
	- Disaster Recovery

## Certificate & Secret Management
- What Certificates & Keys are used
- Where are they used and configured
- When do they expire
- Are the Azure AD Secrets that expire? Who manages this, who is the contact

## Environment Health Observability
What do we require to guarantee health of the environment?
- Health Probes
- Benchmarking 
- What instrumentation do we need
- Can we analyse cross-service

## Cost Management
- Cost Modeling
- Critical Flows are defined
- The right Operational Capabilities are used
	- Capacity
	- Availability
	- Governance
- Operational Cost consideration
- Budgets & Alarms, owners, regular cost reviews, baselines
-

## Security
![Security Layers](media/Platform%20Operations/Pasted%20image%2020220429100947.png)

![Security Checklist](media/Platform%20Operations/Pasted%20image%2020220429101100.png)

