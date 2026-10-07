# My Personal Valorant Soundtrack - Dear Data 100

## Project
This repository was made for my IN1007 Creative Coding project **Dear Data 100**.

**The Research Question**
> This is what I ended up asking myself. How do music, performance, and my social interactions shape my overall experience playing Valorant as a woman?

The project will depict a dataset that I collect over time from my own Valorant games. **One Valorant round is ONE observation.** The final Processing sketch will show those 100 data observations.

## What am I really collecting in these observations?
For each round, I plan to record a small set of variables covering:
- Valorant performance / info (map, agent, result, kills, deaths)
- Music (whether music is playing, the genre, energy)
- Mood before and after the round
- Social experience
- Whether gender was relevant during the game/interactions

No usernames, Riot IDs, names, recordings, or other identifying information about myself or players will be stored.

## Processing concept
Each observation becomes part of the 'GameRound' class and will be displayed as its own visual object. Visual language is a work in progress so it can be evolved throughout the experiment and SCAMPER instead of being fixed before the data is collected.

Current prototype encodings include:
- kills -> object size
- mood change -> visual intensity
- music energy -> rhythm marks
- social experience -> outline weight
- gender visibility -> additional outer layer on the object

## Assessment development
### Part 1
I will develop:
- A working Processing sketch
- A genuinely collected set of observations
- A working code/method that returns a proper/accurate value
- This dedicated GiHub repository updating it over the few weeks

### Part 2
The final result I wish to create is:
- At least 100 displaying data sets
- SCAMPER worthy creative decisions I will explain on the page
- 'GameRound' class creation
- Coding objects and outputting the observations

## Repository contents
- 'MyValorantSoundtrack/' - Processing sketch
- 'MyValorantSoundtrack/data/valorant_data.csv' - All collected data
- 'resources/' - The projects design resources/notes




