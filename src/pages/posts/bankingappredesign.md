---
layout: "../../layouts/BlogPost.astro"
image:
  url: "https://kssiqrs7mf.ufs.sh/f/7Yz5Dce19lBXk1ktk5Wx4dLJmDV12vRAZMlcCIoPy905SGap"
  alt: "Redesigned Home Page"
banner: "https://kssiqrs7mf.ufs.sh/f/7Yz5Dce19lBXTMeBiV7IXctkUozwdL9ZA3Cf0G6EyHMNb4ra"
title: "Redesigning My Banks App: Making Sense of the Maze"
description: "A redesign of a banking app I rely on but frustrates me everytime I use it."
pubDate: Nov 15, 2020
tags: ["UX", "Mobile App Design", "Redesign"]
---

## Intro

A poorly designed application is like a maze, one where when you get lost, you have to go to the beginning and start again. This is how I’d describe my banks app.

I don’t remember the last time I visited an ATM, or even used my debit card for that matter. This is because I can use an app to do everything I needed a card or ATM for. I guess that is a complement to the magnitude of Kenya’s mobile money industry. At the same time, there isn’t a more frustrating app to use than my banks. I liken it to an early morning jog at the beach, at sunrise, the views are beautiful, and a little exercise is always good for you, but jogging on sand makes it more difficult than it needs to be. I say this because the app does all I need it to do, I can withdraw money to my mobile money, or send it to another account, but doing it is always unpleasant, even after almost 2 years of using it.

This article looks at what aspects of the apps design makes using it so frustrating and how I would cure it, taking a look at the process by which you transfer money to mobile money, which is what I do the most. It’s a bit selfish to only look at what I do most, but that’s where my biggest pet peeves lie, and where a remedy would create the most impact for me. Mobile money is also the channel through which most Kenyan’s spend their money, outside cash, I’m making an educated guess that this would also impact a lot of other users.

## The Problem

The fundamental problems with the application lie in three key areas, its information architecture, use of modality and visual hierarchy.

There are also unnecessary steps riddled throughout the apps user journeys, some of which I will cover.

Let’s dive in!

### Shallow Hierarchy

The first problem, and perhaps the root to all the others, is the organization structure used on the app is too shallow, this has lead to its home page becoming one huge menu, where you potentially have to look at all the items before you decide what to press. From my analysis, there is only one layer of hierarchy under the homepage, save for some child modals used to add information to a process, like adding a modal to add recipients when sending money. This robs users of the opportunity to create a mental map of app’s features that would make navigation natural immediately, or after a few uses.

