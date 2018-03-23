---
author: p3trk
cover: Picture-3.jpg
date: 2018-03-25
title: Metrics for Agile Teams Supporting Legacy Applications
categories:
  - Blog
  - Agile
---

Recently I've been working with a team who are supporting (and developing against) a legacy service which affects the daily lives of millions of people. It’s old, and made up of many applications and a couple of huge monoliths with plenty of complexity everywhere. Most things about this service are difficult. It’s tough to develop, tough to test, tough to release, tough to fix bugs (which are plentiful) and tough to feel like you’re making a difference day to day.

We’ve done a lot to make the process more bearable (by looking at our [ways of working](https://www.gov.uk/service-manual/agile-delivery/core-principles-agile) but it hasn’t really translated into more frequent releases of high-quality, valuable software to our users.

To help us focus our improvement efforts on user value and pace of delivery, we’re looking at a new set of metrics. This team is using scrum so you’ll see references to story points but you could adjust these for a more kanban world by counting tickets.

Here they are:

## Deployment time
How long does the average successful release take to perform? Besides making our releases faster and easier, looking at this metric has the added benefit of forcing us to get really clear on what a release is (and isn’t) when _exactly_ does it start? And when is it “finished”?

## Time between successful releases
How often do we complete a successful release? By dividing the number days between our first and latest release by the number of releases, we have an average number of days between releases. Again, this metric forces us to be clear on our shared definition of a “successful release”.

## Release success rate
It can also be useful to look at rolled back releases or "release attempts”. Divide the total number of attempts by the number of successful releases to get your success rate. As before, do we have a shared understanding of the criteria for cancelling or rolling back a release?

## User-facing points per sprint
Ideally, your definition of done ends with features being deployed to production at the end of each sprint. This isn’t always possible. You may also have a number of technical tasks in the backlog which don’t directly contribute to user-facing stories (e.g. infrastructure improvements, minor hot-fixes, build-process automation, etc). Therefore, rather than simply measuring how many points get “burned down”, we want to ask “What’s the average number of business/user-focused story-points (on average) go into production each sprint? Even if you don’t release the features you build in each sprint, this metric will keep you focused on shipping valuable features on a regular cadence and give you a measure of how much gets out to users in a given time box (e.g. a sprint).

## Unplanned Work (Quality)
How many story-points of unplanned "showstopper" work are getting introduced into each running sprint (thereby taking us off of planned work)? What should our target be?


There are lots of metrics you might choose to use in an agile team. We’re using the ones above to help us focus on improving our code quality and our build & release process. You may only need to look at one or two of these to make huge improvements. I’d love to know what you think! Have you tried these? What would you change or add? Any pitfalls or perverse incentives here? Please [contact me](/contact) with your ideas and feedback.

<!--https://unsplash.com/photos/yD5rv8_WzxA-->
<!--small>Photo by Nick Hillier on Unsplash</small-->