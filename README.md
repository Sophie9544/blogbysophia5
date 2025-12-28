**Introduction to Licensing in Firepower Management Center**

Firepower products FMC come with built in licenses for basic functionality, but some advanced features like threat detection, file control, or URL filtering require separate licenses. While “right to use” licenses are perpetual, service subscriptions need to be renewed periodically.

The type of license Smart or Classic depends on the software running on the device, not the hardware itself. For hardware FMC devices, additional licenses are usually not required, but [Firepower Management Center](https://golicense.net/product-category/cisco-license/security/firewall/fmc/) Virtual requires separate entitlements for each device it manages. In clustered or multi instance environments, each cluster member or security module needs an individual license.

![may photo](https://sdmntprsoutheastus3.oaiusercontent.com/files/00000000-c3e0-720c-b3d9-5ffd3a4e67cb/raw?se=2025-12-28T21%3A28%3A36Z&sp=r&sv=2024-08-04&sr=b&scid=ec71c6ea-1bf9-40b7-919a-c0eba8e1a69d&skoid=f28c0102-4d9d-4950-baf0-4a8e5f6cf9d4&sktid=a48cca56-e6da-484e-a814-9c849652bcb3&skt=2025-12-28T18%3A52%3A03Z&ske=2025-12-29T18%3A52%3A03Z&sks=b&skv=2024-08-04&sig=5HDad/FjF8lAaXnaETpTPPymxq/EqaQEFnKDNhIeIeo%3D)

**Licensing Firepower Threat Defense**

Firepower Threat Defense (FTD) devices use Smart Licensing, which allows centralized management of licenses without tying them to a serial number or product key. Base licenses are included with every device and enable core functions such as routing, switching, high-availability configuration, and clustering. Optional licenses such as Malware, Threat, and URL Filtering provide additional capabilities like intrusion detection, file control, and advanced malware protection. 

Every managed device must have the required licenses for the features it will use, including standby devices in high availability pairs.

**License Management and Updates**

Licenses are managed through Cisco Smart Software Manager, where virtual accounts help organize licenses across regions, departments, or business units. To maintain entitlement, Firepower Management Center communicates periodically with the license authority. In isolated or restricted environments, a Smart Software Satellite server can be used to handle license communication.

Service subscriptions have defined terms, and while base licenses are permanent, renewing feature licenses is necessary to continue using advanced capabilities fully.

