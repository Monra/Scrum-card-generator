# Scrum card generator

*Scrum card generator* is a simple card generator that is only based
on html and javascript. With no backend it can be run every where and
caching can be set to rock hard.

## Usage

The input is a six column based csv table with properties

    Card number,Title,User story,How to demo,Area,Estimate

at specified order.

## Columns

* `Card number` -- Card number of your choice that will displayed in the upper corner.
* `Title` -- Title of the card that just sums up what the story is about.
* `User story` -- The actual user story.
* `How to demo` -- How to demo describes which steps are needed to be made and which result is to be expected.
* `Area` -- An area if to group the story with.
* `Estimate` -- The estimate of difficulty and size of the story.