# Product Requirements Document (PRD)

## Project: Mini Poll / Voting App

### Overview

A lightweight web app where users can create polls, vote, and view results in real-time.

### Goals & Objectives

- Allow users to quickly create a poll and share it.
- Enable participants to vote easily without account setup.
- Show live poll results in a clear visual format.

### Target Users

- **Poll Creator:** Someone who wants quick feedback (teacher, event host, small team leader).
- **Poll Voter:** Anyone with the poll link, no login required.

### Core Features

#### Create Poll
- User enters a poll question.
- User adds 2–5 answer options.
- A unique poll link is generated.

#### Vote on Poll
- Voter selects one option.
- One vote per device/session.

#### View Results
- Results update in real-time.
- Displayed as percentage + bar chart.

### User Stories

- As a poll creator, I want to share a poll link so that others can easily participate.
- As a voter, I want to vote without logging in so that it's quick and easy.
- As a voter, I want to see results instantly so that I know how others responded.

### Acceptance Criteria

#### Scenario 1: Creating a poll
- Given I am on the homepage
- When I enter a question and 2+ options and click "Create"
- Then I should get a unique poll link

#### Scenario 2: Voting
- Given I have a poll link
- When I select an option and click "Vote"
- Then my vote is recorded and I cannot vote again

#### Scenario 3: Viewing results
- Given I am on a poll results page
- When votes are cast
- Then I should see the results update in real-time with percentages and bars
