---
layout: single
author_profile: false
title: "Team NYC 2016 Fellowship Mid-year Report"
---

{% include base_path %}

## Executive Summary

The 2016 fellowship team in New York City is working with the Mayor’s Office of Operations to ensure all New York City residents receive all benefits to which they are entitled by supporting the caseworkers and social workers in their day-to-day service delivery. Our goal is to create a product that caseworkers use daily to help their clients. The product should have a great user experience, should be able to meet changing program needs and have the ability to be updated quickly and easily.

The way we are approaching these problems is through user centered design. We have conducted extensive user research, with the partnership of the Mayor’s Office of Operations and have committed to user testing all of our designs before implementing and shipping. By redesigning digital tools that service providers use daily, we hope to improve the user experience of government staff.

## Team

### Fellows

### City Partners

Ariel Kennan  
Alicia Mathews  
Matt Klein  
Tayyab Walker  
Chisun Rees  
Paul Chan  
Chuck Chan  

### Funders

Robert Wood Johnson Foundation  
Helmsley Charitable Trust  

## Focus Area

New York City has thousands of caseworkers and social workers that work through city agencies to assist residents of the city by helping them sign on to benefits, find housing, investigating cases of abuse, neglect and violence, among many other things. New York City is advanced in its use of technology, and is at the stage to continue to improve and reinvent digital services that are starting to show their age.

One such piece of technology is Worker Connect, a data integration system that provides access to a view-only of case file data for caseworkers and managers in accordance with all applicable laws and regulations. Worker Connect links administrative case data and document vaults across multiple New York City Agencies making them accessible through a single online portal. With Worker Connect, a caseworker is given a single place to search for a client to retrieve a consolidated view of select demographic detail, household data, service interactions and casefile documents from multiple City Agencies.

A key component of the Code for America partnership with New York city is to answer the questions: How can we make it easier and quicker for City workers to assist and deliver services to City residents using this platform? What does a mobile first version of this platform look and feel like and how does it operate?

