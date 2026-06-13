# 4. Pop-up Search Feature

Date: 2026-06-13

## Status

Accepted

## Context

Users may have many events in their planner and wish to find an event quickly through a search feature. Without a search feature finding specific events, especially if the user forgets when it is, could be very dificult.

## Decision

This feature will implement a pop up search section to allow users to search for events by name. This pop up will open upon clicking on the search button and display an input box. Upon u=entering a name into the box a list of events containing that sequence of characters will be displayed. The date(s) associated with each event will be displayed to the right of the event name to allow for a more precise selection.

## Consequences

This feature will make it easier to find specific events through a targeted search instead of having to look through a list of events until the user finds the one they are looking for. It will provide a challenge for implementation with considerations to case matching, mispelling, and adding a pop-up screen.
