# UltimateOsuServerSwitcher

The UltimateOsuServerSwitcher is a server switcher for osu, that allows to switch between osu!bancho and various private servers.

# How it works

The Program fetches all its informations from the data/data.json file, which means its fully expandable even without a software update.

Switching to a different server or even bancho itself is fairly simple. You just choose the server you want to connect to from a list and
click the «Connect» button.

# In-deep explination

The current server you are playing on is estimated by the ip that is deposited in the hosts file.
Switching a server includes deinstalling all certificates, modfying the hosts file, followed by installing the corresponding certificate
(if you chose to play on a third-party server).

The certificates will be installed on the local machine, rather than just the local user to avoid a warning prompt the user
has to agree with. This improves the switching agility to garantue the best user experience.

# Current server list

> Currently the following servers are listed:
>
> - osu!bancho
> - Ripple
> - EZPPFarm
> - osu!Ainu
> - The Realm
> - Akatsuki