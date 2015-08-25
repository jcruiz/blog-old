---
layout: post
title: "Using JIRA for Product Development Flows part 1"
date: 2015-08-25 00:01
comments: true
categories: [product management]
---

![](https://www.atlassian.com/wac/software/jira/sectionWrap/0/column/0/imageBinary/jira_rbg_darkblue.svg){:width="300px"}

A popular tool for managing software product projects is [JIRA](https://www.atlassian.com/software/jira). I've been an active user of this tool as well as [Trello](https://trello.com/) in the last few years and have found different ways that these tools can be used for organizing product development cycles. 

In general the tools are only the channel used by the organization to have a central location where the engineering teams track release cycle, triage bugs and escalations. Also the Product team can use this tools to communicate current features, plan releases and define roadmap.

But as with any tool, if you don't proactively maintain the information that resides in there. Information quickly becomes outdated and easily forgotten.
In this article I would like to go over one of the development flows that we used on a large team.
<!--more-->

##JIRA Projects

We created multiple projects that serve as layers or filters to catalog different types of asks for the engineering team. From feature requests, to escalations, to bug fixes. We quickly understood that in order to maintain an organized and clean engineering backlog we needed to protected at all costs. So, engineering leads and product were responsible to manage the following buckets as described below:

### Feature Requests - FR
**Owner:** Product team
**Purpose**: The bucket where the Product team receives and manages feature requests, enhancements, documentation issues, etc.
Although we used JIRA,  in reality this project could be managed with a simpler and more friendly tool like Trello.

### Icebox - IB
**Owner:** Product/Engineering
**Purpose:** This project was used as a [agile Kanban](https://www.atlassian.com/agile/kanban) board. Here,  product and engineering would place upcoming engineering work. Prior to sprint planning each team made sure that the most important asks where registered and presented during sprint planning meeting. We had a dedicated column called (next sprint). Once the sprint backlog was defined we would move all stories for the sprint into the **Active Sprint** bucket.

### Active Sprint - AS
**Owner:** Product/Engineering
**Purpose:**  This project can be setup either as a [Scrum board](https://www.atlassian.com/agile/scrum) or a Kanban board. It contains the engineering load for the current sprint. We worked hard to be realistic and whatever was in the sprint would be finished at the end. This particularly is a great exercise to keep a good team morale.

### Escalations - ESC
**Owner:** Product/Engineering leads
**Purpose:** The engineering team window to the outside world. Whenever something "urgent" that required attention from engineering, the products and engineering leads would triage the issue and request, ask for more information, or create an escalation in the current sprint o planned for the upcoming sprint.  This way we protected our Active Sprint board the most that we could.

###Final Remarks
Remember that JIRA allows you to do bulk changes, which come really handy when moving things from project to project. Also, we had to keep certain guidelines that helped us to maintain consistency across multiple projects. For example: same components set.

And last but not least, purge your icebox. It's super easy to put things in but really hard to get them out.
