# Sunrise on the Reaping Countdown

A live countdown to **10:00 p.m. on Friday, November 20, 2026 in British Columbia**.

Hosted with GitHub Pages.

## The time zone detail

British Columbia adopted permanent daylight time on November 1, 2026, so
Pacific Time (PCT) in B.C. is now fixed at **UTC-7 all year** — there is no
fall-back to UTC-8.

The target in `index.html` is therefore pinned as an explicit UTC instant
(`2026-11-21T05:00:00Z`) rather than a named time zone, so the countdown
lands at exactly 10 p.m. B.C. time even on devices whose time zone data
still follows the old seasonal rules.
