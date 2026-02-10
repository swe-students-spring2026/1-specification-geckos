# Specification Phase Exercise

A little exercise to get started with the specification phase of the software development lifecycle. See the [instructions](instructions.md) for more detail.

## Team members

[Simon Ni](https://github.com/NarezIn)

[Tsengelmurun EnkhOnon](https://github.com/murnbn)

[James Zheng](https://github.com/hyperjasm)

[Alejandro Fiestas](https://github.com/avf8449)

[Sarya Sadi](https://github.com/saryassadi)

## Stakeholders

#### Stakeholder 1 (User Type 1):
> Sandy Liu, a 21-year-old college student who always forgot to drink water but values hydration.

**Goals and Needs**
- Needs notifications that serve as gentle reminders rather than a forcing behavior, because she like to maintain a sense of autonomy.
- Hopes for a seamless verification system using NFC tags; for example, tapping her phone against an NFC sticker on her water bottle to automatically validate that she drank water.
- Wants to see friends’ progress on a leaderboard to feel motivated by a community.
- Needs the ability to customize her own pace and quantity

**Problems and Frustrations**
- Often simply forgets to drink water because she is hyper-focused on schoolwork.
- Frustrated by some apps that are too pushy and complicated to use, which causes her to disengage.
- Found some apps are too easy to manually click "complete" without doing the task, just like the "snooze" button. (Relates to the NFC sticker tap functionality)
- Annoyed by some apps that send too many notifications that are unrelated to keeping up her habits.

#### Stakeholder 2 (User Type 2 / Supervisor):
> Neil, a 31-year-old professional who wants to support his younger brother’s *6-pack work out plan*.

**Goals and Needs**
- Wants app for him and his brother to quickly check if each other is following their *6-pack plan* everyday.
- Needs to know exactly how long a supervisee has been inactive, not to push the supervisee but just to know that information, because he thinks "being lazy" is reasonable as schoolwork can be overwhelming sometimes for his brother.
- Needs to be able to switch between his own habit tracking interface and his supervisor dashboard without annoying logging out.
- He wants a system that requires proof to avoid arguments.
- prefer that the app allows to leave supporting comments in each log to keep supervisees feel motivated.

**Problems and Frustrations**
- Usually cannot go to the gym with his brother because of working but still wants a quick way to check in his little brother.
- Finds it hard to stay objective when a user claims they did a habit.
- Annoyed by apps that don't separate "My Habits" from "People I Supervise", leading to confusion.
- Worried about his and his little brother's data privacy when some apps ask for taking photos.

#### Stakeholder 3 (User Type 1):
> Harvey Li, a 21-year-old college student who sometimes forgot to drink water but want to cultivate the habit of drinking water.

**Goals and Needs**
- Wants to gradually develop the habits of drinking water through consistent reminder. 
- Needs an app that helps him to actively drink water regularly for each day. 
- Wants a system where he and his girlfriend can remind and supervise each other to drink water.
- Wants reminders that will not distract him during focused periods. 

**Problems and Frustrations**
- Gets so concentrated on studying that he forgets about water in take during the long studying sessions.
- Has the problem of converting the thoughts of drinking water into actual actions.
- finds it hard to track the amount of water he drank during the day and whether it meet the hydration goal.

## Product Vision Statement

> Our mobile habit-tracking mobile application helps people build consistent healthy routines through social verification, progress tracking, and rewards, while enabling supervisors to review activity, provide feedback, and support accountability through a transparent, structured workflow.

## User Requirements

**Habit Builder User (Type 1):**
- **Initial App Setup**

   - As a User, I want to create an account with my email, so that I can save my data across devices and protect it with my password.
   - As a User, I want to set up my profile, including name and profile picture, so that my friends and supervisor can recognize me.
   - As a User, I want to choose from a list of default habits, so that I can get started quickly.
   - As a User, I want to be able to create custom habits, so that I can track the ones that matter specifically to me.
   - As a User, I want to generate an invite link to send to a friend, so that they can become my Supervisor.
   - As a User, I want to set daily or weekly goals for my habits, so I can control the difficulty level.

- **Habit Tracking and Verification of Completion**
   - As a User, I want to receive a notification to do my habit, so I don't forget during a busy day and lose my streak.
   - As a User, I want to be able to customize the time of my reminders, so they fit my schedule and are delivered at an appropriate time.
   - As a User, I want to be able to actually validate my habit completion by tapping an NFC tag, so that I cannot get away with not doing it.
   - As a User, I want to be able to upload a photo as proof, so my supervisor knows I actually did the task.
   - As a User, I want to mark some simple habits as completed manually without verification, so that I can track simple habits that don't require proof.

- **Habit Progress, Motivation and Social**
   - As a User, I want to see a counter of my consecutive days, so I feel a sense of accomplishment.
   - As a User, I want to easily see a percentage bar of my daily goal, so I know exactly how much I have left to do.
   - As a User, I want to receive a digital medal or badge when I hit the milestone, so I can be motivated to maintain my habits.
   - As a User, I want to be notified on how a habit is benefiting me, so I remember why I am doing it and keep motivated.
   - As a User, I want to challenge friends to a streak competition, so tracking feels fun.
   - As a User, I want to see if my friends are keeping their habits today, so I have extra motivation to keep up with them.

**The Supervisor User (Type 2):**
- **Monitoring**
   - As a Supervisor, I want to accept an invite from a Habit Builder User, so that I can start tracking their progress.
   - As a Supervisor, I want to be able to toggle between my personal habits and my supervisor dashboard, so I don't have to log out or use another app.
   - As a Supervisor, I want to see a list of all the users I am supervising, so I can check everyone's progress quickly.
   - As a Supervisor, I want to see a "Last Active" indicator for my supervisee, so I know if they have stopped using the app.
   - As a Supervisor, I want to receive weekly reports, so I can track their long-term improvement rapidly.
   - As a Supervisor, I want to be notified when a user misses a habit streak, so I can encourage them to get back on track.

- **Verification and Action**
   - As a Supervisor, I want to view the photo or NFC proof provided by the user, so I can verify they aren't cheating.
   - As a Supervisor, I want to approve or reject a habit log, so the user stays honest.
   - As a Supervisor, I want to leave positive comments or encouragement, so I can provide emotional support to the user.
   - As a Supervisor, I want to be able to remove a supervisee from my list, so I can stop tracking them if we stop working together.
   - As a Supervisor, I want a screen where I can quickly verify the habits of all my supervisees at once, so that I don't have to enter each of their profiles individually.




## Activity Diagrams

_This image has a very high resolution. Zoom in however your want!_
!["Geckos Diagrams. We got 6 here."](diagrams/geckos_diagrams.png)

## Clickable Prototype

[Try Our Prototype here!](https://www.figma.com/proto/KRwNA0Iqkzp2W7oTEL9o3E/Geckos?node-id=2-2&t=NkjKaR9Wtc9tBUjP-1)