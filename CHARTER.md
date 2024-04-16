# Platform Runtime Services Task Group Charter

The primary objective of the Platform Runtime Services (PRS) TG is to drive the standardization for various platform services required for interaction between the supervisor software and the firmware. 
This includes Supervisor Binary Interface (SBI), Advanced Configuration and Power Interface (ACPI), Unified Extensible Firmware Interface (UEFI) specifications. While the SBI is a RISC-V only 
specification maintained by the RISC-V community, UEFI & ACPI are cross architecture specifications maintained by external organizations. Any RISC-V related additions merged in the 
UEFI & ACPI specification will be maintained by the UEFI Forum. Some parts of the UEFI & ACPI  specifications may be maintained by the RISC-V community if it was not merged into the standard ACPI/UEFI specifications.
In that case, the standard ACPI/UEFI specifications will cite the content maintained by the RISC-V community.

The TG will continue to be responsible for maintaining the SBI, UEFI, and ACPI specifications and release future revisions. These are non-ISA specifications and will continue to evolve along with the software ecosystem.
The TG will establish a regular communication channel between various working groups such as, but not limited to, confidential computing, secure/measured boot, hypervisors, debug and unified discovery to identify the areas where possible new SBI extension / UEFI protocol / ACPI tables need to be added.

__Roles and Responsibilities:__ 

* Defines a clear process for any TG to propose a new SBI extension
* UEFI/ACPI specification revision will follow the open standard ECR process
* Provides an open collaborative platform to discuss the new specification proposals
* Responsible for Proof of Concent (PoC) completion of the new extensions
* Maintains Supervisor Binary Interface (SBI) and RISC-V specific parts in UEFI/ACPI specifications 
* Release the SBI specification as per the non-ISA policy laid out by RISC-V International
* Request to merge UEFI/ACPI changes as per the ECR process laid out by UEFI Forum
* Coordination with other TGs depending on the SBI/UEFI/ACPI specification release to keep everything in sync.
* Ensure that the new SBI extensions do not introduce any incompatibility while following the calling convention laid out in SBI v1.0 specification.
* Ensure UEFI/ACPI specification changes are acceptable in the open source community.

__Current Goals:__

This section describes the current goals of the PRS TG. This section will be updated after current goals are achieved and new objectives and requirements are defined.

SBI v3.0 specification
* Supervisor Software Event (SSE) extension 
* Firmware Feature (FWFT) extension
* Debug Trigger (DBTR) extension
* Messaging Proxy (MPXY) extension
* Confidential VM (COVE) extensions
  
ACPI specification
* ACPI Platform Error Interfaces (APEI) modifications
* ACPI System Resource Affinity Table (SRAT) modifications
* RISC-V Quality of Service Controllers  (RQSC) Table
* RISC-V IO Mapping Table (RIMT) specification
  
UEFI specification
* UEFI Common Platform Error Record (CPER) modifications
