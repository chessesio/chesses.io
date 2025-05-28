---
layout: "../../layouts/BlogPost.astro"
image:
  url: "https://kssiqrs7mf.ufs.sh/f/7Yz5Dce19lBXf7aFYhGRs1qpZaPwM7zCdgVUEfoOjBb2uLmD"
  alt: "Redesigned Splash Screen and First Page"
banner: "https://kssiqrs7mf.ufs.sh/f/7Yz5Dce19lBXyYabp6un5Gz8XTDboAeN4uPxIg0p2qthvUYL"
title: "M-Kopa Onboarding Redesign"
description: "A look into how M-Kopa can improve their mobile onboarding process for new customers who enter their ecosystem through their mobile app"
pubDate: 7 Nov, 2020
tags: ["UX", "Mobile App Design", "Redesign"]
---

> M-KOPA is a connected asset financing platform that offers millions of underbanked customers access to life-enhancing products and services.

M-Kopa’s services include asset financing for household products such as solar lighting and smartphones, and loans for small businesses and small holder farmers.

I decided to do this redesign because I believe that M-Kopa’s current onboarding and zero state are likely to cause new users and perhaps existing users, to churn. The churn would be because they don’t understand the apps offering due to lack of context, if they are new to M-Kopa, or are not tech savvy, which is likely the case for M-Kopa’s target audience

I built my assumptions from their website, [m-kopa.com](http://m-kopa.com/), their [LinkedIn](http://linkedin.com/company/m-kopa-solar/) page and job descriptions from recent job postings, formed the foundations of my redesign of their onboarding process and zero state.

- M-Kopa’s customer acquisition is primarily through field sales and retail outlets
- The current app was intended to do account manage and make payments
- M-Kopa wants to grow the app to play a bigger role in their customer acquisition and support

Now that we have a little context, let’s get into the design challenge.

## Design Challenge

> **How might we create an intuitive onboarding experience for new M-Kopa app users and increase retention.**

## Users and Audience

M-Kopa’s audience is mainly the low income demographic in rural Kenya, who typically don’t have access to electricity or capital to finance purchase of basic household appliances and who have access to mobile money through a feature phone at the very least.

The subset of people addressed in this redesign is new users, who have little to no knowledge on the workings and offerings of M-Kopa and existing users who could potentially be up-sold to acquire more of M-Kopa’s different offerings.

## Scope and Constraints

The focus of this redesign was on the onboarding experience before a user logs in or registers

The most noteworthy constraints are that I restricted myself to only doing desktop research and therefore did this with the eye of an outsider looking in

## Process

### Framing the design challenge

The first step was to define scope. This is ensure that the view of the problem is neither too broad nor too narrow. The **outcome** was the design question, “How might we create an intuitive onboarding experience for new M-Kopa app users”

### Creating design brief

I then created my design brief, this included a more detailed definition of the problem, the audience, roles and responsibilities and the scope and constraints, all already touched on in this case study.

This is the point where a lot of the research went in and provides a guide to the ideation stage.

### Ideation

This is the point when I started creating the solution. It involved research into how other designers had solved this problem, followed by brainstorming and wire-framing different options before choosing the one I found most suitable

The **outcome** of the ideation stage was the wireframes that I then flesh out into mockups in the final phase of this exercise and a guide for copywriting of the products content

### Information Architecture and Copywriting

The next step for me is usually to structure how information will appear and write copy. I would describe my style as talking to you rather than talking at you, if you catch my drift. I like users to feel like they are having a conversation with the product.

### Design

The final part of the redesign process was to design mockups of the solution earlier wire-framed. I am most proficient with Adobe Xd, I however designed this using Figma just to learn how it’s different from Xd, because after all, curiosity is the foundation of every tinkerer. I also believe that design is not about tools but rather the work put in before you get into creating the mockups, so I’m always open to learning and using new tools, provided they are or can be a better option.

My mockup design process involve first identifying repeatable elements of the design, these then form components. An example of this is buttons, titles, body text, cards e.t.c. I then design these components before diving into designing every screen. This creates patterns that the users mind will intuitively recognize, creating a fluid experience. It also makes the lives of the developers handling the project a lot easier, since they can also build components they can re-use at different points of their development.

## Outcome

### Previous Design

Initially, the app started with a splash screen the straight in the apps home screen. When a user attempted to perform an action, say make a payment, they are then prompted to log in.

This choice of process in my opinion, does a disservice to M-Kopa. They have so much to offer their target audience but the app does very little to convey this. If you did not download the application with the explicit intention to make a payment to M-Kopa or manage your account, you automatically churn.

![Original screen designs](https://kssiqrs7mf.ufs.sh/f/7Yz5Dce19lBXI9Epjj2I4LWK6JZMxCnAplfkG0d9sh5btvTB)

### Suggested Design

There is an opportunity to create a flow that allows discovery of M-Kopa’s service at the very least, or convert a guest into a users and eventually convert a lead to sale. I came up with the following suggestions through the design process to to make the app better *(In order of which screen appears first)*

#### Language selector (A nice to to have)

Most of rural Kenya speaks their mother tongue as the first language, followed by Kiswahili then English. Allowing people to choose between English and Kiswahili can potentially greatly improve usability, and is a nice touch that might increase stickiness due to a more familiar language.

![Splash screen and language selection screen](https://kssiqrs7mf.ufs.sh/f/7Yz5Dce19lBXf7aFYhGRs1qpZaPwM7zCdgVUEfoOjBb2uLmD)

#### An onboarding flow informing users on what M-Kopa does and Why they do what they do what they do

Broadly speaking, I noticed three categories of customers; customers purchasing household appliances through M-Kopa, small businesses getting loans to grow their business, and farmers using M-Kopa eVouchers to purchase farm inputs, all of whom purchase lighting products as gateway into M-Kopa’s ecosystem.

I added three informational screens after the splash screen to give each of these categories, telling each the benefit of partnering with M-Kopa to enhance their lives.

![Informational screens](https://kssiqrs7mf.ufs.sh/f/7Yz5Dce19lBXI9Epjj2I4LWK6JZMxCnAplfkG0d9sh5btvTB)

#### Displaying the login form before the application home screen with an explore section

Since the application only lets you manage your account, make payments and contact customer care, there is no need to expose it’s functionality before a user logs in, I therefore added a sign in sections before you get to the home screen.

After seeing the information screens, I anticipate users wanting to know what M-Kopa can do for them as individuals. I added an explore section to answer this question. When a user scrolls down on the login page, they will see the different products and services M-Kopa has to offer them. The intention is that this nudges closer to a purchase decision.

![Login screen](https://kssiqrs7mf.ufs.sh/f/7Yz5Dce19lBXcuRRDg8Hk3jDaf4s9A2ePu6FnUSyzCH7GNmY)

## Parting Shot

I believe the new onboarding flow is more engaging and creates a connection with the user as it tells them, ‘what is in it for me’ and when they understand they value they can derive, they are more likely to to make use of the app rather than discard it.

What do you think about this case study and redesign? Is there anything you’d do differently? Let’s get in touch and share, email me at chessesiokibet@gmail.com. I’d love to hear about your ideas.

*Disclaimer: I do not have any relationship with M-Kopa. These are strictly my thoughts on how they could serve their customers better. The M-Kopa logo is property of M-Kopa Solar. It’s use is strictly to create a realistic depiction of the redesign. The images used were derived from the* [_M-Kopa website_](http://m-kopa.com/)
