# Algorand Public Data

Algorand Public Data project provides public json data about algorand nodes and projects

Please help improve this data service. If you run or know about service which is not listed here, please create pull request.

Organization of the data:

## List of algorand projects

Folder `project`

Each project is identified by the subfolder. Eg `project/vote-coin`

Code of the project must be slugify representation of the project name.

`description.json` file is required.

## Algorand node

Folder `algod`

List of algorand participation nodes, or archival nodes accessible by public for requesting for example tx params before the transactions or submitting the tx to the blockchain.

Programmers, feel free to use the public jsons as the source of data. Eg. https://scholtz.github.io/AlgorandPublicData/algod/mainnet-v1.0/public-algod-providers.json

## Algorand indexer

Folder `indexer`

List of algorand indexers. APIs to query algorand blockchain.

## KMD servers

Folder `kmd`

List of algorand public validator servers.

## Genesis data

Folder `genesis`

Genesis data for algorand type networks.