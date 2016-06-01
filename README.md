# Galvanize Q3 Group Project Proposal

1. Fork/clone this repo
2. Update this readme with proposal
3. Pull request

## Group Members
  Jenni Bradstreet
  Dustin Wurtz
  Sean Stokke
  Mike Duin
  Morgen Fett

## Project Description
  Scavenger Hunt App that utilizes geofencing to create organized and customizable experiences for friends and family.

## Who uses it?
  Target Demographic  - (initial) 21+ crowd that wants to organize bar crawl with friends.
                      - (initial) The family that wants to create a fun outing exploring landmarks, parks, and places of interest within a city.
                      - (future)  Organized groups like the AlleyCats that hold competitive events around the city.
## What outputs do they need?
  OAuth - IF user (validate on backend), send to 'make a Scavenger Hunt' screen,
          ELSE make user resubmit or sign up.

  When 'check in' button clicked  - IF at right location, turn clue a different color and send to bottom of que,
                                    ELSE generate a 'not quite' message and return to the scavenger hunt page.
  Once Scavenger Hun-





## What inputs are needed to generate those outputs?
  OAuth

  'Check in' button

  Form  - Name your Scavenger Hunt
        - Date | Time | Location that Scavenger Hunt commences
        - Addresses of locations for Scavenger Hunt (tied to geofencing)
        - Clues/riddles to locations
        - Invite friends
        - Specify Team Captains









## What technologies will you use that weren't covered in class?
  Geofencing (w/ geolocation radius)
  React (2nd)
  React Native (1st)
  Mapbox

## What technologies do you plan to use?
  Node.js
  Express
  Several APIs
  FB OAuth

## Feature list
  Instagram tagging (API, geolocation)
  Partnering with businesses and retailers for cross promotion (possibly Groupon API)(potentially a great way to partner with locally owned businesses)
  Splitwise
  Venmo
  'Progress Board' to compare your progress to other teams
  Geolocation toggling- option for user to set up visible geolocation radius, or keep it behind the scenes (ie competition vs general outing)
  On successful OAuth login, option to access past scavenger hunt, but main focus goes to creating a new one.
  Display page generated upon completion of scavenger hunt
  Auth for initial user VS team captain VS teammate
  Upon submission addresses of locations, auto-generate dropped pins via Mapbox on 'create a SH' page to help organizing user visualize scope of hunt
  Organizer has option to 'Start' Scavenger Hunt at will OR SH becomes accessible on Team Captain's Phone at pre disclosed Date and Time
