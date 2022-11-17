# **CONFIGURE SUBSCRIPTIONS**

## **TOC**

[Introduction](https://learn.microsoft.com/en-us/training/modules/configure-subscriptions/1-introduction) - Link to learning objectives and skills measured in this section.

[Chart of Characeristics and Description](https://learn.microsoft.com/en-us/training/modules/configure-subscriptions/2-identify-regions) - Explination of Paired Regions and what their purpose is.

[Azure Geographies](https://azure.microsoft.com/en-us/explore/global-infrastructure/geographies/#overview) - Link to azure geological locations and regions.

[Ways to Aquire Azure Subscriptions](https://learn.microsoft.com/en-us/training/modules/configure-subscriptions/4-obtain-subscription) - Different options suit different organizatons needs.

[Resource Tagging](https://learn.microsoft.com/en-us/training/modules/configure-subscriptions/7-apply-resource-tagging) - when, why, and how to apply resource tagging.

## Identify Azure Regions

1. Microsoft Azure is made up of datacenters around the globe. Organized based on end users region.Datacenters are in close proximity and networked together with a low-latenccy network.

### Things To Know About Regions

1. Azure is available in over 140 countries/regions.
2. Azure has more regoins than any other cloud servers.
3. Regions provide you with flexibility and scaling to bring applications to end points/ users.
4. Regional pairs are two azure regions paired together to support always on availability of Azure resources.
5. [Chart of Characeristics and Description](https://learn.microsoft.com/en-us/training/modules/configure-subscriptions/2-identify-regions) - Explination of Paired Regions and what their purpose is.

### Things to consider when using regions and regional pairs

1. Always check where your region is and how the pair works for your region. Understand how the applications being deployed use regional pairing to best set up your resources and region deployment.
2. Go to the Azure website to find the region that best suits your business geography. [Azure Geographies](https://azure.microsoft.com/en-us/explore/global-infrastructure/geographies/#overview)

## Implement Azure Subscriptions

- An Azure subscription is a logical unit of Azure services that's linked to an Azure account. An Azure account is an identity in Azure Active Directory (Azure AD) or a directory that's trusted by Azure AD, such as a work or school account. Subscriptions help you organize access to Azure cloud service resources, and help you control how resource usage is reported, billed, and paid.

### Things to know about subscriptions

- Every Azure cloud service belongs to a subscription.
- Each subscription can have a different billing and payment configuration.
- Multiple subscriptions can be linked to the same Azure account.
- **More than one Azure account can be linked to the same subscription.**
- Billing for Azure services is done on a per-subscription basis.
- If your Azure account is the only account associated with a subscription, you're responsible for the billing requirements.
- Programmatic operations for a cloud service might require a subscription ID.
- **Consider access to resources. Every Azure subscription can be associated with an Azure AD. Users and services authenticate with Azure AD before they access resources.**

[Ways to Aquire Azure Subscriptions](https://learn.microsoft.com/en-us/training/modules/configure-subscriptions/4-obtain-subscription) - Different options suit different organizatons needs.

## Implement Microsoft Cost Management

- Tracks spend through azure to help manage subscriptions and usage.
- Show internal and external cost of Azure Marketplace.
- Can be integrated with 3rd party anylitic programs to track cost spending.

## Things to know about resource tags

- Each resource tag has a name and a value.
- The tag name remains constant for all resources that have the tag applied.
- The tag value can be selected from a defined set of values, or unique for a specific resource instance.
- A resource or resource group can have a maximum of 50 tag name/value pairs.
- Tags applied to a resource group aren't inherited by the resources in the resource group.
[Resource Tagging](https://learn.microsoft.com/en-us/training/modules/configure-subscriptions/7-apply-resource-tagging)
