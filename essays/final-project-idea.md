---
layout: essay
type: essay
title: "Final Project Idea"
date: 2023-10-30
labels:
  - Software Engineering
  - Meteor
---

## Overview

### The Problem

Electricians are required to keep track of the cables that are installed as part of a building project. This information is used to create as-built drawings that are used by the building owner to maintain the building. The information is also used by
the electrician to create invoices for the work performed. Currently the information is recorded in spreadsheets or on paper. This information is not easily accessible by the building owner in a way that is conducive to creating a Building
Information Model (BIM).

### The Solution

Introducing CableTrack, a web application that allows electricians to keep track of the cables that are installed as part of a building project. The electrician can enter the cable information into the application as the cables are installed. The
building owner gets the information they need to maintain the building.

## Mockup Page Ideas

* **Landing Page** - Generic or Branded to Company, if the Edit Company Page has been completed.
* **Sign In Page** - Sign in to the application.
* **Sign Up Page** - Sign up for the application.
* **Sign Out Page** - Sign out of the application.
* **Edit Company Page** - Edit the company information. Administrators Only.
* **Edit User Page** - Edit a user. Administrators can assign Roles to users.
* **Edit Project Page** - Edit or Add a project. Administrators/Project Managers Only.
* **Project List Page** - List of projects to which the user has access.
* **Edit Cable Page** - Edit or Add a cable.
* **Cable List Page** - List of cables for a project.
* **Add Cable Pull-In Page** - Add pull-in data for a cable.

## Use Case Ideas

### Initial Setup

Administrator uses default account to sign in for the first time. They create a new account for themselves and delete the default account. They fill out the company information. They invite other users to join the company, assigning them roles as
needed.

### Adding a Project

Administrator or Project Manager creates a new project. They add the project information. They add the known cables that will be installed as part of the project.

### Pulling a Cable

Electrician signs in and selects a project. They select or add a cable and add the pull-in information.

## Beyond the Basics

Once the basic functionality is implemented, here are ideas for more advanced features.

* Add Continuity Test Data to Cables
* Add Megger Test Data to Cables
* Export Open BIM Data to IFC
* Import Project/Cable Data from Comma Separated Values (CSV) File


## Authors
Aaren Orquia, Andrea Jans, Ben Crawford, Matthew Yamamoto, Mikhail Shkaralevich, and Ursula Nichols 