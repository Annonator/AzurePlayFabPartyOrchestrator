# AzurePlayFabPartyOrchestrator

As of today (November 2020) Azure PlayFab does not have an out of the box solution to discover and create Azure PlayFab Party Session on demand. The intend of this Project is to provide a simple, scale able solution for discovering and matching Players into an appropriate Party session on demand.

In order to achieve this, we will make use of Azure Functions to provide a API where Players can announce that they are open to join a Party and one endpoint to match players based on some constrains.


## Disclaimer
This is a sample project and reference architecture not intended for production use. Everything you see here is not based on a single customer but on feedback gathered over time from multiple sources that lead to this reference implementation. If you are looking for insights or help regarding this project, please feel free to open an issue in this repository. PR's are welcomed but please make sure to keep this as general as possible.