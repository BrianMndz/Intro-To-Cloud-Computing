# Computing Resources

* Software Based
* Physical servers (Bare metal servers)

## Storage

Bare metal and virtual servers: freed by users.
Block, file and object storage
Object: highly distributed.

### Virtualization and virtual machines

Virtualization: create a virtual version of something.
Hypervisor makes possible virtualization.

Hypervisor: software that runs above the physical resource.

* Type 1: Install directly on top bare-metal.
* Type 2: Layer of host OS (hosted).

VMs run as physical computers independently.

### Benefits

1. Cost savings
2. Agility + speed
3. Low the downtime (move the VM into another hypervisor).

### Types of virtual machines

(Virtual servers, virtual instances o¡r instances).

Shared: multi-tenant: on-demand predefined sizes.
There are custom configurations (cores, ram, storage).

Transients or spot VMs: less costs as there is unused vm resources. Non-production. Testing and development. Running stateless workloads.

Reserved virtual server instances: reserve capacity and guarantee reources for future deployments. Choose a term.

Dedicated hosts: single-tenant. Exclusive use of capacity. Maximum control over workload placement.

### Bare Metal Servers

Single-tenant, dedicated to single customer. Customer is responsible for administration. Customers can also install their OSs. Add GPUs. Bare metal servers are physical machines. More expensive than VMs. Demanding environments. Dedcated or long-term usage. NO hypervisor required. High-Performance computing: HPC.

* Work best for: CPU and I/O intensive workloads.
* Excel with highest performance and security.
* Strict compliance requirements.
* Offer complete flexibility and control.

### Virtual servers

* Rapidly provisioned.

### Secure Networking in Cloud

Logical instances: Cloud network. vNICs.

Virtual Private Cloud (VPC): subnets. Every subnet is protected. Security groups.
VPN: Virtual Private Network.

Build: set of LOGICAL CONSTRUCTS. ensure high performance applications.

### Containers

Executable unit of software: code and dependencies are contained.
Can run on desktop or cloud.
Linux kernel introduced C groups...

### VMs vs Containers

VM: Host OS / Hypervisor / (OS/LIBS/JS-app) : (OS/LIBS/JS-app_2)
Containers: (manifest: description) -> Image (Docker i.e.) -> Container
    Host OS / Runtime Engine (Docker engine i.e.) / (libs / JS).

Third party services: 3rd party APIs. Shared between all the processes running.

## Cloud Storage

### File storage

Direct atached: attached to a compute node to store data. Less expensive and more resilient to failure. Less disk management. Remote storage appliances.

Physical disks -> Storage Appliances -> Compute node.

Offer encription. Mounter on compute nodes via ethernet networks (dedicated) NFS: Network File Sotage.

IOPS: In/Out Operations Per Second. Low IOPS value can become a bottleneck.

### Block Storage

Breaks files into chunks (or blocks) of data.
Mounted from remote storage. Extremely resilient to failure.

Moiunted as a volume to compute nodes using networks of optical fibres. Speed of light. Workloads that need low-latency. Consistent high speed. IOPS capacity into account.

### Object storage

Application or programin interface. S3 API: offer by AWS.
RESTful API.

### CDN: Content Delivery Networks

CDN: makes website faster, and increases the speed reducing distance. Endpoints.
User not communicating directly with the server thanks to the endpoints.
