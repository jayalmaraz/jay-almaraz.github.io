---
layout: default
title: Zapier Integration Roadmap
nav_exclude: true
---

# Zapier Integration Roadmap
{: .no_toc }
{: .fs-10 }

![Zapier x Campfire](./assets/zapier-banner.png)

We've been working on a Zapier App for Campfire. With nearly unlimited potential to integrate and automate workflows into other hugely popular and powerful applications, a Zapier App will be an exciting extension to Campfire's growing toolset.

_From Zapier's website_

> Zapier is an online automation tool that connects your favorite apps, such as Gmail, Slack, Mailchimp, and more. You can connect two or more apps to automate repetitive tasks without coding or relying on developers to build the integration. It's easy enough that anyone can build their own app workflows with just a few clicks.

This document covers the design and development of the Zapier App and integration principles that we are working toward.

---

## Skip To
{: .no_toc .text-delta }

1. TOC
{:toc}

---

## Our Philosophy on Integration

- We focus on Campfire
- We build Campfire to be the point of truth for your volunteer ops and impact
- We want you to do more
- We want to enable you to use tools that allow you to do more

## Why Zapier?
{: .fs-10 }

We are aggressively familiar with the importance of integrations. From experience building Orange Sky tech, integrations provide huge benefits to the operational capability of a team who uses many tools. Campfire is build for volunteer management, and has been designed to provide a fantastic experience to volunteers and managers in coordinating and delivering your organisation's mission. We focus on doing what we do best, and now we want to provide a solution that will allow your team to use Campfire's data with other tools to take your processes to the next level.

![Zapier trigger - action flow](./assets/zapier-flow.png)

Zapier was selected for our first integration project because it is connects with thousands of other web apps, straight out of the box. Zapier is designed to build workflows, and uses a trigger/action system to automate tasks in the background, leaving you even more time to focus on your mission.

[Read more about Zapier](https://zapier.com/how-it-works).

## Priority Triggers

We are pushing through the R&D phase and prioritising some critical triggers that will enable a major portion of needs in CRM integrations.

### Volunteer created

Triggered whenever a volunteer profile is completed. We see this as the most important trigger for CRM integrations. This trigger will allow contacts, records, and entities to be created or updated whenever a new volunteer joins Campfire.

The trigger will be broadcast after checkpoint 3 of the [onboarding flow](https://guide.campfireapp.org/docs/managers/configuring-your-onboarding-flow/#one-step-at-a-time) is passed, at the point where a volunteer has finished onboarding and had their volunteer profile approved.

| Primary data   | Secondary data  |
| -------------- | --------------- |
| User ID        | Program         |
| Volunteer ID   | Completed tasks |
| Date applied   | Approved by     |
| First name     |                 |
| Last name      |                 |
| Email address  |                 |
| Contact number |                 |

### Volunteer deactivated

Triggered when a volunteer is deactivated. The other side of the coin, being able to respond to volunteers being removed from Campfire is also critical to maintaining healthy data.

| Primary data     | Secondary data |
| ---------------- | -------------- |
| User ID          | Program(S)     |
| Volunteer ID     | Deactivated by |
| Date deactivated |                |
| First name       |                |
| Last name        |                |
| Email address    |                |
| Contact number   |                |

<!-- ## Future Triggers

After the priority triggers are stable and tested, we can start exploring all of the future possibilities. There is so much potential for creative and powerful workflows to follow. We'll be looking to connect with teams just like yours for ideas and opinions once we're ready to start prioritising and designing these triggers.

### Volunteer movements

### Activities and Programs

### Impact from activities

### Incidents

### Resources -->
