# Tiamat.au

Complete replacement release for 10 November 2026.

This package:

- publishes The Returning Room, Book Eight of The Else Chronicles;
- updates the homepage, Stories page, artwork gallery, metadata, and sitemap;
- converts internal navigation and asset links to root-relative paths;
- makes all Home and brand links point to `/`;
- repairs nested-path 404 styling and Return Home behavior;
- consolidates the homepage CSS additions into `style.css`;
- reformats the supplied HTML for human readability;
- preserves the existing content and visual identity.

Upload the contents of this folder to the repository root, preserving folders and replacing matching files. Then place the separately supplied authoritative Book Eight PDF at `downloads/else-chronicles/the-returning-room-first-edition.pdf`. The deprecated helper files `style-additions.css` and `tiamat-home-fix.css` are intentionally not included because their active rules are consolidated into `style.css`.
