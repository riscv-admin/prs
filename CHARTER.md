# Platform Runtime Services 2022 Task Group Charter

The primary objective of the Platform Runtime Services(PRS) 2022 TG is to drive the standardization for various platform services required for interaction between the supervisor software and the firmware. This includes Supervisor Binary Interface(SBI), Advanced Configuration and Power Interface(ACPI), Unified Extensible Firmware Interface (UEFI) specifications. While the SBI is a RISC-V only specification maintained by the RISC-V community, UEFI & ACPI are cross architecture specifications.

Any RISC-V related additions merged in the UEFI & ACPI specification will be maintained by the UEFI forum. Some of the changes may be maintained by the RISC-V community if it was not merged into the standard specifications. In that case, the standard specification will contain a hyperlink to actual content maintained by the RISC-V community.

The SBI specification v1.0[1] was ratified earlier in 2022 and is already in use on any platform capable of running a rich OS environment. Similarly, UEFI v2.9, released in March 2021, already supports RISC-V. Apart from that another RISC-V specific UEFI protocol (RISCV_EFI_BOOT_PROTOCOL) was ratified earlier in 2022. It is currently maintained by the RISC-V community[2]. The latest ACPI specification doesn&apos;t support RISC-V yet.

The TG will be responsible to maintain the current specifications and release future revisions in 2022. As these are non-ISA specifications it will continue to evolve along with the software ecosystem.

The TG will establish a regular communication channel between various working groups such as, but not limited to, confidential computing, secure/measured boot, hypervisors, debug and unified discovery to identify the areas where possible new SBI extension / UEFI protocol / ACPI tables need to be added.

The PRS TG will be performing the following tasks:

 * Defines a clear process for any TG to propose a new SBI extension
 * UEFI/ACPI specification revision will follow the open standard ECR process
 * Provides an open collaborative platform to discuss the new specification proposals
 * Responsible for Proof of Concent (PoC) completion of the new extensions
 * Maintains Supervisor Binary Interface (SBI) v1.0 onwards and RISC-V specific parts in UEFI/ACPI specification
 * Release the SBI specification as per the non-ISA policy laid out by RISC-V International
 * Request to merge UEFI/ACPI changes as per the ECR process laid out by UEFI forum
 * Coordination with other TGs depending on the SBI/UEFI/ACPI specification release to keep everything in sync.
 * Ensures that the new SBI extensions do not introduce any incompatibility while following the calling convention laid out in SBI v1.0.
 * Ensures UEFI/ACPI specification changes are acceptable in the open source community (i.e Linux kernel) as well

[1] https://github.com/riscv-non-isa/riscv-sbi-doc

[2] https://github.com/riscv-non-isa/riscv-uefi/blob/main/boot_protocol.adoc
