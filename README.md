![FloTorch symbol](/icons/flotorch.svg)

# n8n-nodes-flotorch

This is an n8n community node. It lets you use FloTorch in your n8n workflows.

FloTorch is an all-in-one AI gateway.

[n8n](https://n8n.io/) is a [fair-code licensed](https://docs.n8n.io/reference/license/) workflow automation platform.

[Installation](#installation)  
[Operations](#operations)  
[Credentials](#credentials)  <!-- delete if no auth needed -->  
[Compatibility](#compatibility)  
[Usage](#usage)  <!-- delete if not using this section -->  
[Resources](#resources)  
[Version history](#version-history)  <!-- delete if not using this section -->  

## Installation

Follow the [installation guide](https://docs.n8n.io/integrations/community-nodes/installation/) in the n8n community nodes documentation.

## Operations

Chat - Connect a Chat Trigger to chat with your custom FloTorch models

## Credentials

Visit [FloTorch.ai](https://flotorch.ai) to create an account.

## Compatibility

Node.js 24

n8n 1.117.3

## Usage

[Try out n8n](https://docs.n8n.io/try-it-out/)

[Run custom n8n nodes locally](https://docs.n8n.io/integrations/creating-nodes/test/run-node-locally/)

1. Install n8n globally using npm

    ```bash
    npm install n8n -g
    ```

2. Clone the repo

    ```bash
    git clone https://github.com/adibudithi-fissionlabs/n8n-nodes-flotorch.git
    ```

3. Navigate inside the repo

    ```bash
    cd n8n-nodes-flotorch
    ```

4. Install Node.js packages

    ```bash
    npm install
    ```

5. Build FloTorch node package

    ```bash
    npm run build
    ```

6. Link package

    ```bash
    npm link
    ```

7. Navigate to ~/.n8n/custom (in the root directory of your machine). Create it if needed.

    ```bash
    cd ~/.n8n/custom
    mkdir ~/.n8n/custom
    ```

8. Add FloTorch node

    ```bash
    npm link n8n-nodes-flotorch
    ```

## Resources

* [n8n community nodes documentation](https://docs.n8n.io/integrations/#community-nodes)
* [FloTorch resources](https://github.com/FloTorch/Resources)

## Version history

* v1 - First working version
