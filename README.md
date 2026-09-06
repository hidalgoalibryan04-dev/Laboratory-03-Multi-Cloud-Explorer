

### System Information Collected
I launched a KillerCoda Ubuntu playground and used Linux commands to check the server specifications:

- **Operating System:** 
Ubuntu 24.04.4 LTS (Noble Numbat)

text
- **CPU Information:** 
Architecture: x86_64
CPU(s): 1
Model name: Intel Xeon E312xx (Sandy Bridge, IBRS update) @ 2.0GHz

text
- **Memory (RAM):** 
Total: 1.9Gi
Used: 414Mi
Available: 1.5Gi

text
- **Disk Space:** 
Main filesystem (/dev/vda1): Size: 19G, Used: 5.4G, Available: 13G (30% used)

text

### Cloud Migration Options
If this Linux server were migrated to the cloud, the following services could host it:

| **Cloud Provider** | **Service Name** | **Why it fits** |
| :--- | :--- | :--- |
| **AWS** | EC2 (Elastic Compute Cloud) | I can launch a t2.micro or t3.micro instance running Ubuntu 24.04, which provides 1 vCPU and 1-2 GiB of RAM—perfectly matching this server's specs. |
| **Microsoft Azure** | Azure Virtual Machines | I can create a B1s or B1ls VM size with Ubuntu 24.04 LTS, which offers 1 vCPU and 1-2 GiB memory, directly matching the memory and CPU found here. |
| **Google Cloud Platform** | Compute Engine | I can create an e2-micro instance with Ubuntu 24.04 LTS, which provides 1 vCPU and 1 GiB of RAM, fitting these resource requirements exactly. |
