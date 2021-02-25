# Introduction to our project management process
We would love you to contribute to Flilia and help make it even better than it is today! As a contributor, here are guidelines we would like you to follow:

- [Question or Problem?](#question)
- [Getting started](#start)
- [About Scrum, Sprints and GitHub](#scrum)
- [Related documentation and guidance](#guidance)

## Got a Question or Problem?
- If your question not related to development, please contact a project manager by email or Teams.
- If your question related to development and project source code, feel free to start discussion and ask any questions in [Developers team][developers-team].
- If your question related to development but not with project source code, we recommend using [Stack Overflow][stackoverflow] to ask support-related questions.
	```
	Stack Overflow is a much better place to ask questions since:
	- there are thousands of people willing to help on Stack Overflow
	- questions and answers stay available for public viewing so your question/answer might help someone else
	- Stack Overflow's voting system assures that the best answers are prominently visible.
	```
- If you would like to chat about the question in real-time, you can reach out via our Flilia team in Microsoft Teams.

## <a name="start"></a> Getting started

#### Prerequisites
- Install [Microsoft Teams][teams]

#### Set up your development environment
For the project management and communication between members in our company we use Office365 and Azure DevOps services by Microsoft company.

For the further work with Office365 and Azure DevOps services follow next steps:
1. Contact a project manager to create a new personal corporate account (Office365).
2. Once you get credentials for your Office365 account, ask to add you to the following places for the further communication with project members:
	- Flilia project in Azure DevOps
	- Flilia team in Microsoft Teams

#### Summary
You should be able to browse different services by using the below URLs:
```shell
Office365: "https://www.office.com"
Outlook: "https://outlook.office.com"
Teams online: "https://teams.microsoft.com"
Azure DevOps: "https://dev.azure.com/flilia/Flilia"
```

## <a name="scrum"></a> About Scrum, Sprints and GitHub
For the further work, introducing with [Azure Scrum process][scrumazure] and read more details and guidelines about [our management process][fliliawiki] on corporate wiki.

#### Scrum and Sprints

[Scrum][scrum] methods use Iteration Paths, also referred to as sprints, to plan work to be performed by a team within a specific time period and cadence.

The default time period of 1 sprint in our project is 2 week.

```html
             2 week
-----⦿---------------------⦿
  |  |             |        |
  |  └─------------|--------└─--⫸ 1. Conducting <retrospective> on completed sprint
  |                |               2. New sprint <planning> before start
  |                |                       
  └─⫸ Sprint 12   └─⫸ Sprint 13
```

`<retrospective>` - As described in the [Scrum Guide][scrumguides], the purpose of the Sprint Retrospective is to plan ways to increase quality and effectiveness.

During the Sprint Retrospective, the team discusses:
- What went well in the Sprint
- What could be improved
- What will we commit to improve in the next Sprint

`<planning>` - As described in the [Scrum Guide][scrumguides], Sprint Planning initiates the [Sprint][sprint] by laying out the work to be performed for the Sprint. This resulting plan is created by the collaborative work of the entire Scrum Team.

Sprint Planning addresses the following topics:
- Why is this Sprint valuable?
- What can be Done this Sprint?
- How will the chosen work get done?

#### Connect with GitHub
As we use Azure DevOps Boards connected with GitHub, here are guidelines we would like you to follow:
- From GitHub, use `AB#<Task ID>` to link GitHub commits and pull requests to your issues and tasks.
- From Azure Boards issues and tasks, link to GitHub commits and pull requests.

Read through our [contributing guidelines][contributing] to learn about our submission process, coding rules and more.

## <a name="guidance"></a> Related documentation and guidance
This guides will help you get started with installing and setting up the languages and tools you need to develop on Windows or Windows Subsystem for Linux:

- [Microsoft Teams][teams]. Meet, chat, call, and collaborate in just one place.
- [Azure DevOps Server][azure] is a Microsoft product that provides version control, reporting, requirements management, project management, automated builds, testing and release management capabilities.
- [Azure Scrum process][scrumazure]. Scrum process.
- [What is Scrum?][scrum]. A Better Way Of Building Products.

[developers-team]: https://github.com/orgs/flilia/teams/developers-team
[azure]: https://azure.microsoft.com/en-us/services/devops/
[teams]: https://www.microsoft.com/en/microsoft-teams/group-chat-software
[fliliawiki]: https://dev.azure.com/flilia/Flilia/_wiki/
[scrumguides]: https://www.scrumguides.org/
[scrum]: https://www.scrum.org/resources/what-is-scrum
[scrumazure]: https://docs.microsoft.com/en-us/azure/devops/boards/work-items/guidance/scrum-process?view=azure-devops
[sprint]: https://www.scrum.org/resources/what-is-a-sprint-in-scrum
[strimplan]: https://www.scrum.org/resources/what-is-sprint-planning
[strimpretro]: https://www.scrum.org/resources/what-is-a-sprint-retrospective
[contributing]: CONTRIBUTING.md
[stackoverflow]: http://stackoverflow.com/
