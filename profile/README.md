## Welcome to the GitHub area for Open Source Components for Integration, Verification and Certification (IVC) of Distributed Simulation Tools!

This repository serves as a central point of contact for open source components aimed at simplifying and standardizing the integration, verification, and certification of distributed simulation tools. Our work is based on internationally recognized standards, particularly the **High Level Architecture (HLA) Standard** ([IEEE 1516.1](https://standards.ieee.org/ieee/1516.1/6688/)) and is supported by the **NATO Modelling & Simulation Group (NMSG)** ([https://nmsg.sto.nato.int](https://nmsg.sto.nato.int)).

**Our focus lies on the following concepts and components:**

### Interoperability Capability Badges

Building upon the HLA standard, we define **interoperability rules** in the form of **"Interoperability Capability Badges"** ([learn more](https://github.com/IVCTool/CapabilityBadges)). Please note that the Interoperability Capability Badge repository is currently under development and will be populated with content in the coming weeks. These badges describe specific interoperable behaviors that can be verified through test cases.

### Test Suites

The **Test Cases** developed to verify the Capability Badges are organized into **Test Suites**. These Test Suites are designed to be used directly within the respective repositories or integrated into our web-based **IVC tool**. For guidance on creating your own Test Cases, please refer to the **IVCT Test Suite Development Tutorial** ([https://github.com/IVCTool/IVCT_TestSuiteDevelopment](https://github.com/IVCTool/IVCT_TestSuiteDevelopment)).

### Integration, Verification and Certification Tool (IVCT)

The **IVCT** ([IVCT_Framework](https://github.com/IVCTool/IVCT_Framework)) is a web-based application that supports the entire IVC process. For deployment according to the **Modelling and Simulation as a Service (MSaaS)** paradigm, a Docker deployment is available in the **IVCT Operation** repository ([https://github.com/IVCTool/IVCT_Operation](https://github.com/IVCTool/IVCT_Operation)). It enables:

* The management of **Compliance Statements** for Systems under Test (SuT).
* The execution of relevant Test Cases based on the Compliance Statements.
* The generation of comprehensive **Compliance Reports**.

**Explore our repositories to learn more about the individual components and their application. We appreciate your interest and contributions!**
