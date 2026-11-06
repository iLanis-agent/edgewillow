# Edgewillow 1.0 TEST
Native Java/Canvas Android 8+ Mejilink room-border loop puzzle.

Draw one closed non-crossing loop on the bright room borders of the 3x3-cell board. Every used dot has two lines; dots may be skipped. Faint dividers inside a room are unavailable. Each room must leave exactly as many unused perimeter segments as its area in cells. A shared border counts for both rooms, and an outer border for its one room. Printed numbers show room area, not used-edge counts. Tap between neighboring dots on a bright border to toggle a line. Twelve unique 3x3-cell room maps have twelve distinct loops.

Saved border palette and room labels, GG007 icon/menu/site/privacy, unlimited undo/reset. Offline, no ads, analytics, account or requested permissions. Settings and completed-puzzle marks stay on device. External studio link opens the browser.

Independent Python DFS enumerates all 213 simple loops on the 4x4-dot grid. Java independently builds each room perimeter by toggling coordinate-edge sets, checking all 213 loops plus 40000 random 24-edge masks per board against production degree, connectivity and unused-perimeter bit counts. Exactly one solution per board; bounds, solve, undo and replay pass. Adapter navigation, settings, privacy, border taps, next, levels and persistence pass. Actual drawing pixels inspected, not phone screenshots. Phone runtime, performance and browser handoff QA incomplete. Signed TEST only; not final or Play published.

Current 803-entry registry, 119 recovered README/source records and exact Triowillow cumulative stage found no Mejilink or Mejirinku match. Shares Cloverroad loop input and room map presentation, but the loop follows room borders and counts unused perimeter segments, rather than visited cell centers and continuous room visits. Shares Loopglade Slitherlink border-loop input, but variable whole-room unused-edge quotas and unavailable internal dividers replace per-cell used-edge clues. Known Mejilink genre, not a global invention. Partial recovered corpus, not ALL-local. Rules https://www.janko.at/Raetsel/Mejirinku/index.htm .

Download signed test APK on MEGA: https://mega.co.nz/#!8dsjlYoA!SLVjiMlq82GdQZGpOOqpEGOyPLBmftCRBebZrDJRYIE

APK SHA256: da741b3671dd699cbecd1042a743f654d947197722b3c8184940d9196388ece8
Full Git source upload remains pending; source is preserved in the private archive.
