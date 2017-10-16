# @audrey's profile on Rotonde for Beaker Browser

This repo is basically a profile on the Rotonde social network, and this one is mine :) It's built for the Beaker browser which allows p2p networking, no central servers needed! Follow the setup instructions below to start your own!

---
<br>

**`@audrey` on Rontode, find me in the Beaker Browser  at:**
```
dat://49a043352e6bd3d00e8398b56c79b0dc3c3ec92f678259cb505ece6673e486cd/
```
<br>

<div style="clear: both;"/>
If you're on Rotonde, paste a user's address (like mine above) into your `Input` field to 'follow' them.
<br><br>
Since `dat://` is peer-to-peer, in Beaker, you can click the **menu ( ` ▼ ` )** in rightmost side of the URL bar, to get an option to **"Add to Library"**. If you add a site to your library like this, you become a seed! The more seeds, the more likely the site will be available to others.
<br><br>

---

**Instructions from the original repo:**

## Setup

There is a beginner-friendly setup tutorial available at the following URL: [https://louis.center/p2p-social-networking/](https://louis.center/p2p-social-networking/). See this list for rotonde portals to follow: [https://cblgh.org/rotonde.html](https://cblgh.org/rotonde.html)

## Start

- Write a first message maybe.
- Share your `dat:` url with people, and past theirs to follow them.
- Enjoy!

## Commands

- `dat://000` will follow a portal.
- `undat://000` will unfollow a portal.
- `filter @neauoire` will show your mentions.
- `clear_filter` will clear the filtered feed.
- `edit:name Some_name` will change your display name.
- `edit:desc Some_name` will change your display description.
- `edit:site Some_name` will change your display site.
- `edit:0` will edit your first entry.
- `delete:0` will delete your first entry.

## Icon

To change your display icon, update the SVG file located at `media/images/icon.svg`. The icon should be a square file for it to display properly. Keep it small. If you update your svg manually, don't forget to go to Library->(Your Rotonde Site) and press Review Changes -> Publish, otherwise your changes wont be seen by anyone!

## Rich content

- `TEXT >> MEDIA_NAME.jpg`, will connect a media filename from `/media/content/MEDIA_NAME.jpg`.

## Commands

- `dat://`, to subscribe to a portal.
- `undat://`, to unsubscribe to a portal.
- `edit:name TEXT`, to update your portal name.
- `edit:desc TEXT`, to update your portal description.
- `edit:site URL`, to update your portal website.
- `edit:ENTRY_ID TEXT`, to edit an entry.
