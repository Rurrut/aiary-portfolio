# Aiary

A daily planner and activity log I built for myself.

[한국어 소개](README.ko.md)

![Aiary mobile timetable](assets/timetable-demo.png)

The timetable puts the plan and what I actually did in the same view. Each hour is split into six 10-minute cells. On a phone, I can swipe across cells to log an activity instead of starting and stopping a timer or rebuilding the rest of the day by hand.

## Why I started

Most planning tools felt unintuitive or took too much effort to maintain. I kept going back to paper. While learning to build small tools with AI, I realized I could make a planner and log that worked the way I already used them on paper.

I like planning, but I am not always good at keeping up with the plan. The part I value most is being able to record what happened and let the remaining schedule adjust around it.

## Product decisions

- **Show plan and actual time together.** A day is easier to understand when the intention and the record are side by side.
- **Make logging a gesture.** A swipe selects a time range; choosing the activity and ratings should take only a few taps.
- **Adjust only what is still ahead.** A late activity can change later plans while completed and current plans stay where they are.
- **Keep a bedtime target.** Flexible gaps and activities can absorb delays before the schedule gives up on that target.
- **Work without a connection.** The phone keeps its own schedule and records. Sync is an extra path, not a requirement for daily use.

## What exists today

Aiary has personal Android and Windows builds. The phone can plan and record offline; it can also sync with the PC over the same Wi-Fi. Daily records can be exported to Notion in a form that is easier to review and use with AI tools.

This is still a personal prototype. The automatic adjustment rules reflect one routine and need to become configurable before the app can work well for different people. Weekday and weekend routines, calendar integrations, and broader testing remain open work.

## How I used AI

AI helped me implement and debug the app. I supplied the routines, described what felt cumbersome, tried the changes in daily use, and chose how the schedule should behave. The product decisions came from that cycle of use and revision.

## About this repository

This is a product case study: it contains the project story and a UI image, not the application source or installation packages. The earlier public prototype and its releases are separate; this portfolio copy does not withdraw files that were already published.
