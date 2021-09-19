---
layout: post
title: Three things you do not have to consider using story point estimation
image: /assets/posts/storypointestimation.jpg
description: All in all there is a lot of value in doing story point estimation with planning poker with the entire team. Done right it will give us increased understanding of what the story is all about, velocity from previous sprints to use when establishing capacity for coming sprints as well as less focus on time and how to keep everyone busy.
date:   2021-08-26 20:20:49 +0200
categories: post
---
![story point estimation](../../../../assets/posts/storypointestimation.jpg)

- How much work is remaining and how long time it will take
- Resource planning to make sure everyone in the team are occupied
- Common understanding of what the story is all about

During a discussion around planning in a software development team we come to talk about how hard it is to estimate how many story points that remains on the stories that will spillover to the next sprint. This is a common misunderstanding of how story points should be used. 

## Capacity of future sprints

One of the reasons why teams pick up story point estimation is because they would like to understand their capacity in terms of how many of the stories fits in a sprint considering the size of them in story points. To make story points useful for this we need to work with them in a good and structured way. Stories are refined and estimated using story points and the story point estimation is a whole team exercise. It is normally performed using planning poker[^1]. The estimate that a story gets should not be changed and when a story is done all story points of that story is added to that sprints velocity.

>When a sprint ends and a story is not done, zero points are are accounted for and the whole story goes into the next sprint along with all its story points (if it is still prioritized in the sprint planning).

It is not possible to know how much of the story, or complexity of the story, that were completed last sprint and how much that remains for the coming sprint. Looking back at the velocity of the completed sprints we get an idea of what the capacity of the team is. This is not a pure mathematical exercise.

> The capacity for the coming iteration can be made based upon the velocity of the recently closed iterations together with a judgment from the team. Is there is anything else that affects the team capacity?

## How do all the other work affect the capacity?

The stories that we are estimated assumes to be created to deliver some kind of value to the customers. This is not the only thing that is worked upon during a sprint. I will touch upon a few different kind of work types and explain why they should not be stories and how that is managed from a capacity point of view.

Bugs, it could be hard to know how many bugs that will be reported the coming sprint, but the best assumption is that it will be roughly as many as in the previous sprint. The same reasoning goes for for example support and line meetings. There is no major differences between the situation in the previous vs future sprints that might affect capacity, i.e. how many story points of stories that is the capacity going forward.

| Previous sprint | Current sprint       | Next Sprint      |
|:--------------- |:-------------------- |:---------------- |
| Refinement work | Development and test | Support and bugs |

Use only story point for the work from definition of ready (DoR) and definition of done (DoD). Refinement work is done when DoR is fulfilled and DoD should describe when a story is done, still we need to support and fix bugs after DoD. These different work types exists in all sprints with a similar distribution and that is why it is built in to the system and we only need to estimate stories.

## The main benefit of story point estimation

Some teams abandons story point estimation and scrum since they feel it takes unnecessary time and effort. Instead they use kanban to manage the flow of stories. It might be the right thing to do. It depends... When I ask teams about how they gain and share understanding of the stories after this change they normally do not understand why I ask the question.

> Story point estimation done with planning poker not only gets us the estimates but also an increased understanding of what the stories are all about

This is far more important than the estimated story points.

## Summary
All in all there is a lot of value in doing story point estimation with planning poker with the entire team. Done right it will give us

- increased understanding of what the story is all about
- velocity from previous sprints to use when establishing capacity for coming sprints
- Less focus on time and how to keep everyone busy

***

[^1]: [Wikipedia: Planning Poker](https://en.wikipedia.org/wiki/Planning_poker)
