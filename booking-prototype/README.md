# Booking journey — annotated prototype

A working prototype of the askpaul booking journey, built as part of a UX and
accessibility audit of the live system at `booking.askpaul.ie`.

Open `index.html` in a browser. Nothing to install, no build step, no network
calls — it is a single self-contained HTML file.

## This is not the booking system

It only looks like it. Every appointment, adviser name, reference number and
list of available times in here is generated in the browser for demonstration.
No booking made in this prototype reaches anybody, and no data leaves the page.
The payment step is not reproduced.

## What the numbered markers are

The small numbered circles are design notes. Each one corresponds to a finding
in the written audit and explains what the prototype does differently from the
live system, and why. Click a marker to read it; the **Notes** button at the
bottom right hides them all if you would rather see the interface on its own.

The numbers are the finding numbers from the audit document, so note 24 here is
finding 24 there. Where one finding produced several separate changes they are
lettered — 18a, 18b, 18c.

## Desktop and mobile

The switch at the foot of the page renders the journey at 390 × 844, the
logical size of an iPhone 14/15, inside a real viewport rather than a narrow
column — so the responsive behaviour is the genuine one.

## Demonstrating the failure states

Some of the audit findings are about what happens when something goes wrong,
which is hard to show in a prototype that always succeeds. Three buttons marked
with a dashed border trigger those states deliberately:

- **Preview: the service list fails** — on the first screen
- **Preview: the server fails** and **Preview: the request never answers** — on
  the date and time screen

## Status

Audit measurements were taken against the build live on 24 September 2026. The
live system is deployed frequently, so specific measurements in the notes may
have moved on. The prototype is a proposal, not a specification: several
changes in it are design decisions that still need agreement.
