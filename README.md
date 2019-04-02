# Mattermost for Franz
This is the official Franz recipe for Mattermost, modified to have a static URL so it works with a free account in Franz

## Installation

1. Clone/download the folder `recipe-mattermost` repo.

2. Open the Franz Recipe folder on your machine:
  * Mac: `~/Library/Application Support/Franz/recipes/`
  * Windows: `%appdata%/Franz/recipes/`
  * Linux: `~/.config/Franz/recipes/`

3. Create a `dev` folder if you have not already done so

4. Create a `Mattermost-rh` directory in the dev directory

5. Copy the contents of the `recipe-mattermost` directory into the the Mattermost-rh directory

6. Edit the `package.json` file with the URL of your mattermost instance

7. Restart Franz and add the Mattermost-rh service
