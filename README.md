# Unit 18 PWA Homework: Online/Offline Budget Trackers

## Description

This is a progressive web application for tracking a single user's budget. It allows the user to enter information to track adding funds and subtracting funds and it keeps track of the balance. It also displays a graph of the additions and subtractions. If connectivity to the internet is lost while the app is being used, it will continue to collect new information and store it offline in the IndexedDB of the browser. When connectivity returns, it will load those stored changes into the online database to sync up the informaiton. When the user is online, it updates the online database in real time.

## User Story
AS AN avid traveller
I WANT to be able to track my withdrawals and deposits with or without a data/internet connection
SO THAT my account balance is accurate when I am traveling

## Business Context

Giving users a fast and easy way to track their money is important, but allowing them to access that information anytime is even more important. Having offline functionality is paramount to our applications success.


## Acceptance Criteria
GIVEN a user is on Budget App without an internet connection
WHEN the user inputs a withdrawal or deposit
THEN that will be shown on the page, and added to their transaction history when their connection is back online.
Complete

