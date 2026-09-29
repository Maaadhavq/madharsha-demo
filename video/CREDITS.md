# Video sources

Everything in this folder is cleared for commercial use. Recorded here because a
folder of video with no provenance becomes a problem the moment somebody asks
where it came from — and on a product whose whole argument is provenance, that
question will get asked.

All files are transcoded to 960 px wide, H.264 crf 24, no audio, `+faststart`
(playback begins before the file finishes arriving). Same treatment the
dashboard's generated clips get in `pipeline/camera/build_video_clips.py`.

---

## Stock footage — Pexels

**Licence:** [Pexels Licence](https://www.pexels.com/license/) — free for
commercial use, no attribution required, modification permitted. Attribution
given here anyway.

| File | Shows | Source |
|---|---|---|
| `shop-browsing-rack.mp4` | Two shoppers choosing clothes and a bag | [pexels.com/video/8322526](https://www.pexels.com/video/8322526/) |
| `shop-looking-at-rail.mp4` | Shoppers looking along a clothing rail | [pexels.com/video/8387486](https://www.pexels.com/video/8387486/) |
| `shop-staff-assisting.mp4` | Shop assistant showing dresses to a customer | [pexels.com/video/8387356](https://www.pexels.com/video/8387356/) |
| `shop-two-shoppers.mp4` | Two people shopping for clothes | [pexels.com/video/5707909](https://www.pexels.com/video/5707909/) |

Originals were 4K, 29–47 MB each (159 MB total); these are ~1–2 MB each.

### Where these belong, and where they do not

**Use them on a landing or marketing page.** They are clothing-retail footage,
which matches the client, and they look good.

**Do not put them in the camera view.** They are handheld/gimbal b-roll shot at
eye level: the camera moves, and the framing is close. A tracking overlay drawn
on a moving camera reads as broken, because the boxes slide against a background
that is also sliding. The camera view needs a fixed mount and a wide view — that
is what the CARR clips below are for.

---

## CCTV footage — CARR

**CARR — Customer Activity Recognition in Retail Dataset.** Licensed
[CC BY 4.0](https://creativecommons.org/licenses/by/4.0/),
doi:[10.6084/m9.figshare.29470079.v3](https://doi.org/10.6084/m9.figshare.29470079.v3).

**Attribution is required by the licence** wherever these are distributed. It is
already carried in the deploy README written by `deploy.sh`.

Real fixed-camera retail footage from ten stores. This is what the camera view
should use: the mount does not move, the view is wide enough to see a person
walk through it, and tracking overlays sit correctly on it.

Selected clips and their scores are listed in `carr-picks.md` alongside this file.
