# Sterling media section

## Goal
Add a Foundation-styled section that points visitors to the long-form English videos on the Arthur Sterling YouTube channel and to the wider Tempus Code universe website.

## Editorial boundary
The page must distinguish the external media from the Foundation's fictional 2008 archive. It should not present the videos or the universe website as 2008 catalogue records, archival holdings, or documentary evidence. Spanish-language videos are intentionally excluded.

## Tasks
- [x] Add a dedicated `media.html` page using the existing static page shell and visual language.
- [x] List the two current long-form English videos with title, duration, and external YouTube links.
- [x] Link to the English entry point for the Tempus Code universe (`https://thetempuscode.com/en/`) and the main site (`https://thetempuscode.com/`) as an external related resource.
- [x] Add the page to the primary navigation and sitemap.
- [x] Validate local references and inspect the final diff.

## Non-goals
- No embedded YouTube player or JavaScript.
- No Spanish-language video listing.
- No changes to the historical archive content or visual system.

## Evidence
- `yt-dlp` inventory on 2026-03-10 found two English long-form videos and one Spanish video on `@ArthurSterlingF`.
- Existing README requires static HTML/CSS and no build step.
- HTML parser validation passed for all 17 pages and Media navigation is present on all 17 pages.
- One pre-existing missing local reference remains: `elizabeth-crawford.html` -> `assets/elizabeth-crawford-portrait.png`.
