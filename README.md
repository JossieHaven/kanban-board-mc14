# Kanban Board

## Description

Module 14 Challenge - Kanban Board

Module challenge that provides the opportunity to practice Authentication with JSON Web Tokens (JWTs), as they are crucial for full-stack applications, since they provide a secure and scalable method for verifying user identities. They are compact, URL-safe tokens that encode a user's authentication data, allowing servers to authenticate requests. JWTs can inclue metadata and be easily verified and decoded, enhancing security while enabling seamless authentication across various parts of an application. The challenege includes adding authentication with JWT to an existing Kanban Board app. 

## Table of Contents

- [Description](#description)
- [User Story](#user-story)
- [Installation](#installation)
- [Acceptance-Criteria](#acceptence-criteria)
- [Link Deployed App](#link-deployed-app)
- [Github-repository](#github-repository)


## User Story

AS A member of an agile team
I WANT a Kanban board with a secure login page
SO THAT I can securely access and manage my work tasks



## Installation

1) npm install to get the app working on VSCode. 

## Acceptence Criteria

- GIVEN a Kanban board with a secure login page
- WHEN I load the login page
- THEN I am presented with form inputs for username and password
- WHEN I enter my valid username and password
- THEN I am authenticated using JSON Web Tokens (JWT) and redirected to the main Kanban board page
- WHEN I enter an invalid username or password
- THEN I am presented with an error message indicating that the credentials are incorrect
- WHEN I successfully log in
- THEN a JWT is stored securely in the client's local storage for subsequent authenticated requests
- WHEN I log out
- THEN the JWT is removed from the client's local storage and I am redirected to the login page
- WHEN I try to access the Kanban board page without being authenticated
- THEN I am redirected to the login page
- WHEN I remain inactive for a defined period
- THEN my session expires, the JWT is invalidated, and I am redirected to the login page upon my next action

## Link Deployed App
[Deployed App]()

## GitHub Repository
[Github-Repo](https://github.com/JossieHaven/kanban-board-mc14)