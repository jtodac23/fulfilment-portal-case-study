# Component Fulfilment Portal — case study

A working walkthrough of a shared delivery portal I designed and built: a global lift
manufacturer's engineers need components on site the same day, and the logistics side has to
get them there with a record both companies can read afterwards.

**Live page:** https://jtodac23.github.io/fulfilment-portal-case-study/

## What it is

One self-contained HTML file. No build step, no dependencies, no server. Open it from disk
and it works offline; the only external reference is a web font that falls back cleanly.

It is not a write-up about the product. It is a reconstruction of the product, running:

- Raise a delivery request as the store keeper
- Watch it land unassigned on the control tower board
- Offer it to a driver, with each driver's live load shown
- Accept it on the driver's phone, check the parts off, sign at the door
- Close the job, then read the sealed record from either side

State is shared across all five roles, and every action appends an event. The timeline, the
stage durations and the service-level flags are all computed from those events.

A **Show my reasoning** switch pins numbered callouts onto the screens carrying a design
decision, so the argument sits on the thing it is about.

## Anonymity

The client is not named anywhere. Data is illustrative. Nothing here is a live system or a
client record.

## Licence

Written up by Jordan Chang as a record of work delivered at Ninja Van. Not for reuse.
