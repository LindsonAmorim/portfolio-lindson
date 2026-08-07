# Design: Mobile responsive polish (custom.scss)

**Date:** 2026-08-07  
**Status:** Approved for implementation  
**Approach:** Overrides only in `quartz/styles/custom.scss` at `max-width: 800px`

## Goal

Full mobile polish: compact header/sidebar, readable type, no horizontal overflow, better home/post spacing — without editing Quartz core `base.scss`.

## Changes (mobile only)

1. Page shell: prevent horizontal overflow; comfortable horizontal padding
2. Left sidebar / toolbar: reduce padding and gaps; ≥44px touch targets
3. Typography: smaller h1, readable body, wrap long links
4. Home avatar + article images: constrained sizes, `max-width: 100%`
5. Right sidebar / footer: less crowding, wrap footer links

## Out of scope

- Desktop/tablet layout changes
- Plugin or `base.scss` edits
- Content rewrite
