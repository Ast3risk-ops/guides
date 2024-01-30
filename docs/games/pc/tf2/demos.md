---
icon: material/video-vintage
description: Creating and Exporting TF2 replays.
---

# :material-video-vintage: Replays

## Creating a replay

WIP

## Exporting Replays

!!! info "Credit for this guide goes to [**boXy**](https://steamcommunity.com/id/secretitem), [**Zoey Fox (ZFox)**](https://steamcommunity.com/id/Zoey_Fox/) and [Goluboch](https://steamcommunity.com/id/goluboch/)."

Turning your replay into a movie.

### Platform-specific steps

=== ":material-microsoft-windows: Windows"

    First, you will need to download [:simple-quicktime: QuickTime](https://secure-appldnld.apple.com/QuickTime/031-43075-20160107-C0844134-B3CD-11E5-B1C0-43CA8D551951/QuickTimeInstaller.exe). Use the typical install.

    ??? question "Why?"
        TF2 uses the **QTFF** (MOV) codec on Windows, and the game will check for QuickTime to be able to get the needed codec to export your movie.


    Reboot your **PC** and launch TF2.


=== ":simple-linux: Linux"

    No platform-specific steps here, just ensure that you have a media player of some kind installed, as by default TF2 uses the WebM codec on native Linux.


*[QTFF]: QuickTime File Fornat

## Exporting a take

1. Select the take of the replay you want to render.

1. Click **Save to movie...**

1. Enter your preferred settings.

1. Click **Go**.

1. Wait for your replay to finish rendering.

1. Once finished, click on your saved movie (in the Movies section) in the replay menu.

1. Click **Export** and choose the name and location to export to.

1. You should find your movie where you exported it to.

??? note "For Linux users"
    You may get a filesystem error when exporting your movie, that's okay.

    You'll find your rendered movies in: 
    
    ```
    <Steam Library Folder>/steamapps/common/Team Fortress 2/tf/replay/client/rendered
    ```

    They will be in **MOV format** (Windows) or **WebM format** (Linux).