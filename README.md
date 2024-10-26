This is a collection of logs and autosaves collected to debug multiplayer desyncs with The Old World in Total War: Warhammer III

"Player 1" was playing on Linux using Proton. Apart from issues with the Nvidia display driver, this has not caused any other issues, and is unlikely to be the cause here.

"Player 2" was playing on Windows.

We switched who hosted a few times without that changing anything.

Campaign 1 desynced consistently during the first end-of-turn. That one was with MCT, so I assume the real problem there is MCT being broken in MP, but I figure might as well include it.

Campaign 2 also desyncs consistently at end of turn. We started this one with one other mod (https://steamcommunity.com/sharedfiles/filedetails/?id=3311338953&searchtext=campaign+buff) which has no scripts. After the first desyncs we disabled it, but we kept desyncing. Save is attached.

Campaign 3 was started with only this mod and MIXER (as well as the script debug mod). We also autoresolved all turn 1 battles (from old-time MP desync instincts). This one does not desync at the same place every time, and is able to progress, but still desyncs about once per turn on average.

The logs labelled "end_turn_desync" occurred during the end-of-turn. One of them, "end_turn_desync_2", did not provoke the desync dialog but instead just left both players alone in their own campaign. Not sure what happened there, but I guess that's probably a weird issue with the game and not something provoked by the mod?

The logs labelled "turn_start_desync" are from desyncs at the very start of a turn, before any player took action. These also in most cases contain an actual error output, so are probably more fruitful to dig into?


