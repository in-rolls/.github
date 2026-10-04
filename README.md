# .github

Org profile for [in-rolls](https://github.com/in-rolls): `profile/README.md` is what the org page shows.

## Repository names

Names are `family_topic[_state][_year]`, lowercase, words joined by underscores, so a sorted repo list groups each project together and the repo name matches its Python module name.

- **Family first.** Current families: `electoral_rolls`, `polling_stations`, `local_elections`, `quota`, `caste`, `ror` (land records), `ration`, `mnrega`. Start a new family only when a second repo joins a project; a one-off repo keeps a plain name.
- **States** are full lowercase names (`bihar`, `rajasthan`, `uttarakhand`), except `up` for Uttar Pradesh.
- **Years** are the year of the data, four digits, last: `electoral_rolls_bihar_2020`.
- **Replications** are named for the topic, not the author: `caste_marriage_matching`, not `caste-marriage-banerjee`. The paper goes in the description.
- **Packages** published under their own name keep it: `indicate`, `savitr`, `upnaam`, `anusuchi`, `jaali`.
- **Never reuse a retired name.** GitHub redirects an old name to the renamed repo only until a new repo takes that name. GitHub Pages sites (`in-rolls.github.io/<name>/`) do not redirect at all.
