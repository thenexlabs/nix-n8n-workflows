# Nix Block Workflow Examples

This repository contains examples of workflows using the Nix Block, showcasing its versatility and integration with various applications.

## n8n is automatically hosted privately for all NixGuard tiers above Basic

## host yourself - n8n AI Starter Kit

Check out the [n8n Template AI Starter Kit](https://docs.n8n.io/hosting/starter-kits/ai-starter-kit/) to get started with AI workflows in n8n.

## Contents

1. **Workflows**: collection of workflows showcasing Nix.
   1. **Nix Block**: Workflow made to be used within other workflows.
   1. **Basic Nix Block Usage Example**: Demonstrates how to use a Nix Block.
   2. **Categorizing Emails with Nix Example**: Identifies spam emails and labels them.
   3. **Scheduled Nix Block Example**: Runs a Nix Block every hour and notifies team members via popular apps about alerts.
2. **Community Contributions**: Share your own workflows with the community!

## Getting Started

### For Importing Workflows:

1. **Import Workflows into n8n**:
   - **Import via URL**:
     1. Open your n8n instance and log in.
     2. Go to the "Workflows" section.
     3. Click on the "Import" button.
     4. Select the "URL" option.
     5. Enter the raw GitHub URL of the workflow you want to import, for example:
        ```plaintext
        https://raw.githubusercontent.com/thenexlabs/nix-n8n-workflows/main/workflows/example_workflow.json
        ```
     6. Click "Import" to add the workflow to your n8n instance.

   - **Import via File**:
     1. Open your n8n instance and log in.
     2. Go to the "Workflows" section.
     3. Click on the "Import" button.
     4. Select the "File" option.
     5. Click "Choose File" and select the JSON file of the workflow you want to import from your local machine.
     6. Click "Import" to add the workflow to your n8n instance.

## Contributing

We welcome contributions from the community! If you have a workflow you'd like to share, please follow these steps:

1. **Fork the Repository**: Fork this repository to your GitHub account.
2. **Create a New Folder**: Add a new folder under `community-contributions` with a descriptive name & a README describing the workflow.
3. **Add Workflow Files**: Include all necessary files (e.g., JSON configuration, scripts) in your folder.
4. **Submit a Pull Request**: Submit a pull request with your contributions. Your workflow will be reviewed before inclusion.

## Review Process

All community contributions will be reviewed to ensure they meet quality standards. We appreciate your patience during this process.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

