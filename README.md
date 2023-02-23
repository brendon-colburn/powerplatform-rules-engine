# Rules Engine for Power Platform
An accelerator for building rules engines in Power Platform. It's getting iteratively improved based on the feedback from the community. It's built to be flexible and extensible. It's a great starting point for building your own rules engine.

## Features
- Dataverse solution for deployment and packaging
- Dataverse tables for configuration and a sample advanced approval use case
- Power Automate for running the rules engine and kicking off approval flows on assignment
- Model Driven App for the sample approval use case
- Canvas App for building rules

## Getting Started
1. Download the latest release from the [releases page](
2. Import the solution into your Dataverse environment
3. Create a new record in the Rules Engine Configuration table
4. Populate the configuration record with the following [sampleRule.json](sampleRule.json)
   
## How to demonstrate the sample approval use case
Watch this video to see how to demonstrate the sample approval use case: [Federal Business Applications Summit Dec 8th Recording](https://youtu.be/OvncrX4gS8Q)

Some things have changed / improved though since the recording. Here are the additional steps to follow:
1. Populate the user role tables with a branch chief, usually best to use yourself as the user for demo purposes
2. Assignment generation now works, woohoo!
3. If you want to show the guts, show the run history of the rules engine flow and the assignment approval flow

## How to contribute
1. Fork the repo
2. Test your changes
3. Demo them to me
4. We can discuss how to merge them into the main branch
