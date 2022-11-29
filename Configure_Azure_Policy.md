# Configure Azure Policy

- Learn how to configure Azure Policy to implement compliance requirements.

## Things to know about management groups

    - By default, all new subs are placed under the top-level management group, or root group.
    
    - All subs within a management group automatically inherit the conditions applied to that group.
    
    - A Management group tree can support up to six levels of depth.
    - Azure roll-based access control auth not ennabled by default. 
  
[Example of a GROUP TREE](https://learn.microsoft.com/en-us/training/modules/configure-azure-policy/2-create-management-groups)

    - used to manage subs and give access.

## Implement Azure policies

[link](https://learn.microsoft.com/en-us/training/modules/configure-azure-policy/3-implement-azure-policies)

    - Azure policies scans resources to make sure compliant. 
  
    -  click link for table.

### Things to consider

    - deployable resources.
    - Location restrictions, choose specific geographic locations or regions that are available to an organizagion.
    - rules enforcement.
    - inventory audits.

## Create Azure Policiies

    - Create policy definitions - A plicy definition can prevent VMs from being deployed if exposed to a public IP address.

    - Create an initiative definition - ensure resources are compliant with security regulations.

    - Scope the initiative definition - you can limit the scope of an initiative definition to specific management groups, subs, or resource groups.

    - Determine Compliance - Individual resources, resource groups, and subscriptions within a scope can be exempted from having the policy rules affect it. Exclusions are handled individually for each assignment.

    When writing a new policy definition must be in JSON format required by Azure.

[Create an initiative definition](https://learn.microsoft.com/en-us/training/modules/configure-azure-policy/6-create-initiative-definitions) - Examples, Must be written in JSON format.

## Knowledge Check

[Answer the following questions](https://learn.microsoft.com/en-us/training/modules/configure-azure-policy/10-knowledge-check)

1. There are several Azure policies that need to be applied to a new branch office. What's the best approach?

Create a policy initiative

2 To satisfy the finance team's request for billing by department, multiple resource groups have been created and the resource tags applied. What's the next step?

Create an Azure policy

3 How can you ensure that only cost-effective virtual machine SKU sizes are deployed?

Create a policy in Azure Policy that specifies the allowed SKU sizes

4 Which option can you use to manage governance across multiple Azure subscriptions?

Management groups

## Summary and Resources

[Link to resources](https://learn.microsoft.com/en-us/training/modules/configure-azure-policy/11-summary-resources)

    - Azure Policy is a service in Azure that enables you to create, assign, and manage policies. Azure Policy helps you define and implement your governance strategy by using policies to control and audit your resources.

    - In this module, you explored how to implement Azure policy definitions and initiatives for your corporate departments. You discovered how to create management groups to target specific policies and spending budgets. You reviewed how Azure policies can be scoped to meet compliance regulations.
  