# Video work status
- DONE (Oct 31 2026): all Practice Exam videos integrated. 196 P* stills now play a real loop (181 unique clips; reused clips share one file). VIDMAP = 202 entries incl. the earlier post-test set. SW at v23.
- Matching method: PDF figures extracted in reading order (Question N / Commentary -> P{N}_q{i}/e{i}, identical to img/ names); a figure counts as a video when a play-overlay image (364x205, 1134x638 or 560x315) sits on it (198 such). Each poster matched to the clip with the highest normalized frame correlation (all >= 0.97).
- Encoding: libx264 crf26 preset medium, max width 800, faststart, no audio, -fps_mode vfr (one source declares 1,000,000 fps and explodes without it).
- P68_q2: its clip (59d7cbf4, 61 s) had been missed in staging; now added, trimmed to 20 s.
- T14_q1: matched from the Post Test zip (D:\SCC ECHO). T17/T20 clips exist but those questions are not in data.js, so not added.
- DONE: CLIP text added for P14.q P51.q P65.q P70.q P105.q P157.q P52.e (SW v24). P118 is not a question in data.js, so its clip text is not needed.
