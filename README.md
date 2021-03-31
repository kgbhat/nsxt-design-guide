# NSX-T version 3.0 Design Guide 

This repository is maintained by the VMware Networking and Security Business Unit.

## Introduction

This document provides guidance and best practices for designing environments that leverage the capabilities of VMware NSX-T®. It is targeted at virtualization and network architects interested in deploying NSX Data Center solutions.

### How to Use This Document and Provide Feedback

This document is organized into several chapters. Chapter 2 to 6 explain the architectural building blocks of NSX-T as a full stack solution, providing a detail functioning of NSX-T components, features and scope.  They also describe components and functionality utilized for security use cases. These chapters lay the groundwork to help understand and implement the design guidance described in the design chapter.

 

The design chapter (Chapter 7) examines detailed use cases of network virtualization and recommendations of either best practices or leading practices based on the type of use case or design form factor. It offers guidance for a variety of factors including physical infrastructure considerations, compute node requirements, and variably sized environments from small to enterprise scale.

 

This version of design guide we have updated our chapter on performance. This chapter was introduced by a popular request from our loyal customer base in version 2.0 of this document and aims at clarifying the myths vs facts on NSX-T based SDN.

 

This document does not cover installation, and operational monitoring and troubleshooting. For further details, review the complete [NSX-T installation and administration guides](https://docs.vmware.com/en/VMware-NSX-T/index.html).

A list of additional resources, specific API examples and guidance are included at the end of this document under multiple appendixes.


Finally starting with this design guide, readers are encouraged to send a feedback to NSXDesignFeedback@groups.vmware.com