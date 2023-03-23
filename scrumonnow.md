# ScrumOnNow 


Scrum is being popular around the world this days.

In this series, we will learn the fundamentals of ServiceNow's Agile Development 2.0 application, including how to create products, agile groups, releases, personalized backlogs, and sprints including tracking progress.

The target audience for this course includes:
-Product Owners
-Scrum Masters
-Scrum Users


This course is designed for all customers, partners, and consultants that want to increase skills to learn how to implement Agile Development 2.0 in ServiceNow and gain insight into the technical execution of the application.

In this course, you will learn how to implement Agile Development 2.0 based upon a customer's current processes and the configuration of future needs. Attendees will also gain insights and knowledge into the application's architectural framework, tables, and properties, role administration, what questions to ask during implementation, and explore ad-hoc requirements.In this course, you will learn how to implement Agile Development 2.0 based upon a customer's current processes and the configuration of future needs. Attendees will also gain insights and knowledge into the application's architectural framework, tables, and properties, role administration, what questions to ask during implementation, and explore ad-hoc requirements.


---
One of the very important step of implementating 
Agile Development 2.0 is to *know you Customer*.

Based on the interactions with the stakeholders and executives, you can conclude whether ServiceNow’s Agile Development 2.0 solution would work well or not and understand how to configure the Agile Development 2.0 application.

Agile Development is an iterative and incremental process for software development. It is based on short, fixed scheduled cycles with an adjustable scope to address changing development needs. 

ServiceNow’s Agile Development 2.0 application provides an agile environment for product-based or project-based efforts, using the Scrum framework. It helps deliver software products efficiently by managing and tracking the software development cycle.

In order to understand how PPM Adventure World wants to use ServiceNow’s Agile Development 2.0 application, I would first employ techniques such as workshop sessions and process walk-through meetings to understand their business requirements, team structure, and inclusion in the documentation process,

We believe there are advantages of using Agile methodology because it will allow our Project Management and Customer Service teams to work in short cycles with an adjustable scope to address the rapidly changing needs. This will lead to positive reviews, and higher customer satisfaction. We are struggling with our current practices because of the complexity of our work.

  I want to get a better understanding of what your current processes are so that we can configure ServiceNow to best meet your needs. 

As a best practice, ServiceNow does not recommend having end-users create stories directly. There should be some sort of intake process. 

Intake Process

ServiceNow encourages customers to use the Idea Portal or Demand Management application for the intake of work. Both allow managers to create tasks that convert into Agile entities such as a story or epic.

If Innovation Management and/or Demand Management applications are installed, it easily formalizes the intake process for any agile work.

Now that I have all the information from the customer, I am ready to install Agile Development 2.0 application for PPM Adventure World. Let's take a look at the different plugins needed.

To install the Agile Development 2.0 plugins, navigate to System Definitions > Plugins, and activate the plugins required. All Plugins are shown below. 


---
Agile Development 2.0
–
Agile Development 2.0 plugin is the base plugin to activate Agile Development 2.0 application. It provides an agile environment for product-based or project-based efforts, using the Scrum framework. It offers flexibility to implement a pure agile approach or a hybrid approach using agile methods within a traditional project structure.

---

Scrum Programs
–
Scrum Programs plugin allows users to create and manage scrum programs and track the work of multiple teams working together. Scrum programs help to plan and track the work of multiple teams working together either towards a common short-term outcome or on an ongoing basis.

---

Performance Analytics Content Pack for Agile 2.0
–
Performance Analytics Content Pack for Agile 2.0 provides preconfigured Agile 2.0 Dashboards and can be found in the Dashboards module of the Agile Development application. Agile 2.0 Dashboards contain preconfigured dashboards with data visualizations that help improve the Agile processes and practices. The PA content pack for Agile 2.0 is found in the ServiceNow Store.

---
Agile Development v2 Mobile app
–
Agile Development v2 Mobile app allows the team members to track and update their stories and track sprints that they are part of, from their mobile device.



It helps users to create, edit, manage and track the status of stories and scrum tasks. It also lets users add work notes and attachments to a story or scrum task. Users can receive mobile notifications when the stories or scrum tasks are updated.

---

Agile Development 2.0 - ATF
–
Agile Development 2.0 –Automated Test Framework (ATF) Tests plugin provides the test cases and test suites that can be run on the Agile Development 2.0 application.



Also called Quick Start Tests for Agile Development 2.0, it validates that the application still works after making any configuration changes. For example, if you apply an upgrade or develop a new application, you can copy and customize these quick start tests to validate your instance-specific data. 


When you customize or make configuration changes, it is a best practice to create quick tests as well for the changes and make sure things are still functioning correctly. 



To find the agile tests, navigate to Automated Test Framework > Tests. Search against the package column for the records that contain agile to see the agile tests.

---
Agile Development 2.0 - Unified Backlog
–
Agile Development 2.0 – Unified Backlog plugin allows users to triage and maintain a centralized backlog containing records of different task types, such as defects, problems, incidents, and stories. 



A Product Owner can use a filter to define what records are related to their backlog. For example, enhancements or defects that match specific criteria.

---

# Roles
When we install the Agile Development 2.0 plugin, user roles are activated along with several other components. 

We must set up scrum teams by creating groups, adding group members, and assigning scrum roles to groups or group members.


Product Owner
–
Manages agile process and product backlog
Can move stories between product backlog and releases
Can create and manage epics, stories, products, releases, and teams

Scrum Master
–
Guides the team through the sprint to address issues that arise in the process
Can move stories between product backlog and releases
Can create and manage epics, stories, sprints, and team members

Scrum Admin
–
Can access all modules of the agile application
Can inherit any of the scrum roles to create, edit, or manage an agile element

Scrum Team Member
–
Works on the story in a sprint
Can create and manage scrum tasks
Can log enhancement requests and defect reports

Scrum User
–
Has read-only rights to the Agile Development 2.0 application
Can view all agile elements such as Stories, Products, Releases, and so on
Cannot create, edit, or manage any record types

---
The Agile Development Guided Setup wizard helps you create groups, add group members, and assign scrum roles.

---
Tables

The data tables are used to manage the agile process, represent releases, and represent product backlog items to be included in a sprint. These tables are installed with the activation of the Agile Development 2.0 plugin.

---


