# Introduction to our project management process
We would love you to contribute to Flilia and help make it even better than it is today! As a contributor, here are guidelines we would like you to follow:

- [Getting started](#start)
- [About Scrum](#scrum)
- [Related documentation and guidance](#guidance)

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
- [Office365][office365]
- [Outlook][outlook]
- [Flilia channels in Teams][fliliateams]
- [Flilia project in Azure DevOps][azureflilia]

## <a name="scrum"></a> About Scrum
Scrum methods use Iteration Paths, also referred to as sprints, to plan work to be performed by a team within a specific time period and cadence.

For the further work, read more details and guidelines about [Scrum][scrum] and [Azure Scrum process][scrumazure].

- [Areas](#scrumareas)
- [Sprints](#scrumsprints)
- [Work item types](#scrumtypes)
- [Work item tags](#scrumtags)
- [Connect with GitHub](#scrumgithub)

#### <a name="scrumareas"></a> Areas
Currently we have three areas for each part of project with its own [Delivery Plan][plan].
```shell
Area-1: "flilia.com"
Area-2: "business.flilia.com"
Area-3: "support.flilia.com"
```

#### <a name="scrumsprints"></a> Sprints
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

#### <a name="scrumtypes"></a> Work item types
Agile management processes have [work item types][scrumwits] (WITs) they provide for planning and tracking work.

In our project we use lightweight Scrum process that have the following WITs:
```html
Portfolio
backlog    <Feature>
               |
-------------------------------------
Product        |
backlog        └─⫸ <Product-Backlog-Item>
               |             |
               |             └─⫸ <Task>
               └─⫸ <Bug>
                      |
                      └─⫸ <Task>
```

#### <a name="scrumtags"></a> Work item tags
[Tagging work items][tagging] helps you quickly filter the product backlog or a work item query by categories that you define. A tag corresponds to a one or two keyword phrase that you define and that supports your needs to filter a backlog or query, or define a query.

We have a few rules for how tags should be added, this format leads to easier to read issues and task:
- tags is mandatory and must conform to the issues and tasks subject
- not capitalized
- no dot (.) at the end
- no special characters
- maximum length is 20 characters
- total count cannot be more than 6

There are several default tags that can be used in issues and tasks:
- [![#ec001d](https://via.placeholder.com/15/ec001d/000000?text=+) bug] - Something isn't working
- [![#2cbdd9](https://via.placeholder.com/15/2cbdd9/000000?text=+) documentation] - Improvements or additions to documentation
- [![#525252](https://via.placeholder.com/15/525252/000000?text=+) duplicate] - This issue or pull request already exists
- [![#00564b](https://via.placeholder.com/15/00564b/000000?text=+) feature] - New feature or request
- [![#00564b](https://via.placeholder.com/15/00564b/000000?text=+) enhancement] - New feature or request
- [![#245cac](https://via.placeholder.com/15/245cac/000000?text=+) good first issue] - Good for newcomers
- [![#7ace64](https://via.placeholder.com/15/7ace64/000000?text=+) help wanted] - Extra attention is needed
- [![#fbfd52](https://via.placeholder.com/15/fbfd52/000000?text=+) invalid] - This doesn't seem right
- [![#ff00ff](https://via.placeholder.com/15/ff00ff/000000?text=+) question] - Further information is requested
- [![#525252](https://via.placeholder.com/15/525252/000000?text=+) wontfix] - This will not be worked on

You can add custom tags, but be sure new tags is conform to the issues and tasks subject.

<strong>NOTE</strong>: If you misspell a tag, don't assign the misspelled tag to any work item and the system will automatically delete it within 3 days.

#### <a name="scrumgithub"></a> Connect with GitHub
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

[azureflilia]: https://dev.azure.com/flilia/Flilia
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
[scrumwits]: https://docs.microsoft.com/en-us/azure/devops/boards/work-items/guidance/scrum-process-workflow?view=azure-devops
[plan]: https://dev.azure.com/flilia/Flilia/_deliveryplans/plan/dc023e6a-c4a5-4493-959b-af6f5e5a8f1a
[tagging]: https://docs.microsoft.com/en-us/azure/devops/boards/queries/add-tags-to-work-items?view=azure-devops
[fliliateams]: https://teams.microsoft.com/l/team/19%3af126286a785b46e49b9a94d3eed0ffd8%40thread.tacv2/conversations?groupId=462ef793-2a17-4613-ab50-ea302d209c26&tenantId=be3b533b-6900-4e84-8338-a5934799565d
[outlook]: https://outlook.office.com
[office365]: https://www.office.com