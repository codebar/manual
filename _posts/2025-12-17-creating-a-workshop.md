---
layout: post
title: "Creating a workshop"
weight: 60
---

This guide covers how to use the admin area of the codebar website if you are a chapter organiser, with a focus on creating a workshop.

> **Screenshots:** The original doc includes screenshots. Add them as normal image files in the repo (recommended) and link them here, rather than pasting base64 images into the Markdown.

## Intro

Once you’ve been given admin access on the codebar website you’ll see extra options in the left-hand menu, including the ability to create sponsors, create workshops, view feedback, and access your chapter admin area under **My Chapters**.

[comment]: <> (![Screenshot: admin menu](TODO-add-screenshot))

## Chapter admin area

In your chapter admin area you can see upcoming workshops, view students/coaches, and see the latest subscribers.

[comment]: <> (![Screenshot: chapter admin area](TODO-add-screenshot))

1. **Organisers list** for your chapter
2. **Coaches and students** subscribed to your chapter  
   - Clicking **Students** or **Coaches** shows a full list  
   - Clicking **View students emails** / **View coaches emails** shows email addresses
3. **View all workshops** shows every workshop your chapter has run (and lets you open old workshop admin pages)
4. **Workshops list** shows the workshops you’ve created; click one to open its admin page
5. **Latest subscribers** shows recent signups (name, pronouns, whether student/coach, and time). Clicking a person opens their member admin area.

## Adding a sponsor

If the company has **never hosted a codebar workshop before**, you’ll need to add them as a sponsor before creating the workshop. If they’re already in the system, you can skip to creating the workshop.

- Go to the **New sponsor** tab in the left menu
- Fill out the required fields and click **Create sponsor**

Notes:
- **Website:** usually the company website, unless they ask you to link elsewhere
- **Avatar:** ask for a transparent-background PNG logo
- **Address:** you don’t need latitude/longitude unless the map pin is wrong; 
- **Directions** are useful if the location is hard to find
- **Accessibility:** even if optional, do your best to add it (at minimum: step-free access to the workshop and bathrooms)
- **Contact details:** the dropdown is useful if the person already has an account; otherwise add name/email manually

[comment]: <> (![Screenshot: new sponsor form](TODO-add-screenshot))

## Creating a workshop

If it’s a new sponsor, make sure you’ve created the sponsor first.  
If you need to change student/coach numbers for the host, go to https://codebar.io/admin/sponsors, find the sponsor, and edit it.

- Go to the **Admin** tab and select **New Workshop**

There are two parts depending on whether the workshop is **in-person** or **virtual**. For both, these fields are required:

- Select your **chapter**
- Select the **date**
- Select the **start time** (include the 30 minutes of socialising beforehand)

### In person (left side)

- Select the **host**
- Select your **sponsor(s)**  
  (sometimes a different company sponsors food/drink; if it’s the same, select the same company as host)
- Optionally set the date/time the workshop should **auto open RSVP**
- Ensure **Invitable** is **unchecked** if you don’t want RSVPs yet (leave it checked if you do)
- Click **Save**

### Virtual (mostly right side)

- Check **Virtual workshop**
- Create a workshop channel in Slack and enter the **channel name**
- Get the Slack channel URL (in Slack: click the channel name → Copy Link) and paste it in
- Enter **coach** and **student** spaces

> Note: we normally do not have a sponsor for virtual workshops, so don’t add one unless there is an explicit agreement.

If you want people to RSVP right away, check **Invitable**. If you only want to list it for now, leave **Invitable** unchecked.

[comment]: <> (![Screenshot: new workshop form](TODO-add-screenshot))

## Workshop admin area

Once your workshop is created you can edit it any time. Each workshop has its own admin page where you manage the workshop and attendees.

[comment]: <> (![Screenshot: workshop admin page](TODO-add-screenshot))

### Buttons at the top

- **Edit** — edit workshop details
- **Invite** — invite chapter members (usually choose **Everybody**)
- **Labels** — download a CSV of attendees (useful if the host asks for a list)
- **Attendees** — see attendees and what students are working on
- **Emails** — view attendee emails (if you mass email, **BCC everyone**)
- **Destroy** — you can destroy a workshop up to 3 hours after creating it

Below the buttons you’ll see the venue, date, address, organisers, and student/coach spots.

## Attendee list

[comment]: <> (![Screenshot: attendee list](TODO-add-screenshot))

1. Shows how many invitations were sent, RSVP counts, and waitlist counts (students/coaches).
