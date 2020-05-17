# BeatSaberMultiplayerServerRepo [![JSON Validation](https://github.com/Zingabopp/BeatSaberMultiplayerServerRepo/workflows/JSON%20Validation/badge.svg?branch=master&event=push)](https://github.com/Zingabopp/BeatSaberMultiplayerServerRepo/actions)
This repository provides BeatSaberMultiplayer/Lite mod with a list of ServerHubs. It was created as an easy way to make ServerHubs available to players without having to manually add the server to the mod's config file or packaging the server as a default in a new version of the mod. Players that have a repository included in their config file will see the ServerHubs in the repo (almost) immediately after they are added.

# Main Server Repository Links
The CompatibleServers repository is included in both Beat Saber Multiplayer and Beat Saber Multiplayer Lite by default. If you want the link to the main server repositor, you can use one of these.
* Through GitHub Pages (Recommended): https://zingabopp.github.io/BeatSaberMultiplayerServerRepo/CompatibleServers.json
* Through raw.githubusercontent: https://raw.githubusercontent.com/Zingabopp/BeatSaberMultiplayerServerRepo/master/ServerRepositorySchema.json

# Getting Your ServerHub Added/Changed/Deleted
You can request your server to be added one of two ways:
* Creating a Pull Request on **CompatibleServers.json**.
  * Please make sure your addition is correctly formatted json compliant with the [schema](https://zingabopp.github.io/BeatSaberMultiplayerServerRepo/ServerRepositorySchema.json).
  * A GitHub Action will run when the Pull Request is created to validate your edits against the schema. Your Pull Request should pass the check.
* Creating a GitHub Issue (an issue template is provided you can fill out) with your server information.
  * This may take longer to approve.

# Creating Your Own Server Repository
You can create your own Server Repository by making a json using the **ServerRepositorySchema.json** available through [HTTP](https://raw.githubusercontent.com/Zingabopp/BeatSaberMultiplayerServerRepo/master/ServerRepositorySchema.json). This can be in a GitHub repository or through your own web server as long as the URL in the mod's config file returns the repository json.
