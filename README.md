# AWS CloudFormation Extension Pack

[![Version](https://img.shields.io/visual-studio-marketplace/v/dannysteenman.aws-cloudformation-extension-pack?color=374151&label=Visual%20Studio%20Marketplace&labelColor=000&logo=visual-studio-code&logoColor=0098FF)](https://marketplace.visualstudio.com/items?itemName=dannysteenman.aws-cloudformation-extension-pack)
[![Installs](https://img.shields.io/visual-studio-marketplace/i/dannysteenman.aws-cloudformation-extension-pack 'Currently Installed')](https://marketplace.visualstudio.com/items?itemName=dannysteenman.aws-cloudformation-extension-pack)
[![Rating](https://img.shields.io/visual-studio-marketplace/stars/dannysteenman.aws-cloudformation-extension-pack)](https://marketplace.visualstudio.com/items?itemName=dannysteenman.aws-cloudformation-extension-pack)

This is a collection of extensions that I've curated in this vscode extension pack to help you build, deploy and manage your AWS CloudFormation templates.

<!-- TIP-LIST:START -->
> [!TIP]
> **Stop AWS bill surprises from happening.**
>
> Most infrastructure changes look harmless until you see next month's AWS bill. [CloudBurn](https://cloudburn.io) prevents this by analyzing the cost impact of your AWS CDK changes directly in GitHub pull requests, catching expensive mistakes during code review when fixes are quick, not weeks later when they're costly and risky.
>
> <a href="https://github.com/apps/cloudburn-io"><img alt="Install CloudBurn from GitHub Marketplace" src="https://img.shields.io/badge/Install%20CloudBurn-GitHub%20Marketplace-brightgreen.svg?style=for-the-badge&logo=github"/></a>
>
> <details>
> <summary>💰 <strong>Set it up once, then never be surprised by AWS costs again</strong></summary>
> <br/>
>
> 1. **First install the free [CDK Diff PR Commenter GitHub Action](https://github.com/marketplace/actions/aws-cdk-diff-pr-commenter)** in your repository where you build your AWS CDK infrastructure
> 2. **Then install the [CloudBurn GitHub App](https://github.com/apps/cloudburn-io)** on the same repository
>
> **What happens now:**
>
> Whenever you open a PR with infrastructure changes, the GitHub Action comments with your CDK diff analysis. CloudBurn reads that diff and automatically adds a separate comment with a detailed cost report showing:
> - **Monthly cost impact** – Will this change increase or decrease your AWS bill? By how much?
> - **Per-resource breakdown** – See exactly which resources are driving costs (old vs. new monthly costs)
> - **Region-aware pricing** – We pick the right AWS pricing based on the region where your infrastructure is deployed
>
> Your team can now validate cost impact alongside infrastructure changes during code review. Essentially, this shifts FinOps left where you optimize costs as you code, not weeks later when context is lost and production adjustments require more time and carry added risk.
>
> CloudBurn will be free during beta. After launch, a free Community plan (1 repository with unlimited users) will always be available.
>
> </details>
<!-- TIP-LIST:END -->

## Included Extensions

This extension pack includes the following VS Code extensions:

1. **AWS Toolkit for Visual Studio Code**: Provides support for developing AWS applications
2. **Boto3 IDE**: Provides intelligent code completion, type checking, and documentation for AWS boto3 SDK
3. **CloudFormation Snippets**: Provides YAML and JSON snippets for all AWS CloudFormation resources
4. **AWS IAM Actions Snippets**: Adds autocomplete and snippets for all AWS IAM policy actions
5. **AWS IAM Service Principal Snippets**: Autocompletion for AWS service principals.
6. **Draw.io Integration**: Integrates Draw.io diagrams into VS Code
7. **CloudFormation Linter**: Validates CloudFormation templates for best practices
8. **YAML**: Provides comprehensive YAML language support

## Installation

1. Open Visual Studio Code
2. Go to the Extensions view (Ctrl+Shift+X or Cmd+Shift+X on macOS)
3. Search for "AWS CloudFormation Extension Pack"
4. Click "Install"

## Usage

Once installed and configured, you can start using the extensions right away in your AWS CloudFormation projects. The extensions will automatically enhance your development environment with features like code completion, linting, formatting, and more.

For specific usage instructions for each extension, please refer to their individual documentation.

---
## Feedback and Contributions

If you have any feedback or suggestions for improving this extension pack, please open an issue on the [GitHub repository](https://github.com/towardsthecloud/vscode-cloudformation-extension-pack/issues). Contributions are always welcome!

Happy templating with AWS CloudFormation!

## Author

[Danny Steenman](https://towardsthecloud.com/about)

[![](https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/company/towardsthecloud)
[![](https://img.shields.io/badge/X-000000?style=for-the-badge&logo=x&logoColor=white)](https://twitter.com/dannysteenman)
[![](https://img.shields.io/badge/GitHub-2b3137?style=for-the-badge&logo=github&logoColor=white)](https://github.com/towardsthecloud)
