# LAURA_RECS-Project

A short description of your project.
A website for the record label/party series I run called L.A.U.R.A. Recs

Link to the API you plan to use
https://soundcloud.com/oembed?format=json&url=https://m.soundcloud.com/laurarecs/autumns-my-bodys-overwhelming-sound-of-decay-ft-lower-tar

http://ws.audioscrobbler.com/2.0/?method=album.search&album=believe&api_key=YOUR_API_KEY&format=json

http://ws.audioscrobbler.com/2.0/?method=artist.getinfo&artist=Cher&api_key=YOUR_API_KEY&format=json

```
Example data response you plan to use
{
version: 1,
type: "rich",
provider_name: "SoundCloud",
provider_url: "https://soundcloud.com",
height: 400,
width: "100%",
title: "Autumns - My Body's Overwhelming Sound Of Decay Ft Lower Tar by L.A.U.R.A. RECS",
description: "L.A.U.R.A. Recs 006 : Autumns / Smog Index - Tasteless EP",
thumbnail_url: "https://i1.sndcdn.com/artworks-E6cTuMBcBTbnlpCX-iPySHQ-t500x500.jpg",
html: "<iframe width="100%" height="400" scrolling="no" frameborder="no" src="https://w.soundcloud.com/player/?visual=true&url=https%3A%2F%2Fapi.soundcloud.com%2Ftracks%2F1207900078&show_artwork=true"></iframe>",
author_name: "L.A.U.R.A. RECS",
author_url: "https://soundcloud.com/laurarecs"
}


artist:
bio: {links: {…}, published: '01 Jan 1970, 00:00', summary: ' <a href="https://www.last.fm/music/Strait+Jacket">Read more on Last.fm</a>', content: ''}
image: (6) [{…}, {…}, {…}, {…}, {…}, {…}]
name: "Strait Jacket"
ontour: "0"
similar: {artist: Array(5)}
stats: {listeners: '281', playcount: '1577'}
streamable: "0"
tags: {tag: Array(5)}
url: "https://www.last.fm/music/Strait+Jacket"

```

Visual of your component hierarchy
Project 1 Component Hierarchy
https://media.git.generalassemb.ly/user/41584/files/c5540b00-99c1-11ec-9190-4ef27b091e99

Wire Frames
Copy and paste or drag and drop your images here.
Project 1 Wire Frame
https://media.git.generalassemb.ly/user/41584/files/c84efb80-99c1-11ec-9221-d13f66ea38c2

User Stories
Add user stories following the As a [type of user], I want [what the user wants], so that [what it helps accomplish] format.

- As a user, I want to click through the home page so that I can view different parts of the site
- As a user, I want to be able to click through the carousel, so that I can see the different album art work
- As a user, I want to be able to click on the image in the carousel, so that I can get more information about the album release
- As a user, I want to click the play button, so that I can listen to the music associated with each release

- As a user, I want to be able to click into the navigation bar so that I can view different aspects of the site
- As a user, I want to be able to click into the shows tab so that I can see upcoming shows
- As a user, I want to be able click into the releases tab, so that I can see a comprehensive view of all upcoming shows
- As a user, I want to click into the merchandise tab, so that I can view what label merchandise is for sale
- As a user, I want to click into the about tab, so that I can see a bio about the record label

MVP Goals

- Flip through the homepage carousel with different release album cover art
- linking API data for the album art work and song associated with it
- clicking a play button thats on each slide and have it link to a song associated
- clicking into the carousel and having it route to the release
- click similar artists button and have it display similar artist cards
- Link releases component in the nav bar with a routed link that opens a page
- clicking into the About button and routing to a bio section in the nav bar with a routed link that opens a page

Stretch Goals

- Link shows component in the nav bar with a routed link that opens a page
- Link shows releases component
- having a navigation bar with clickable links to shows, releases, and merchandise
- stylizing the homepage to match the label's aesthetic
