---
copyright:
  years: 2019
lastupdated: "2019-10-17"

keywords: compute, virtual server, profile, vpc, vpc on classic, infrastructure, cloud environment

subcollection: overview

---

{:new_window: target="_blank"}
{:shortdesc: .shortdesc}
{:screen: .screen}
{:codeblock: .codeblock}
{:pre: .pre}
{:tip: .tip}
{:note: .note}

# Comparing compute generations in VPC
{: #compare-vpc-vpcoc}

Compare the key differences between generations of virtual server profiles to decide which generation is best for your workloads and applications.
{: shortdesc}

* First-generation virtual server profiles were introduced with the release of {{site.data.keyword.vpc_full}} (VPC) and offer a broad selection of general-purpose profiles that are available in all VPC regions. 
* Second-generation virtual server profiles offer five times faster provisioning speeds and up to 5 times the networking performance of generation 1 profiles.

## Considerations across generations of virtual server profiles
{: #compare-feature-vpc-vpcoc}

See the following table for more information about generational differences.

We are always adding new features and support. Over time, there will be fewer considerations between generations of compute resources.
{:note}

| Key Features | Current Considerations |
|-----|-----|
|Linux instance support||
|Windows instance support| Windows images are supported for generation 1 profiles only. |
|Import custom images| |
|Developer-friendly, REST-based API||
|IBM Kubernetes Service (IKS) requirements| IKS is supported for generation 1 profiles only. |
{: table="table2"}
{: tab-title="Compute"}
{: tab-group="Features"}
{: class="comparison-tab-table"}
{: row-headers}
{: caption="Table 1. VPC compute infrastructure feature availability" caption-side="top"}
{: summary="This table has row and column headers. The row headers identify characteristics features. The column headers identify whether the feature is included in generation 1 or generation 2 infrastructure. To understand the differences between environments, navigate to the row and find the details for the feature that you're interested in."}

| Key Features | Current Considerations |
|-----|-----|
|Multi-zone regions | Generation 2 profiles are available in Dallas only. |
|Subnet|  |
|Floating IPv4| |
|BYOIP (RFC-1918 based)| |
|Public gateway| |
|Security groups| |
|Network access control lists (ACLs)| ACLs are supported for generation 1 resources only.  |
|VPN| VPN is supported in Beta for generation 2 resources.   |
|Load balancer| Load balancer is supported in Beta for generation 2 resources.  |
|Access to classic infrastructure| Access to classic infrastructure is supported for generation 1 resources only. |
{: table="table3"}
{: tab-title="Network"}
{: tab-group="Features"}
{: class="comparison-tab-table"}
{: row-headers}
{: caption="Table 2. VPC network infrastructure feature availability" caption-side="top"}
{: summary="This table has row and column headers. The row headers identify characteristics features. The column headers identify whether the feature is included in generation 1 or generation 2 infrastructure. To understand the differences between environments, navigate to the row and find the details for the feature that you're interested in."}

| Key Features | Current Considerations |
|-----|-----|
|Block Storage primary and secondary volumes||
|Provider-managed block storage keys||
|BYOK block storage keys| BYOK is supported for generation 1 profiles only. |
{: table="table4"}
{: tab-title="Storage"}
{: tab-group="Features"}
{: class="comparison-tab-table"}
{: row-headers}
{: caption="Table 3. VPC storage infrastructure feature availability" caption-side="top"}
{: summary="This table has row and column headers. The row headers identify characteristics features. The column headers identify whether the feature is included in generation 1 or generation 2 infrastructure. To understand the differences between environments, navigate to the row and find the details for the feature that you're interested in."}

## Same developer-friendly API and experience

Both generations of compute resources have the same developer-friendly API and user experience. You can migrate your virtual server instances from the classic infrastructure to VPC using the IBM Cloud console, or modify your existing API script to recreate your environment.  

Generation 1 and generation 2 resources are not compatible and must be created in separate VPCs.
{:tip}

For more information about migrating virtual server instances from our classic infrastructure, see the following information.
* [Migrating classic virtual server instances to a VPC for generation 1 compute](/docs/vpc-on-classic-vsi?topic=vpc-on-classic-vsi-migrate-vsi-from-classic-infra-to-vpc-on-classic)
* [Migrating classic virtual server instances to a VPC for generation 2 compute](/docs/vpc?topic=vpc-migrate-vsi-to-vpc)

For information about the VPC API considerations when migrating to generation 1 or generation 2 compute resources, see [API application migration considerations](/docs/vpc?topic=vpc-api-integration-migration).

## Next steps
{: #compare-nextsteps-vpc-vpcoc}

For more information about VPC capabilities and how to get started, see the following information.

* [VPC for generation 1 virtual server profiles](/docs/vpc-on-classic?topic=vpc-on-classic-getting-started)
* [VPC for generation 2 virtual server profiles](/docs/vpc?topic=vpc-getting-started)
