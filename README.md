# contentstack
Contentstack's Urgent Care app content
This repository aims to provide stack content to users for the implementation of marketing websites. An easy way to import this stack content is by using the ‘seed’ command.

To import this content to your stack, perform the following steps:

Install the CLI by running the following command in your terminal:

npm i -g @contentstack/cli

By default, CLI uses the North America region. To use the Europe region, run this command in your terminal:

csdx config:set:region EU

Next, log in to your Contentstack account via CLI:

csdx auth:login

Run the ‘seed’ command to import content to your stack:

csdx cm:seed -r "contentstack/stack-urgentcare-app"

Refer to the Seed command documentation to learn more.
