# ideas

- intercept route to videos / analytics most watched videos / no watched videos

# MVP

Upload videos, upload to panda and R2, embed om player

- [ ] Sync subtitles with Panda
- [ ] Play route (edge redirect)

# Thoughts

- Datadog / Sentry
- DeadLetter queue (manual retry)
  - store number of retries and if its the last maybe notice somewhere and display a button for manual retry
- Find possibly typos in transcription based on commit diff
- Tests please?!
- refactor upload table (selectors - too many renders)
- remove some preload links from listings

- ci