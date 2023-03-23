
Theme [scrum_theme]
Contains the Agile element called theme which is either a tangible product (such as a trading application) or an abstract goal (such as performance tuning). 

Epic [rm_epic]
Contains related stories or requirements that you have not yet transformed into stories. 

Story [rm_story]
Indicates self-contained pieces of work called tasks that can be completed within a sprint. 

Scrum release [rm_release_scrum]
Contains individual release versions of the product. Each release contains a list of sprints. 

Sprint [rm_sprint]
Stores sprints, which are the backlog items to be addressed together during a given time period.

Team [scrum_pp_team]
Contains the information of the team members who complete scrum tasks and stories during releases and sprints. 

Agile Development 2.0 Implementation: Base Configuration (Tokyo)
100% COMPLETE
Lesson 2 - Roles

Lesson 3 of 12
Tables
Office image
Abel:  As the Implementation Specialist, it is important to recognize the data tables associated with Agile Development 2.0 and their relationship.

Tables

The data tables are used to manage the agile process, represent releases, and represent product backlog items to be included in a sprint. These tables are installed with the activation of the Agile Development 2.0 plugin.  

Select each of the cards to learn more.

Front of card
Theme [scrum_theme]


Click to flip
Back of card
Contains the Agile element called theme which is either a tangible product (such as a trading application) or an abstract goal (such as performance tuning). 


Click to flip
Front of card
Epic

[rm_epic]


Click to flip
Back of card
Contains related stories or requirements that you have not yet transformed into stories. 


Click to flip
Front of card
Story

[rm_story]


Click to flip
Back of card
Indicates self-contained pieces of work called tasks that can be completed within a sprint. 


Click to flip
Front of card
Scrum release [rm_release_scrum]


Click to flip
Back of card
Contains individual release versions of the product. Each release contains a list of sprints. 


Click to flip
Front of card
Sprint

[rm_sprint]


Click to flip
Back of card
Stores sprints, which are the backlog items to be addressed together during a given time period.


Click to flip
Front of card
Team

[scrum_pp_team]


Click to flip
Back of card
Contains the information of the team members who complete scrum tasks and stories during releases and sprints. 


Click to flip
Data Model

The data model allows you to normalize data and to define it in terms of what it is and what attributes it can possess. It gives the ability to ask and derive reports from the database. The data and relationships represented in the data model provide a foundation to build a common understanding of Agile business processes. If an implementer is asked to create additional fields on a project form, they must first look at the data model to see if the fields exist, or is part of a relational table before creating new ones. 

For example, if PPM Adventure World wants to add a new field, cooling stations, to the Story form, you would want to look at what other tables are related to the Story table in case you can reference any existing fields as opposed to creating a brand new field in the data dictionary.

## Unified Backlog Data Table

Unified Backlog allows the scrum product owner to add any task types to their backlog or sprints such as stories, defects, incident tasks, or problem tasks, using a Triage Board.

To make triage records appear in the backlog, ServiceNow uses a ‘wrapper’ story record to wrap objects related to the Agile application. Activating the Agile Development – Unified Backlog plugin adds the following tables:

---

## Agile Properties

The Agile Development 2.0 application adds several properties to assist agile processes. 

Navigate to the System Properties page. You can type sys_properties.list in the navigator to open the page. Use the keyword *sdlc to view for the list of properties related to agile. 
---
Burndown chart in linear line

Burndown chart is a visual representation of work completed against the projected rate of completion. 

This property draws the burndown chart ideal line as a straight line if set to true.
---

Default Sprint Length

The length of the sprint (in days) is specified during the creation of the sprint. The default sprint length is used if the length cannot be calculated from the sprint. An administrator can specify a default sprint duration that can be used when creating a sprint. 
---
Progress Task State

Tasks to be shown on the progress board can be defined based on their state. 

This property allows to specify the states of the task using a comma separated list that should be shown in the progress board. The states in the progress board follow the same order as specified here.
---
Task uses Actual Hours

This property enables the Actual Hours field in the Scrum Task form. The field displays actual hours of tasks on the task progress board. It gives the ability to track actual hours against a scrum task.
---
Agile2SecurityManager

This script is created when the Agile Development 2.0 plugin is installed. It fetches a list of options for a field, when other fields are set. For example, it fetches a list of sprints when a user selects a group, etc. The value of this property can be changed by an admin. 
---
Progress Board Parent Updates

By default, any changes to a task in the progress board does not update the parent story. An administrator can update the parent stories when changes are made to tasks in the progress board. 

The progress_board_parent_updates property specifies whether the changes to task in the progress board update their parent stories.
---
Progress Task State

Tasks to be shown on the progress board can be defined based on their state. 

This property allows to specify the states of the task using a comma separated list that should be shown in the progress board. The states in the progress board follow the same order as specified here.
---
Progress Story States

Stories shown in the progress board can be defined on the basis of their state.

This property specifies the story states that should be shown in the story progress board. The states in the progress board follow the same order as specified here.
---

## Additional Properties

### Auto Fill Time Card

To effectively track the time spent on the scrum tasks and stories, you can convert hours of the stories to timecards. Time Sheet policies allow users to automatically fill the time cards with the time spent to complete the task. 
Navigate to Project Administration > Settings > Policies – timesheet to configure the Time Sheet policy.

To configure the Time Sheet Policy, perform the following steps: 

Select the Default time sheet policy to view the policy details. 
Select the checkbox against Auto fill time card with time worked entries property to enable it. 
Click Update.
