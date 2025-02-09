---
layout: post
title: "Designing caseworking systems meetup #2"
date: 2018-10-10 00:00:01 
categories: gov
---

Over the last year I organised two meet-ups for people designing caseworking systems in government. Previously I’d hosted write-ups of the events on a dedicated site (https://cross-gov-caseworking.herokuapp.com) but as that site is password protected (because reasons) I thought it would be better to move over the write-ups of the events to Medium for better visibility.

See the write up of the first meet-up here. Also Andrew Travers did a nice [complementary blog post](https://trvrs.co/journal/case-working-and-the-user) about this meetup.

In March 2018 I ran the second designing caseworking systems meet-up at Newspeak House, London.

Below are some notes from the day.

Big thanks to Caroline Trimm, Rosie Cowling and Lynne Roberts for the hard work taking notes.

## Agenda

- 11:00–12:45: Talks
- 12:45–13:45: Lunch
- 13:45–16:00: Unconference

### Morning — Talks

#### Welcome by me

We should talk more about designing and building internal systems. About half of our work at Home Office seems to be on case-working systems.

But there’s a reluctance to speak about internal systems — some I think from a fear of exposing our decision-making processes.

But if we don’t talk about these things, we’ll lose them. We can save more time and money by talking about these things more.

There’s a tendency to outsource internal systems. Why can’t we get to the point where we have a starter kit where anyone working on a caseworking system can use — one stop shop with guidance and code in there to help people get started?

People might think ‘we’ll wait for GDS to do something about this’ — but we don’t need to wait for them to do it, we in departments are the ones who are doing it, so we need to surface that as much as possible.

I made a website after the last meetup that catalogues screenshots of different caseworking tools for designers to reference.

#### Chris & Joe from DWP, talking about their work in Universal Credit to make case management easier

There’s two main user needs for Universal Credit

1. making sure people have enough money
2. getting people into work/more stable work

There are around:

- 400,000 claimants
- 9,000 agents
- 30 service centres
- 268 job centres

There are different user roles of the caseworking system

- Work coach
- Case managers — do all the stuff to make sure people get paid, answer questions people have about getting a job
- Decision makers — person that decides whether someone is eligible for a benefit or not

Goals for work coaches

- Making sure they understand someone’s situation, where they are at with their claim
- Knowing about something critical that might change how you support someone

Problems with caseworking system

- Content is poorly organised
- Actions are poorly labelled
- Analytics on case working dashboard — 2 of the 20-odd sections were used 66% of the time (Internal case history, looking at claimants account).
- There’s a tendency for dashboards to have poor information hierarchy.
- No persistent navigation — adds seconds to each action, which all adds up.
Some things in the system are rarely used, if ever

Consequences

- Agents miss important things that has a negative effect on claimants
- It just takes longer to do things, takes a long time to learn how to navigate the system, they’ve seen agents creating their own glossary of terms
- It’s hard to add new functionality (like accessing a payment statement to see what claimants are getting paid)
- We did three rounds of card sorting, and five rounds of usability testing

We designed a prototype.

- There was no categorisation of recent history — new design divides a claimant’s history into blocks.
- We added labels for users to quickly glance at what an entry into the history is about
- Issue of misinformation as different users are using different parts of the system
- Able to filter history as well
- Agent can ‘pin’ important notes — they appear on the claim overview
- About surfacing vulnerability — important that caseworkers can see this information
- Notes were becoming less relevant over time because markers were getting lost, making a case difficult to keep up to date over time
- Work Coach and Case Manager have different needs most of the time, with occasional overlap
- Notify upcoming things
- Preview content
- Need to surface important information
- Provide single source of truth by giving contextual guidance
- We found that there is poor internet connectivity in job centres — it’s important to have a light page load.
- Their changes resulted in 20% reduction in pageviews (less jumping around pages).