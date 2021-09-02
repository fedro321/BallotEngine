# BallotEngine
## To Do
### Create a Ballot
As a match secretary I would like to configure dates & times in the calendar that will be dedicated to the results of a ballot system.
#### Requirements
- The ballot should be allocated to a course<br />
- The ballot should have a tee time start date & time; an end time.<br />
- The ballot should have an entry window start date / time and an end date / time<br />
- The ballot should have a name defaulting to "Ballot for [tee time start date]"<br />
- The ballot should have a draw date defaulting to [system configuration integer] days before the tee start time
- The ballot should have tee slot options i.e hourly, 2 hourly defaulting to [sytem configured integer]
- The ballot should have maximum group sizes set defaulting to [system configured integer]
- The ballot should have a set number of tee times per hour defaulting to [system configured integer]
### Register for the Ballot
As a golfer I would like to register my party for the ballot.
#### Requirements
- I shoud be able to choose the ballot I want to enter with the one starting soonest at the top of the list
  - Only the ballots that are in the future and have an active entry window should be available to me
- I should be able to choose the number of playing partners I wish to play with up to a maximum of players allowed in each group
- I should be able to enter unique identifiers for the golfers
  - I should only be able to enter people into the ballot once
- I should be able to indicate whether my group is open to additional players joining assuming my group is less than [system configuration integer]
- I should be notified that my entry has been successful
### Play the lottery
As a match secretary I would like the ballot to be drawn at the allotted time
### Requirements
- Nomads will not be eligable for tee times
- Pairs should be paired up where they have indicated they are open to being paired up
- Nomads should be added to groups who have indicated they are open to being paired up
- Each player that has entered the draw should be a participant in the lottery
- If a player qualifies for a time that time is removed from the pool and his group will fill that time
  - A tee time is the floor of (60 minutes / tee times per hour ) * tee slot number
- The lottery should be fair
- The results should be published




