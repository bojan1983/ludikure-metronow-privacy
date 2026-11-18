# Privacy Policy

**MetroNow DC** (iPhone and Android) is a free train-times app for Washington, DC. It has no
accounts, no advertising and no analytics or tracking SDKs. This page says what leaves your phone,
why, and how long we keep it.

*Last updated: November 17, 2026.*

## Your location

Location is optional. With it on, your phone uses it to find your nearest station and how long
the walk to the platform takes. On the iPhone, a Nearest Station widget also reads your location
on the phone to pick its station.

Your location leaves your phone only to answer a request you can see on screen:

- **A walk time or walking directions.** On iPhone it is sent to Apple Maps. On Android it is sent
  through our server to Google Maps.
- **A route ("Where to?" on iPhone).** It is sent to our route server to work out the way there,
  and to Apple Maps for the walks at each end.

We don't keep it. Our servers' logs leave out the part of a request that carries your location,
nothing with your location in it is cached, and our route server records only that a route was
asked for, not where from. Apple and Google handle
their part under their own privacy policies.

## What you search for

When you type a place or an address in "Where to?", the text goes to Apple Maps (iPhone) or,
through our server, to Google Places (Android) to find it. We don't keep the search. On Android
the place you pick is remembered on your phone, and its position is refreshed from Google after
30 days.

## Lock Screen tracking, stop alerts and widgets (iPhone)

When you track a train, set a stop alert or add a widget on an iPhone, the app sends our push
server what it needs to send you updates:

- the push token Apple gives the app (it lets us send updates to the app on your phone; it does
  not identify you);
- the station, train and stop you chose;
- a random identifier the app makes for itself, so one phone's registrations can be told apart.

A tracking or stop-alert registration is deleted when the ride ends, and after at most 8 hours. A
widget's registration is kept until Apple reports its token is no longer valid, and is then
deleted. The push server also keeps a daily count of how many phones used tracking that day; it
keeps the random identifiers behind each day's count, only so a phone is counted once, for about
13 months, and no station, train or time with them. The push server's own logs are kept for about 3 days.

On Android, tracking and stop alerts run on your phone and nothing is sent to the push server.

## Server logs

The apps fetch train data through our server. Its logs record each request's time, the network
address it came from and the page asked for (without the query, which is where a location would
be), and are kept for 7 days to keep the service running. We use them to count how many people
use the app. We do not sell, share or combine them with anything else.

## On your phone

Your favorites, settings, the direction you usually ride and the app's diagnostic logs stay on
your phone. The diagnostic logs leave it only if you choose to export and send them.

## Where the train data comes from

Train and bus times come from the public feeds of WMATA, the Maryland Transit Administration
(MARC), Virginia Railway Express (VRE), Fairfax Connector, Arlington Transit (ART) and Loudoun
County Transit. Fetching them sends nothing about you to those agencies.

## Children

The app is not directed at children and collects nothing that identifies anyone.

## Changes

If this policy changes, this page will say so, with a new date at the top.

## Contact

Questions about this policy: [metronow@proton.me](mailto:metronow@proton.me)
