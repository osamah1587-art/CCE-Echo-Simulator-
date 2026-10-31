# Video work status
- DONE (Oct 31 2026): all Practice Exam videos integrated. 196 P* stills now play a real loop (181 unique clips; reused clips share one file). VIDMAP = 202 entries incl. the earlier post-test set. SW at v23.
- Matching method: PDF figures extracted in reading order (Question N / Commentary -> P{N}_q{i}/e{i}, identical to img/ names); a figure counts as a video when a play-overlay image (364x205, 1134x638 or 560x315) sits on it (198 such). Each poster matched to the clip with the highest normalized frame correlation (all >= 0.97).
- Encoding: libx264 crf26 preset medium, max width 800, faststart, no audio, -fps_mode vfr (one source declares 1,000,000 fps and explodes without it).
- No clip exists for P68_q2 (best match 0.69, wrong image) -> stays a still.
- T14_q1 and T20_q1 (post-test) have no match among the Practice videos either; they remain stills.
