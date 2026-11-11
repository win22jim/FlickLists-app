# Privacy Policy

**FlickLists**
Effective date: November 10, 2026

## Overview

The developer of FlickLists does not collect, receive, or store any of your data. There is no FlickLists server, no account or sign-up, and no analytics, advertising, or tracking of any kind.

To do its job, the app connects directly from your device to The Movie Database for movie and TV information, and to Trakt for its public TV schedule and lists, which need no account. Signing in to Trakt is optional. Like any internet request, these connections share your device's IP address with that service so it can send a response. Exactly what is involved is described below.

## Data Storage

All of your data — your watchlists, the people and groups you watch with, your ratings, and your watch history — is stored locally on your device and in your private iCloud account. Only you can access it.

## Movie & Show Data

To show movie and TV information, FlickLists looks up public content directly from your device:

- **The Movie Database (TMDB)** provides details, artwork, ratings, trailers, and search. FlickLists uses the TMDB API but is not endorsed or certified by TMDB.
- **JustWatch (via TMDB)** provides "where to watch" availability.

These are content lookups. The app sends only what is needed to fulfil the request — your search text, the title you are viewing, and your chosen region — so TMDB can return the matching results. It does not send your identity, your watchlist, or any account information, and your use of TMDB is governed by the [TMDB Privacy Policy](https://www.themoviedb.org/privacy-policy).

## Trakt

**For everyone, with no sign-in,** FlickLists reads two kinds of public information from Trakt:

- **TV air times.** So that a new episode counts as out when it actually airs, the app downloads Trakt's public TV schedule: every episode Trakt lists from two days ago to about a month ahead. Apart from what any internet request carries, such as your device's IP address, the request holds only FlickLists' own app identifier and the dates, so every device sends the same request that day. Nothing about you, your library or your shows is sent: the app matches the schedule to your shows on your device and keeps it only there, never in iCloud or device backups. It asks only while you're using the app and once your device has a TV show's episodes to match, and asks again only when its copy is over 12 hours old or from an earlier day.
- **Most Anticipated lists.** Discover's Most Anticipated shelves come from Trakt's public lists, requested the same way: with the app's identifier and which list.

**Signing in is optional.** If you choose to connect Trakt, you sign in with your own Trakt account, and FlickLists then syncs your personal ("Me") watchlist, watch history, ratings and the shows you stop watching (Trakt's "dropped" list) with that Trakt account so they stay up to date in both places. It also reads the air times of the shows on your Trakt account, and Discover adds Trakt's recommendations for you and its trending lists. Your Trakt sign-in token is stored securely in the device Keychain and used only to talk to Trakt on your behalf. You can disconnect at any time in Settings > Trakt, which revokes FlickLists' access to your Trakt account and deletes the air times kept from it. Settings > Trakt also links directly to Trakt's account-deletion page if you want to delete your Trakt account itself (only Trakt can do that). What Trakt does with your data is governed by the [Trakt Privacy Policy](https://trakt.tv/privacy).

## Trailers (YouTube)

Trailers and extras play inside the app using an embedded YouTube player. When you press play, the video streams from YouTube — exactly like an embedded YouTube video on a web page — so YouTube (Google) receives the standard request needed to deliver the video. FlickLists configures the player to use a non-persistent (private) browsing session, so no YouTube cookies or tracking data are kept on your device between trailers. FlickLists itself receives none of this; it only hosts the player. Your use of the YouTube player is governed by Google's [Privacy Policy](https://policies.google.com/privacy) and the [YouTube Terms of Service](https://www.youtube.com/t/terms).

## Third Parties

FlickLists includes no analytics, advertising, tracking, or attribution SDKs. The only third-party code that runs is the embedded YouTube player used to play trailers (see "Trailers" above), and it runs only when you choose to play a trailer, in a private session. Your data is never sold, and it is never shared for advertising or tracking. The data that leaves your device is: content requests to TMDB; requests to Trakt for its public TV schedule and lists, which carry nothing about you; if you sign in to Trakt, the sync with your own Trakt account; and, when you play a trailer, the video request to YouTube — all described above.

## iCloud Sync

If iCloud is enabled on your device, your app data syncs across your devices through your private iCloud account using Apple's CloudKit. This data is governed by Apple's privacy policy and is not accessible to the developer.

## Contact

If you have questions about this privacy policy, contact: [swishes_heels7s@icloud.com](mailto:swishes_heels7s@icloud.com)
