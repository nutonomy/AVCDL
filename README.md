# AVCDL

## Overview

The **AVCDL** is a set of identified processes, requirements of those processes, generated products,
and mappings from the generated products to their corresponding certification standard (**ISO/SAE 21434**,
**UNECE WP.29**) work products: for the purpose of ensuring the creation of secure systems.

## Where to Start

There's a lot of material here with more on the way. The recommended starting point is the [**AVCDL** primary document](./AVCDL.pdf). The primary document is about 160 pages, so it's recommended that you download the repository. Although you could just download the primary document itself, there are outbound links to the secondary documents that are path relative. If you can get by with just picking things out yourself, then download the primary document, the [secondary documents directory](./reference_documents/secondary_documents), and the [working material directory](./reference_documents/working_material).

## Background Material

Before beginning, you should read the blog series introducing the **AVCDL** and the concepts behind it.

| Title | Description |
|--|--|
| [Cybersecurity and Safe Driverless Vehicles](https://mindsofmotional.medium.com/cybersecurity-and-safe-driverless-vehicles-e7af87c59cad) | how do you create safe driverless vehicles? |
| [Purpose-driven Security](https://mindsofmotional.medium.com/purpose-driven-security-882c2d983216) | how we have chosen to apply security in a way that supports vehicle safety |
| [Certifiably Secure: Does it Matter?](https://mindsofmotional.medium.com/certifiably-secure-does-it-matter-9334c2566cf7) | you can make thing secure without getting outside approval, so why bother? |
| [Policy - Process - Procedure](https://mindsofmotional.medium.com/policy-process-procedure-whats-in-a-name-139bb98dd57f) | coming to terms with the terms |
| [Aligning the Organization with the AVPDL](https://mindsofmotional.medium.com/aligning-the-organization-with-the-avpdl-af1d60ea7c1f) | how do you bring the multitude of development practices together? |
| [Traceability: Making the Case for Security](https://mindsofmotional.medium.com/traceability-making-the-case-for-certification-62f3cb93c085) | how do you ensure follow through? |
| [The AVCDL: Autonomous Vehicle Cybersecurity Development Lifecycle](https://mindsofmotional.medium.com/avcdl-the-autonomous-vehicle-cybersecurity-development-lifecycle-266cf51e1cad) | an overview of the AVCDL |

## Element Relationships

The following diagram illustrates the relationship between the various sources for and elements of the **AVCDL**.

![lifecycle creation flow](./reference_documents/misc/images/processed/lifecycle%20creation%20flow.png)

## Release Timetable

The **AVCDL** has a lot of moving parts. We'll be providing material as soon as it has been reviewed by the certification body we're working with.

## AVCDL Element Status

The following table shows the status of the various AVCDL elements.

| Secondary (process) Document                        | Status   |
|-----------------------------------------------------|----------|
| **General**                                         |          |
| security requirements taxonomy                      | complete |
| understanding the phase products dependencies graph | complete |
| secure design principles                            | draft    |
| understanding workflow graphs                       | complete |
| understanding cybersecurity interface agreements    | complete |
|                                                     |          |
| **Foundation Phase**                                |          |
| training catalog                                    | draft    |
| system to track training participation              | draft    |
| roles and responsibilities                          | complete |
| list of approved tools and components               | draft    |
| global security goals                               | complete |
| global security requirements                        | complete |
| code protection plan                                | draft    |
| release integrity plan                              | draft    |
| cybersecurity monitoring plan                       | draft    |
| incident response plan                              | draft    |
| decommissioning plan                                | template |
| threat prioritization plan                          | draft    |
| deployment plan                                     | template |
|                                                     |          |
| **Requirements Phase**                              |          |
| product-level security goals                        | draft    |
| product-level security requirements                 | draft    |
| requirements phase gate                             | draft    |
|                                                     |          |
| **Design Phase**                                    |          |
| design showing security considerations              | draft    |
| security design review report                       | template |
| attack surface analysis report                      | draft    |
| threat modeling report                              | draft    |
| ranked/risked threat report                         | draft    |
| threat report                                       | draft    |
| design phase gate                                   | draft    |
|                                                     |          |
| **Implementation Phase**                            |          |
| list of tools and components used                   | draft    |
| build process documentation                         | draft    |
| secure setting document                             | draft    |
| component/version - product/version cross-reference | draft    |
| secure development                                  | draft    |
| currently used deprecated functions                 | draft    |
| static analysis report                              | draft    |
| dynamic analysis report                             | draft    |
| secure code review summary                          | draft    |
| fuzz testing report                                 | draft    |
| implementation phase gate                           | draft    |
|                                                     |          |
| **Verification Phase**                              |          |
| penetration testing report                          | template |
| updated threat model                                | draft    |
| updated attack surface analysis                     | draft    |
| verification phase gate                             | draft    |
|                                                     |          |
| **Release Phase**                                   |          |
| final security review report                        | draft    |
| archive manifest                                    | template |
| release phase gate                                  | draft    |
|                                                     |          |
| **Operation Phase**                                 |          |
| cybersecurity incident report                       | template |
| software deployment report                          | template |
|                                                     |          |
| **Decommissioning Phase**                           |          |
| decommissioning report                              | template |

#### Legend

| Status   | Description                       |
|----------|-----------------------------------|
| template | not completed                     |
| draft    | pending certification body review |
| complete | reviewed by certification body    |
