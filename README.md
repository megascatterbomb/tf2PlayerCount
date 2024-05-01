# tf2PlayerCount
This repo contains the data used for Zesty Jesus' video ["TF2: Nobody's Home"](https://www.youtube.com/watch?v=2stmQfv93oQ)

Contents:
- `steam_api_data.csv`
  - Contains TF2's player count as reported by Steam, collected every 5 minutes.
  - Data collected by megascatterbomb.
  - The data contains many instances of successive queries that are identical to each other.
    - These duplicates are caused by Steam caching the result and is not reflective of actual player counts at that time.
    - These duplicates were filtered out in Zesty's analysis.
  - Data contains some gaps due to outages in the bot.
- `teamwork_tf_data.xlsx`
  - Contains the number of players in TF2 gameservers as reported by [teamwork.tf](https://teamwork.tf/community/statistics)
  - Historical data accessed via the Wayback Machine.
  - Data manually scraped and compiled by Zesty Jesus.
  - Data contains gaps due to Steam API outages, teamwork.tf outages, or gaps in the Wayback Machine's archives.

License: Do whatever you want with this info, Zesty and I don't care.