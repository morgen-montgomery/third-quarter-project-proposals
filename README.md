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
  (a) OAuth - IF user (validate on backend), send to 'make a Scavenger Hunt' screen,
              ELSE make user resubmit or sign up.

  (b) Invite generated via email / text

  (c) Upon receiving SH invitation  - IF accept, send to OAuth?
                                      ELSE, generate 'maybe next time' message

  Once Scavenger Hunt becomes accessible:
      - Interactive drop-down menu for each clue/riddle generates, utilizing inputs from (b)
          - (d) onClick 'I think I'm here' button  -  IF at right location  - turn clue a different color,
                                                                        - send clue to bottom of que,
                                                                        - update team score (see scoring section)
                                                  ELSE - generate a 'not quite' message,
                                                       - return to the scavenger hunt page

  Once all clues/riddles solved, final destination unlocked.

## What inputs are needed to generate those outputs?
  (a) OAuth

  (b) Form  - Name your Scavenger Hunt
            - Date | Time | Location that Scavenger Hunt commences
            - Addresses of locations for Scavenger Hunt (tied to geofencing)
            - Clues/riddles to locations
            - Invite friends (via email / text)
            - Specify Team Captains

  (c) Accept or reject invitation

  (d) 'I think I'm here' button

  ** POINT SYSTEM: - max points given for each location (set by organizer)
                   - deduct points for using optional (additional) hints accessible during SH (set by organizer)
                   - when 'I think I'm here' successful, recalibrate score

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

## Feature list (Nice-to-haves)
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
  Organizer has option to 'Start' Scavenger Hunt at will OR SH becomes accessible on Team Captain's phones at pre disclosed Date and Time
  Countdown feature
  See past scavenger hunts
  Points of interest / trivia about a novelty product found at, or history of, location
  Team delegation more customizable
  Toggle between map and clues during SH
