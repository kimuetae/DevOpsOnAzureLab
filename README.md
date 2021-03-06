# DevOpsOnAzureLab

This *DevOps on Microsoft Azure lab* is designed as a step-by-step guide to demonstrate how you could add DevOps practices for any of your current projects. We are illustrating this lab with a sample ASP.NET Core web app hosted on Azure App Service (Web App) with Application Insights all of which is orchestrated by Visual Studio Team Services (VSTS).

Total duration of this lab: 80 min

## Agenda of this lab

1. [Introduction (15min)](./docs/Introduction/README.md)
2. [Lab 1 - Source control (10min)](./docs/Lab%201%20-%20Source%20control/README.md)
3. [Lab 2 - Continuous Integration (20min)](./docs/Lab%202%20-%20Continuous%20Integration/README.md)
4. [Lab 3 - Continuous Delivery (25min)](./docs/Lab%203%20-%20Continuous%20Delivery/README.md)
5. [Lab 4 - Continuous Monitoring (10min)](./docs/Lab%204%20-%20Continuous%20Monitoring/README.md)
7. [Conclusion (15min)](./docs/Conclusion/README.md)

Note: It's important to follow the lab in the order exposed, each lab add a key feature for the project which will be used by the next steps.

## Prerequisities

- 1 Microsoft Azure subscription
  - If you don't have one, give it a try: [https://azure.microsoft.com/free/](https://azure.microsoft.com/fr-fr/free/)
- 1 Visual Studio Team Services account + 1 VSTS Project (with Git)
  - If you don't have one, give it a try: [https://www.visualstudio.com/team-services](https://www.visualstudio.com/team-services)
- 1 Slack account + 1 Slack channel
  - If you don't have one, give it a try: [https://slack.com/](https://slack.com/)
- 1 Web Browser (Edge, Chrome or FireFox for example)
  - **No local development or manipulation, all operations are done through your web browser.**

## History of changes

- 2017-11-16 - Integrate YAML definition for CI - [PR#6](https://github.com/mathieu-benoit/DevOpsOnAzureLab/pull/6)
- 2017-11-15 - Add Gates in the Release pipeline - [PR#5](https://github.com/mathieu-benoit/DevOpsOnAzureLab/pull/5)
- 2017-11-07 - Initial lab for the Agile Tour Quebec 2017