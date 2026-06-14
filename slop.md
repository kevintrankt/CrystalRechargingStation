# Discord Chat Transcript

1. **kebin** _05/26/2026 2:18 PM_
   - usb hub
   - auto import into library

2.
   - share on cloud after festival or event

3. **kebin** _05/27/2026 11:58 AM_
   we could have a big ssd that is partitioned every time a new usb is put in

4. idk if that's efficient

5. **peter** _05/27/2026 12:30 PM_
   Why repartition? If we have a big enough SSD we could just incrementally grow the shared library on disk whenever a new source is added (small db can track known/imported USBs...maybe an edge case if two ppl have an identically named USB)

6. **kebin** _05/27/2026 12:32 PM_
   i was thinking of partitioning to be the easiest to just have a copy of each usb in the drive so there's no need to deal with hacking a rekordbox library file

7. but ideally we just have one library that keeps expanding

8. with notion external agents feature, we can create a notion project board that all connects to a single github repo + claude code agent so we can all interact with the same code base and agent all at once hahah

9. **peter** _05/27/2026 1:05 PM_
   Yeah dealing with rekordbox vs engine formats would be a huge pain probably. Wouldn't repartitioning put us back to square 1 though in that the controller would just see a bunch of different sources that we'd have to swap between? I thought we wanted to avoid having to go and do the extra button pushing to bounce between sources

10. **kebin** _05/27/2026 1:08 PM_
    yeah true it'd be nice to not have to deal with changing sources.

    if we can find a way to have an empty RB playlist and as we put more usbs in, everything appends to that library - would need some sort of diffing logic if the same usb is inserted and there's new music/cues

11. **kebin** _05/27/2026 3:13 PM_
    @Sam

12. **kebin** _05/27/2026 4:28 PM_
    https://www.notion.so/kebt/Crystal-Recharge-USB-Hub-36d6e036c005801383d0d4e671b113ef

13. i'll plug in some agents to handle some coding tasks for us

14. **Sam** _05/27/2026 7:09 PM_
    Hmm

15. Is this for music sharing?

16. Swapping usbs isn't that much of a chore

17. **kebin** _05/27/2026 7:11 PM_
    music sharing

18. swapping usbs is whatever - denon supports a usb hub

19. it's building a shared library

20. **kebin** _06/02/2026 8:33 PM_
    https://nicotine-plus.org/ @John
    Nicotine+
    [Nicotine+](https://nicotine-plus.org/)
    Graphical client for the Soulseek peer-to-peer network

21. modern day limewire

22. **John** _06/02/2026 8:34 PM_
    Oh yah

23. When I get moved up to michigan circa early July I can start taking a look at how annoying the Rekordbox DB format is

24. Claude says not too hard