![There are 13 ungrouped menu item on the homepage before opening the hamburger menu](https://kssiqrs7mf.ufs.sh/f/7Yz5Dce19lBXXex47WGTN0isTuCmyl1B5fXVbtpvO8IJ74WR)

_There are 13 ungrouped menu items on the homepage before opening the hamburger menu_

A good organizational scheme is one that allows its users to understand where they are on the application and use context they find to navigate to the information they need or where they can achieve a task intuitively.

Information should be grouped in a logical way that allows users to naturally move around the application, and navigate their way back to familiar parts if they get lost. This problem is aggravated by the apps implementation of modality, which I cover next, together with screenshots of the screens to give you better context.

### Improper Use of Modality

As already mentioned, a shallow hierarchy is implemented in the app, on top of this, every menu item opens a main window. The problem this creates, based on their implementation, is once you start a process, you can’t navigate back to exit. Once you have opened a menu item, you have to tap the home button on the top right of the screenshots below to go back to the home page and start afresh, which can be very frustrating.

![Transfer to mobile money screens: The 1st screen is the main page, the 2nd and 3rd screens are modals to add a recipient. The last is a confirmation screen.](https://kssiqrs7mf.ufs.sh/f/7Yz5Dce19lBXNm5sOuBtD1FxdGq0IQugrsWVUY4efc6wlaJ9)

Transfer to mobile money screens: The 1st screen is the main page, the 2nd and 3rd screens are modals to add a recipient. The last is a confirmation screen.

Good use of modality would suggest that home page be the main window, with other processes that originate from it being its children. This would create a better navigation system improving user interaction with the app. Also, modals should also be used only where necessary, the extra modal screen titled one-off transfer, for example, is unnecessary.

### Subpar Visual Hierarchy

Good products allow us to interact with them naturally, making it easy to understand them and navigate around them. This is not the case here

![How visual hierarchy has been implemented throughout the app](https://kssiqrs7mf.ufs.sh/f/7Yz5Dce19lBXBTf1m5QK9h3H48GpNlLfwgMukQcRnUT2xevO)

How visual hierarchy has been implemented throughout the app

The blue section doesn’t tell me that I should interact with it, in fact, before I embarked on this case study, I had never interacted with content in this section of the app, and if I had, it would reduce a great deal of frustration. For example, you don’t have to enter a recipients phone number if you change the transaction type, assuming that you have saved them as a recipient before. They appear as shown in the second screen. Instead, I’m always forced to the third screen and enter all those inputs whenever I make a transaction.

Proper implementation of visual hierarchy could have saved me a lot of time over the period that I’ve been using this app, and more importantly, saved me a lot of frustration. I probably wouldn’t be writing this now if visual hierarchy was better implemented.

### Unnecessarily Long User Journeys

Last but not least, some process, I believe, are unnecessarily long. A case in point is the adding recipient process I just mentioned. To add a beneficiary, saved or not, you have to open a child modal, this lets you select saved recipients, if they’re saved, or open another child modal to add the recipient. All this is unnecessary since the only information that is needed to technically and legally achieve sending money to a mobile money account is its phone number. Aspects such as name can also be retrieved at the verification stage for users to confirm. Avoiding this would save users a lot of time and frustration too.

## The Fix

### Better categorisation for better organiSational hierarchy

The primary features of this app can be categorised into four main groups; **account management**, like checking balances and viewing transaction history; **transfers**, which is mainly sending money out, but includes money coming in; **paying bills**, like utility payments and over the counter payments at shops, restaurants e.t.c; and **support**, including all requests you can make to the bank through the app.

I would use these as four as the basis for the first hierarchical layer, with associated tasks nested in each group. Account management, transfers and paying bills are perhaps the main tasks people would use the app for, so I would make these and home page, the non-modal screens and main screen respectively, and place them on the bottom navigation.

Using transfers as a case study, you can transfer money to mobile money, a local bank account or internationally. These can be nested in one group in a transfer page, accessed through the bottom navigation.

![New transfer to mobile money screens.](https://kssiqrs7mf.ufs.sh/f/7Yz5Dce19lBX23fdhlNoK6ZlIAVqjQSCyatWYO7G0cJsgUMr)

New transfer to mobile money screens

Grouping information like this will help make navigating the app easier as users can spot and remember patterns better, as well as remedying the improper use of modality highlighted earlier.

### Decluttering the home page

I’d also use the home page as a quick access section, showing snippets of what you can do inside the other section i.e account management, transfers and pay bills. In this case, from the home page, you can enter an accounts page through the card, add an account you regularly send money to in the quick send section, and some common bills, as well as the ability to add more in the pay bills section. You can also view your most recent transactions. Doing this also gives the user an idea of what is in the other pages so that they can make mental links to them as they continue to use the app.

![New home screen](https://kssiqrs7mf.ufs.sh/f/7Yz5Dce19lBXk1ktk5Wx4dLJmDV12vRAZMlcCIoPy905SGap)

New home screen

### Better visual hierarchy

I would also cease the use of the blue section covered in ‘Subpar visual hierarchy’ outside page titles, to show users that is content they should interact with. This is best illustrated by looking at the transfer to mobile money screens on the redesigned UI.

The mobile money page also only needs one page since their is no real need for the extra modal screens.

## Parting Shot

It’s telling that I complain about the app, yet I continue to use it. Ultimately, it provides more convenience than pain, which might mean that it’s already good enough and it doesn’t need more work. But I would argue that it’s only a matter of time until someone else reaches me and others like me, with the same convenience as well as a pleasant experience, and without a doubt I would churn. It’s important that businesses ensure their service delivery is of high standards to ensure customer loyalty and secure future profits, and that is exactly what good user experiences do, build a relationship with customers that ensures they stick, and they stay relevant.
