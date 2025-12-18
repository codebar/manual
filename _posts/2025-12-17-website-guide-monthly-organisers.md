---
layout: post
title:  "Website Guide"
---

### How to use the admin area of the codebar website (for monthly organisers)

## Intro

Now that you’ve been given admin access on the codebar website you’ll be able to see some extra options on the left side menu — mainly the ability to create new monthly events.

> _Note:_ The original document included screenshots. Add them back later if you want, using normal image files in the repo (recommended), rather than base64 blobs.

## Creating a monthly event

_If it’s a new sponsor, make sure that a sponsor has been created first. If you need to change the student/coach number for the workshop, visit https://codebar.io/admin/sponsors, find your sponsor and edit it._

1. Go to the **Admin** tab in the top menu.
2. Select **New Monthly**.
3. Fill out the form:
   - **Name:** e.g. _February Monthly_
   - **Slug:** a unique slug, e.g. `monthly-feb-2020`
   - **Date:** select the event date
   - **Time:** normally **6:30PM** start
   - **Description:** this is **Markdown**. It’s easiest to copy an older monthly description and update the details/speakers.
   - **Space:** the number of people the host can accommodate
   - **Venue:** select the host from the dropdown
   - **Organisers:** add organisers for the event
   - **Chapter:** select the chapter this monthly is for
   - **Inviteable:** check/uncheck depending on whether the event is open for RSVP yet  
     (You may want to list the event but not open RSVP right away.)

## Monthly admin area

_Once your monthly event has been created you can edit it at any point._

Each monthly event you create has its own admin page. It’s where you manage the event and attendees.

### Top buttons

- **Invite** — invite members of your chapter to the workshop. You can choose **Students**, **Coaches** or **Everybody** (usually **Everybody**).
- **Edit** — edit event details.
- **Emails** — view attendee emails. If you mass email, **make sure you BCC** everyone.
- **Labels** — download a CSV of attendees (useful if a host asks for a list beforehand).

You’ll also see key event info (venue, date, address, organisers, number of spaces), and the event description (often speaker info).

### Attendee list

- **a)** At the top you can see how many people have RSVP’d.
- **b)** You may see a dropdown to manually add someone (who has been email-invited) from your chapter.
- **c)** You’ll see the attendee list:
  - The **minus** symbol next to someone’s name removes them from the event (commonly used when someone emails to cancel).
  - At the start time of your workshop the minus symbol changes to a **checkbox** so you can check people in.
  - Each attendee is a **link** to their member admin area.

#### Waitlist

Once spaces are filled up, a waitlist link appears. The waitlist is kept in Airtable. As people drop out, email someone from the waitlist to offer them a spot.

## Member admin area

Every member of the codebar community has an admin area. You can view personal info, remove chapter subscriptions, see attendance history, send attendance/eligibility emails, leave notes, and ban members.

### Actions

- **Ban** — ban someone (e.g. bad attendance or code of conduct issues). You can choose the ban duration.
- **Note** — add a note to someone’s profile (eligibility, behaviour, etc.).
- **Eligibility** — send an eligibility email if you’re unsure whether a student is eligible.  
  _Note: a member who is only subscribed as a coach won’t have this button._
- **Attendance** — send an attendance email if someone repeatedly RSVPs and doesn’t show up.

### What you’ll see on the page

1. Action buttons (Ban / Note / Eligibility / Attendance)
2. Personal information
3. Chapters the member subscribes to (remove a subscription using the **X** next to the chapter)
4. RSVP vs attended counts (useful when deciding whether to send an attendance email)
5. List of workshops/events they RSVP’d to:
   - A **tick** indicates they attended
   - A **!** indicates they RSVP’d but didn’t show up
   - Monthlies attended may be listed underneath too

## Updating sponsor information

If a sponsor moves, changes URL, changes logo, etc:

1. Go to https://codebar.io/admin/sponsors
2. Find your sponsor and click **Edit**
3. Make changes and click **Save**

## FAQ

### I want to update some information about the host/sponsor?

Edit it via https://codebar.io/admin/sponsors → **Edit**.  
You can change student/coach number, address, contact details, etc., then click **Save**.

### What does it mean when a workshop is “invitable”?

It means members of your chapter can RSVP to the event.

### If I send out email invites again what will happen?

Only people who subscribed since the last invite will receive it. It can be worth sending again if you know a bunch of people subscribed recently.
