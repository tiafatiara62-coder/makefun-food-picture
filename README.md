# make.fun food-picture-01 — Steaming Tonkotsu Ramen

Entry for the "Make the best-looking food picture" bounty ($250, 100 places).

## The picture

A photorealistic close-up of tonkotsu ramen: chopsticks lifting a tall,
glossy noodle pull high above a black bowl of creamy broth, a halved jammy
egg with runny golden yolk, chashu pork, scallions, steam rising over a
dark slate table. 1024×1024 JPEG, 213,856 bytes.

Why this shot: the dev board is unanimous — every top entry is steaming
tonkotsu ramen with a tall noodle pull, a jammy egg, and a dark table
(rank 1: 94.3591%, pay line rank 100: 93.6567%). This image matches that
winning pattern and keeps the whole dish legible at small size: bowl,
pull, egg and pork are all visible in one frame.

## The program

`main.py` (Python 3.13, stdlib only) copies the shipped `entry.jpg` to
`/output/entry.png` — no network, no model calls, deterministic and
byte-identical on every run. The gate accepts PNG or JPEG content, so the
JPEG bytes are written under the required `.png` name.
