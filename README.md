# 废片焕新 / Photo Revival

把普通照片、生活随手拍、废片和日常物件，重新画成一页白纸上的诗性手绘插画。

This Codex skill turns everyday photos into poetic hand-drawn illustration pages: tiny subject, huge white paper field, vivid local color, subtle print texture, and small handwritten notes.

![License](https://img.shields.io/badge/license-MIT-111111)
![Skill](https://img.shields.io/badge/Codex%20Skill-photo--revival-4f46e5)
![Format](https://img.shields.io/badge/default-3%3A4%20vertical-f97316)

## What It Does

`photo-revival` is not a photo filter. It treats the source photo as memory and evidence, then redraws it as a delicate illustration page.

It is especially useful for:

- daily snapshots that feel emotionally good but visually ordinary
- objects, rooms, streets, buildings, cats, food, travel fragments
- photos that should keep their subject and mood but become more poetic
- visual tests that need a consistent white-paper, small-illustration style

## Style DNA

- 3:4 vertical page
- white or near-white paper texture
- 80-88% blank negative space
- tiny illustrated subject, usually 10-16% of the page
- absolute maximum subject area: 18%
- vivid color only inside the small illustrated area
- hand-drawn pencil, watercolor, dry brush, wax pastel, risograph grain
- tiny Chinese or English handwritten notes

## Quick Use

```text
Use $photo-revival to turn this photo into a 3:4 poetic hand-drawn illustration with a white paper field, 80-88% blank negative space, a tiny 10-16% subject area, vivid localized color, subtle collage accents, and tiny handwritten captions.
```

## Prompt Pattern

```text
Transform the reference photo into a 3:4 vertical poetic hand-drawn illustration page on clean white textured paper.
Preserve: <main subject, pose, object, place, mood>.
Redraw it as a tiny illustration occupying only 10-16% of the full page, absolute maximum 18%.
Keep 80-88% of the page as untouched blank white paper.
Use pencil line, watercolor wash, dry brush, wax pastel edges, and light print grain only around the subject.
Use vivid color only in the small illustrated area.
Add tiny handwritten caption: "<short poetic line>" and tiny English note: "<FIELD NOTE / DATE>".
Avoid full-bleed photo, photo-filter look, large typography, dense collage, old yellow paper, and duplicated text.
```

## Sample Gallery

| | | |
|---|---|---|
| ![](examples/01_car_page.png)<br/>Car page | ![](examples/01_flower_tree_paper.png)<br/>Flower tree | ![](examples/01_moon_gate.png)<br/>Moon gate |
| ![](examples/02_camera_page.png)<br/>Camera note | ![](examples/03_bubbles_page.png)<br/>Bubbles | ![](examples/03_pagoda.png)<br/>Pagoda |
| ![](examples/03_red_bike_dot.png)<br/>Red bike | ![](examples/03_runner_paper.png)<br/>Runner | ![](examples/04_skyline_page.png)<br/>Skyline |
| ![](examples/05_dumpling_paper.png)<br/>Dumplings | ![](examples/05_japan_road_page.png)<br/>Road memory | ![](examples/05_old_shop_torn_label.png)<br/>Old shop |
| ![](examples/06_cat_bed_paper.png)<br/>Cat bed | ![](examples/06_mask_dance.png)<br/>Mask dance | ![](examples/06_train_window_page.png)<br/>Train window |
| ![](examples/07_mountain_yaks.png)<br/>Mountain yaks | ![](examples/10_turkeys.png)<br/>Field note | |

## Good Subjects

- a cat sleeping on a blanket
- a stairwell, hallway, window, or doorway
- a bowl of food, cup, chair, umbrella, bicycle, or small tool
- old shops, street corners, stations, parks, bridges, courtyards
- traditional craft, folk performance, handwritten notes, travel fragments

## Do Not Use For

- realistic portrait retouching
- full-page posters with big titles
- commercial product hero ads
- dense infographics
- photo restoration where exact pixels matter

## Files

- `SKILL.md` contains the skill instructions.
- `agents/openai.yaml` contains display metadata for Codex.
- `examples/` contains public sample images.

## License

MIT
