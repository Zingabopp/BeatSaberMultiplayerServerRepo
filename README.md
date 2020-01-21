# BeatSaberMultiplayerServerRepo
This repository provides BeatSaberMultiplayer/Lite mod with a list of ServerHubs. It was created as an easy way to make ServerHubs available to players without having to manually add the server to the mod's config file or packaging the server as a default in a new version of the mod. Players that have a repository included in their config file will see the ServerHubs in the repo (almost) immediately after they are added. The CompatibleServers repository is include in Beat Saber Multiplayer Lite by default.

# Getting Your ServerHub Added
You can request your server to be added by creating a GitHub Issue (an issue template is provided you can fill out) with your server information, or by creating a Pull Request on **CompatibleServers.json**. If you create a Pull Request, please make sure your addition is correctly formatted json.

# Creating Your Own Server Repository
You can create your own Server Repository by making a json using the **ServerRepositorySchema.json** available through HTTP. This can be in a GitHub repository or through your own web server as long as the URL in the mod's config file returns the repository json.
