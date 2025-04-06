# ASA-Server-Manager: Simplify Your Ark Server Administration
ASA-Server-Manager is designed to streamline the management of your Ark: Survival Ascended servers. Easily adjust server configurations, tweak settings, and fine-tune your gameplay experience to create the perfect environment for you and your friends.

# Getting Started:
Run as Administrator: Ensure the application is running with administrator privileges (it should already be configured to do so).
Create a Server Profile: Create a new server profile and give it a descriptive name (optional).

Initial Launch & Configuration: Launch the server once to download all necessary game files. Then, terminate the server. The newly populated settings tabs will now be available for customization.
Networking (For Public Servers): If you plan to run a public server, ensure all required ports are properly forwarded on your router/firewall and that the server IP address is correctly configured.
Adding Mods: Add mods one at a time using the input box that appears when you click the "Add Mod" button. The application will automatically download each mod when the server is started.
Start Your Server! After configuring settings and adding mods, you should be good to go!

![Alt text](URL "/Screenshot 2025-04-06 170709.png")

# Important Considerations:
Server Relocation: Moving your server after creating a profile currently requires manually updating the server path within the server_profiles.json file. We plan to automate this process in a future update.

BattleEye Status: The application currently defaults to disabling BattleEye. Control over BattleEye will be implemented in a future release.

Custom INI Settings: Currently, adding custom settings/values to the Game.ini or GameUserSettings.ini files requires manual editing of those files. We plan to implement a more integrated solution in a future release.

Cluster Support: ASA-Server-Manager is primarily designed for managing single-map servers. While cluster support isn't currently a priority, we will consider adding it based on user demand. Please let us know if this feature is important to you!

