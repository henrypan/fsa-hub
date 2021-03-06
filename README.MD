# #thehub
> Revolutionizing technical education.

We believe every city in America needs a hub for community-driven technical education. The Full-Stack Apprenticeship is a focused, repeatable educational program to teach full-stack development. Build skills through open-source projects. Mentorship for developers of all stripes & skill levels. Pairing would-be entrepreneurs with technical cofounders and teammates. Community structure, accountability & leadership at the local level. 

![](fsa.png)

## Installation

Download on Expo: https://expo.io/@fullstackapprentice/thehub

## Current Functionality

#thehub offers a way to access the FSA Knowledge Base & a 60pg ebook called 'The Blueprint' to lay out the journey for somebody looking to become a full-stack developer.

## Release History
* 0.1
    * Blueprint Edition Versioned & Released

## Contributing

1. Fork it (<https://github.com/yourname/yourproject/fork>)
2. Please use yarn for installing and adding dependencies.
3. Create your feature branch (`git checkout -b feature/fooBar`)
4. Commit your changes (`git commit -am 'Add some fooBar'`)
5. Push to the branch (`git push origin feature/fooBar`)
6. Create a new Pull Request

# Branching
The default branch is develop, while production releases are merged to master.
All new work should start as a new branch from develop, with merge requests created roughly 1:1 to ticket #s
We're following the git-flow model:

feature/TICKET_OR_ISSUE_NUMBER (feature/#43)
bug/TICKET_OR_ISSUE_NUMBER (bug/#102)
release/VERSION_NUMBER (release/0.1.2)

## Community Sprint Planning, Standup & Retrospectives

The FSA believes that people generally learn best by hopping in & contributing useful code. Reading books is great, but you can get stuck in 'tutorial hell' and not actually make any progress. The key towards developing competence (and mastery) is time spent on your craft in a useful, professional capacity. That is why we hold the opportunity for community members to participate in a sprint planning (and retrospective) meeting for our open-source project called #thehub - to simulate the experience of working on an engineering team, to give you practice estimating your ticket items, and giving you a structured timebox to achieve your goals.

Requirements are simple:
- Only pick the GitHub tickets you believe you can reasonably accomplish in the duration of the weekly sprint.
- You must commit to attending the sprint retrospective that following Friday, sometime between 4-8pm for 30 minutes (will work out schedule amongst the group). This is to compare your initial estimates against the actual time taken, and to talk about what we can do from a workflow and process perspective to improve as a development team.
- You must commit to attending sprint 'stand-up' meetings on Tuesday & Thursday sometime between 5-8pm (or in the am if that works best) - like a real stand-up meeting, it should only last 10 minutes and is an opportunity for professional counsel & accountability. Blocked on something? Stay on the call after the meeting to talk it over.

We will be meeting on Google Hangouts, the link is here: https://hangouts.google.com/call/DD7mY82pQKuHkLlrQzfHAEEE.

# Directory Structure
## fsa-cms
This is where our Sanity.io powered Content-Management System lives.

## react-web
This is where our React application lives.

## react-native-expo
Where our React-Native application lives, built to work together with the React-Web repository.

## fsa-db
Where our PostgreSQL & serverless functions live.



