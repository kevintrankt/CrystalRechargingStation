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

1