![](http://img.keith.is/gOCi/Image%202016-06-07%20at%2011.05.02%20AM.png)

## Methods

Over three weeks, the research team comprised of a group of six people from both the Mayor’s Office of Operations and Code for America conducted 21 interviews with three different agency programs. The interviews were conducted in group settings with two to six social workers and two to four interviewers from Code for America and the Mayor’s Office of Operations.

The interview sessions lasted 60-90 minutes and ended in shadowing the worker as they did their job. Interviews began with introductions and framing the desired outcome of the user research. Participants were asked to discuss their titles, roles, and history with their agency, followed by walking us through their typical day or their last client case. The interviews concluded with participants discussing technology used through their typical day and the data they find important. During return trips, the research team conducted follow up interviews that included participatory design activities and usability testing.

> Placeholder for journey maps

## Findings

While conducting research, we came across a few themes around which we created product development goals.

### Access to More Data

Our research confirmed previous findings that access additional data sources would be used all of the social workers we spoke to. Adult Protective Services (APS), Automate the Schools (ATS), and Child Protective Services (CPS) data sources were most mentioned over both Health and Hospitals and Child Protective Services. Interviewees generally noted having a more holistic view of their clients and faster data discovery their primary motivations for wanting more data.

However, significant barriers exist to further data sharing and integration. Organizational politics, fears over data breaches, waiting for legal use case approval and improper use were frequently cited as the main reasons behind why agencies were reluctant to share data.

### Standardized Administration of Data

Currently, Worker Connect data providers curate their own data stores and user access privileges. However, these practices do not appear to be standardized across agencies. Agencies do not appear to have standard models for determining which city employees are able to access their data, what their level of access should be, and how long their access should last.

City agencies could benefit from establishing user permission levels with clear requirements, as well as segmenting their datasets into different tiers of privacy. Access to databases should be administered and monitored centrally, such that a city employee has a one-stop-shop of all data sources that are available. Having standardized policies such as these in place across agencies could lay the groundwork to reduce siloing of information.

### More Mobile Technology, Placed Appropriately

Smart phones were present in many of the offices where interviews were conducted, however they were most often provisioned managers and senior level staff. City agencies may benefit from a framework that helps evaluate which employees would be helped most by a mobile device based on the amount of time they spend working in the field.

Additionally, the city may wish to create a mobile devices playbook, which could outline use-cases, procurement, and maintenance of mobile devices for agencies considering a rollout of mobile technology.

> Placeholder for user group visualization

## Goals

Our products can provide great value to city caseworkers and social workers by increasing the number of people who have access to Worker Connect and who use it on a repeated, regular basis. In addition, they can provide value to New York City residents by increasing the number of people receiving benefits who need them. Measuring our impact in this area, we will look to the number of city workers logging on to Worker Connect, the number of new use case requests that come in and the usage statistics of the different user groups signed on. To help enhance some of the other outreach work the city is already doing, we also plan to make the list of resources city staff use to aid their clients.

### Impact 1: User Enhancements

1.  Make it easier and quicker for caseworkers to perform key tasks.
    *   Users verbally indicate that they prefer enhancements.
    *   Time-trials of search tasks take less time than similar tasks in Worker Connect.
2.  Create a system that caseworkers choose to use over alternatives.
    *   Usage statistics for our beta-release of Worker Connect, particularly daily active users.
3.  Create policy buy-in towards provisioning caseworkers with mobile devices.

### Impact 2: Improved Business Processes

4.  Create a workflow that makes the provisioning process faster.
5.  Increase the ratio of people who use the software compared to the people provisioned.

### Impact 3: Continuing Future Development of Worker Connect

6.  Increase organizational momentum towards a Worker Connet 4.0.0.
7.  Provide open-source recommendations that will make the development process faster and less expensive.

## Metrics

*   Number of users that stay active over time
*   Number of repeat/easily solvable help tickets
*   Feedback loop: micro surveys on Worker Connect that allow the user to give feedback
*   Number of people who share login information
*   Stats on incorrect/outdated information from data sources

## Features

### General User Experience

*   Refining the log-in process: Worker Connect staff reported that the majority of help tickets were related to log-in issues. Specifically, we would like to indicate if a user has been soft-locked or hard-locked out of the system, and what actions they should take.
*   Clear visual hierarchy: Using font size, layout, and other indicators to help users find information on the page more easily. These changes will occur across the application.

### Speed and Performance

*   Single Page Application: Worker Connect 4.0.0 will make requests to the server in the background so that full page refreshes are not required for each transaction. This will increase page load time and reduce loading “flashes” that a user might experience during a full reload.
*   Eager Loading: Begin loading client information when it is returned in the initial results list. This will reduce the amount of time that the user waits for the client profile page to load.
*   Caching: Temporarily store data from recently viewed client profiles in the browser so that they can be loaded quickly if the user returns to view the profile again.

### In-Product Learning

*   Improve contextual help information: Review and improve existing help content where necessary, implement a UI that will allow users of Worker Connect to access information more readily.
*   User-group information & data privileges: Create a user information dashboard where the user can see what user-group the belong to, a plain language description of what their use case entitles them to do, as well as the data sets available to them. This feature will help clarify Worker Connect’s role as a data broker, as well as help users understand what data they should expect to see returned in their searches.
*   Tutorial video: Create short tutorial videos that introduce new features and covers the basic tasks that can be completed in Worker Connect.

### Query & Search

*   More flexible age-range filter: Provide a selector for a variety of age-ranges when conducting a search by name. This will reduce repeated searches when the user does not have a specific age for the individual they wish to look up.
*   Indicate if the client’s address is a homeless shelter: Due to the high number of addresses attached to homeless shelters, Worker Connect does not display records associated with an address at an DHS shelter. This feature would add a warning if a user attempts to search an address that is a shelter and may not return results.
*   Address validation: Create a typeahead feature that provides a dropdown list of addresses as the user types.
*   Unified search: Consolidate search functionality into a dropdown and provide progressive fallback to four separate searches. Allows users to select the method by which they want to search either directly from a drop-down menu on the search bar, or by clicking to look up via a specific search. The intention of this feature is to reduce the number of clicks and keystrokes necessary to execute a search.
*   Replace hyphens in last-name search with wildcard: Searching names with a hyphen present in the last name currently returns erratic results. This filter will implement a regular expression that removes hyphens and replaces them with a wildcard operator before executing the search.

### Search Results

*   Sorting Search Results: A drop-down menu button that allows the user to sort a results returned by the Worker Connect back-end, by any field the user chooses.
*   Filtering results: Filter results returned by the Worker Connect back-end by age range, first name, gender, and location. Filtering returned results will prevent a user from having to initiate a new search if they find that their initial query returned too many results to scan quickly.
*   Clear visual hierarchy: Using font size, layout, and other indicators to help users find information on the page more easily. These changes will occur across the application.
*   Pagination: Add the ability for users to search through more than the current maximum of returned searches by paginating results.
*   Saving individual clients to a list: Use the browser’s secure local-storage (if enabled) to add individuals to an internal “seen” list. This would highlight profiles seen in the last 10 days while viewing searches.

### Client Profiles

*   Display client addresses on map: Provide geographic context for client locations by placing pins representing their most recent and past addresses on a map.
*   Text address from Worker Connect to mobile device: Allow city employees to easily retrieve directions to their clients by selecting an address to text to their phone, which could then be opened in a mapping application.
*   Group duplicate documents by default: Compile duplicate documents into folders that can be expanded for more information so that the user can see which types of documents are available at a glance. The most recent document would be available to be clicked on immediately, while additional duplicate documents could be seen by clicking further into the navigation structure.

### Business Process

*   Use case document cover page:. Many times, the person sending the use case to the legal review stage already has insight into how viable the user group’s case is. A simple, elegantly-designed cover page could be useful in summarizing the case and providing a signal as to how straightforward a case is.
*   Provide Updated Content for Worker Connect Training: Ensure that any changes to the Worker Connect interface are associated with training material that can be used upon launch.
*   Executive level WC aggregate dashboard: Build a dashboard the maintains up-to-date statistics on Worker Connect usage.

## Risks and Dependencies

Ability to deploy Worker Connect 4.0.0 remains uncertain: While we have identified a theoretical method of deployment, we are still uncertain as to whether we would be able to test our project on the Worker Connect production environment.

Worker Connect’s technology is at end-of-life: In meetings with the tech-team supporting Worker Connect, we have heard that the infrastructure is seven years old and nearing end-of-life. Without intervention, it’s unclear as to how long Worker Connect can feasibly maintained.

Worker Connect has not been integrated into agency business processes: Agencies are not proactively thinking about how to expand adoption of Worker Connect to their users. Many seem to be unaware that Worker Connect exists as a service. Agency liaisons act in a mainly passive role and may not consider onboarding new-hires or removing old users from Worker Connect.
