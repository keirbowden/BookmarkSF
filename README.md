# Bob Buzzard's Bookmarks Plug-In Salesforce Metadata

This the metadata that accompanies the Salesforce CLI plug-in created for my [ApexHours](https://www.youtube.com/watch?v=jk4kx6EO1MQ) session.

## Installation

The metadata is in source format, so can be installed to a scratch org using the command:

`sfdx force:source:push`

or to a developer, sandbox or production org using the command

`sfdx force:source:deploy -p force-app`

Install the plug-in from the NPM package register using the command:

`sfdx plugins:install bbbookmarks`

## Usage

Run `sfdx bbbm -h` to see the available commands, and then `sfdx bbbm:<subcommand> -h` to get the details for a specific subcommand.