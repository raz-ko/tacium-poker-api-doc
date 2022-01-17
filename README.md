# arenax-poker-api-doc
ArenaX Poker API Documentation.

## Format
The documentation is done using AsyncAPI format https://www.asyncapi.com

The documentation visualization is done using AsyncAPI generator CLI.
## AsyncAPI Generator CLI
### Installation
```shell
npm install -g @asyncapi/generator
```
### Generation
```shell
ag doc/arenax_poker_asycapi.yml @asyncapi/html-template -o dist
```
more info can be found at https://www.asyncapi.com/tools/generator

## Artifacts
Documentation artifacts are located under _dist_ folder