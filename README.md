# Azure-Project-Governance
Configuring Governance with Azure Policy and Cost Management

The main objective of this project is to implement governance and cost control in Azure using Azure Policy and Cost Management tools. This ensures resources adhere to organisational policies, such as tagging requirements and helps track and manage spending by setting budget limits with alerts. These measures enhance accountability, compliance and financial efficiency in cloud resource management.

For example

Job Specific Scenario: Managing Cloud Governance and Costs for a Growing Startup

A growing startup is scaling its cloud infrastructure in Azure. I was tasked with ensuring all resources are properly tagged for cost tracking and compliance while monitoring and controlling the monthly cloud spending within a £50 budget.

Steps taken:

Steps in Context:

Set Up Governance with Azure Policy:
Implementing the Require Tag on Resources policy at the resource group level. This enforces tagging standards, such as "azureproject", for every new resource created. If a developer forgets to apply tags during resource deployment, Azure marks the resource as non-compliant.

Monitor Compliance:
Regularly checking the Compliance section in Azure Policy to identify non-compliant resources.
Works with the respective teams to bring these resources into compliance by adding the necessary tags, ensuring accurate cost allocation.

Set Budgets and Alerts:
I then set a £50 monthly budget for the startup's Azure subscription.
Next is to configure alerts to notify the team at 80% and 100% of the budget utilisation, ensuring timely action to prevent overspending.

React to Alerts:
When the budget threshold is exceeded, it is vital to investigate usage in Cost Management to identify high-spending resources or inefficient configurations (e.g., underutilised VMs).
Recommends or implements optimisation measures, such as resizing VMs or scaling down unused resources.

Outcome: The startup maintains control over Azure spending, avoiding unexpected bills and ensuring resources are used efficiently.
Tagging governance ensures accurate cost attribution across departments and projects, aiding in financial planning and transparency.
As an IT administrator I provide proactive cloud governance, aligning with the organisations growth while maintaining compliance and cost efficiency.
