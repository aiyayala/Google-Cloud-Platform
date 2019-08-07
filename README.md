# Google-Cloud-Platform
Some Q&amp;A

### How to purchase google cloud service?  
Google cloud platform > menu > market > search WordPress Certified by Bitnami deployment
### Bitnami deploy or google default “click to deploy”? Bitnami. They have customer service to help.
### How to choose a Zone? 
us-east1-d (free tier)
### Our current plan? 8 Core / 16 Thread Intel Xeon-D CPU	30 GB RAM  1 TB SSD Unmetered Bandwidth
Boot disk type? SSD. It is 5 – 10times faster than standard.  Our website is 66GB. We may need 100GB for now.? ??
### Core vs. vCPU? How to choose a Machine type(vCPU)?
-          N1 high-memory machine types have 6.50 GB of system memory per vCPU. https://cloud.google.com/compute/docs/machine-types
-          A vCPU is implemented as a single hardware Hyper-thread on one of the available ( when software tells you how many cores they need they don't take hyper-threading into account , 2 cores means 2 vCPUs. Yes, a single HT CPU core shows up as 2 CPUs to the OS, but does NOT quite perform as 2 truly independent CPU cores.)
-          12:00pm(200 - 300 users) Server Load 5.880371 (16 CPUs) Memory Used 22.3% (6,871,068 of 30,811,596) Swap Used 0% (0 of 0)       (6GB out of 30GB)
-          Conclusion: 8vCPUs 26GB, 150GB SSD (standard)
### Security? Malware and DDos?   
Shielded VM offers verifiable integrity of your Compute Engine VM instances, so you can be confident your instances haven't been compromised by boot- or kernel-level malware or rootkits.            	
### Caches？
Vanish.  https://docs.bitnami.com/oci/apps/wordpress/administration/configure-use-varnish/
### How much we need to pay?   
$219.68 per month estimated   //  WordPress Certified by Bitnami deployment  
### Bitnami customer support? 
Submit a request.Documentation. 
### How to setup database? 
Https requests  0.95 /million     90+ requests in each page
~ 100  
### How to migrate our website?  
1. Set up wordpress https://www.youtube.com/watch?v=uMs01-uNjak&t=623s   
2. https://firstsiteguide.com/change-hosting/  sftp (…)

