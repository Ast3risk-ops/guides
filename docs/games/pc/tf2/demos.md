---
icon: material/video-vintage
description: Creating and Exporting TF2 replays.
---

# :material-video-vintage: Replays

!!! warning
    Replays only work on servers that support them. The game will tell you when loading in to a match if this is the case (as well as in the serverlist, look for the movie reel icon). Offline games will always have replay support.

## :material-camera-plus: Creating a replay

Press ++f6++ while alive to record and save a replay after death.

Press ++f6++ after death to save your life as a replay.

Replays can be viewed by pressing the **Replays** button on the main menu (the TV).
<!-- No I haven't played at all on the official servers. -->
![tf2menu](../../../assets/img/tf2menu.jpg)

The **Replay Editor** will show off your replays and saved movies.

![tf2replays](../../../assets/img/tf2replays.jpg)

Hovering over a replay will show more info:

![tf2replays2](../../../assets/img/tf2replays2.jpg)

Clicking on a replay offers a few options:

![tf2replayview](../../../assets/img/tf2replayview.jpg)

<div class="annotate" markdown>
1. **Originals and Takes** (1)
2. **Replay Title** (2)
3. **Watch/Edit** (3)
4. **Save To Movie** (4)
</div>

1. The original replay and any takes you've made.
2. This can be clicked on and edited.
3. View your replay in the **Replay Editor**.
4. **[Export](#exporting-replays)** your take (select a take or the whole movie first).

You can also see stats like who you played as, movie time, map name and kill count.

??? question "How does this replay system work?"
    These replays need to be exported because they are **[not videos](https://developer.valvesoftware.com/wiki/DEM_(file_format))**. They basically load up the map, and have the demo player recreate your (and others') *exact* actions (what it's really recording).

## :material-content-save-all: Exporting Replays

!!! info "Credit for parts of this guide goes to [**boXy**](https://steamcommunity.com/id/secretitem), [**Zoey Fox (ZFox)**](https://steamcommunity.com/id/Zoey_Fox/) and [Goluboch](https://steamcommunity.com/id/goluboch/)."

### :material-cog: Platform-specific steps

=== ":material-microsoft-windows: Windows"

    First, you will need to download [:simple-quicktime: QuickTime](https://secure-appldnld.apple.com/QuickTime/031-43075-20160107-C0844134-B3CD-11E5-B1C0-43CA8D551951/QuickTimeInstaller.exe). Use the typical install.

    ??? question "Why?"
        TF2 uses the **QTFF** (MOV) codec on Windows, and the game will check for QuickTime to be able to get the needed codec to export your movie.


    Reboot your **PC** and launch TF2.


=== ":simple-linux: Linux"

    No platform-specific steps here, just ensure that you have a media player of some kind installed, as by default TF2 uses the WebM codec on native Linux.


*[QTFF]: QuickTime File Fornat

### :material-content-save-cog: Exporting a take

1. Select the take of the replay you want to render.

1. Click **Save to movie...**

1. Enter your preferred settings.

1. Click **Go**.

1. Wait for your replay to finish rendering.

1. Once finished, click on your saved movie (in the **Movies** section) in the replay menu.

1. Click **Export** and choose the name and location to export to.

1. You should find your movie where you exported it to.

??? note "For Linux users"
    You may get a filesystem error when exporting your movie, that's okay.

    You'll find your rendered movies in: 
    
    ```
    <Steam Library Folder>/steamapps/common/Team Fortress 2/tf/replay/client/rendered
    ```

    They will be in **MOV format** (Windows) or **WebM format** (Linux).