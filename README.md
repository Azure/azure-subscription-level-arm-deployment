---
page_type: sample
languages:
- json
- yml
products:
- Azure Resource Manager (ARM)
- Azure DevOps
description: "A sample subscription level deployment of two vnets in separate regions and peering."
urlFragment: ""
---

# Official Microsoft Sample

<!-- 
Guidelines on README format: https://review.docs.microsoft.com/help/onboard/admin/samples/concepts/readme-template?branch=master

Guidance on onboarding samples to docs.microsoft.com/samples: https://review.docs.microsoft.com/help/onboard/admin/samples/process/onboarding?branch=master

Taxonomies for products and languages: https://review.docs.microsoft.com/new-hope/information-architecture/metadata/taxonomies?branch=master
-->

A sample subscription level deployment of two vnets in separate regions. The sample creates resource groups, an example policy definition and assignment as well as the nested deployments for each vnet. The sample includes an example DevOps Pipeline to peer the two vnets and demonstrate marshalling variables from the output of the first deployment to parameters of the second.

## Contents

| File/folder                        | Description                                |
|------------------------------------|--------------------------------------------|
| `sample\`                          | All sample files are in this folder.       |
| `sample\az-deploy.json`            | ARM Template deployment file.              |
| `sample\az-deploy.parameters.json` | ARM Template parameters file.              |
| `sample\az-peer-vnets.json`        | ARM Template to peer vnets.                |
| `sample\azure-pipelines.yml`       | Example DevOps piplines file.              |
| `.gitignore`                       | Define what to ignore at commit time.      |
| `CHANGELOG.md`                     | List of changes to the sample.             |
| `CONTRIBUTING.md`                  | Guidelines for contributing to the sample. |
| `README.md`                        | This README file.                          |
| `LICENSE`                          | The license for the sample.                |

## Contributing

This project welcomes contributions and suggestions.  Most contributions require you to agree to a
Contributor License Agreement (CLA) declaring that you have the right to, and actually do, grant us
the rights to use your contribution. For details, visit https://cla.opensource.microsoft.com.

When you submit a pull request, a CLA bot will automatically determine whether you need to provide
a CLA and decorate the PR appropriately (e.g., status check, comment). Simply follow the instructions
provided by the bot. You will only need to do this once across all repos using our CLA.

This project has adopted the [Microsoft Open Source Code of Conduct](https://opensource.microsoft.com/codeofconduct/).
For more information see the [Code of Conduct FAQ](https://opensource.microsoft.com/codeofconduct/faq/) or
contact [opencode@microsoft.com](mailto:opencode@microsoft.com) with any additional questions or comments.
