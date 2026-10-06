# Changelog

## 1.0.6 (2026-10-05)

New

- Enabled RemuxDB Integration.

Changes

- Updated the English formatter.
- Fixed the missing separator after the original-language label.
- Simplified unknown subtitles to display SUB (🏳️).
- Updated the Tamtaro formatter to its latest Default preset.

## 1.0.5 (2026-10-03)

New

- Added an optional NZBatlas protection setting for Usenet services other than TorBox. Enabled by default, it preserves the first two NZBatlas results.

Changes

- Reordered P2P and HTTP addons: STorz, PenguPlay, HdHub, Sootio, Meteor, Comet, OpenSubtitles V3+, SubDL, and SubSource.
- Enabled Include AI Translated subtitles and Movie Hash + Auto Adjustment for OpenSubtitles V3+ in the P2P profile.
- Removed TorBox download limits from the P2P profile. Limits now apply only when TorBox is selected.
- Updated the Arabic formatter to show the series name, season, and episode number without the episode title.
- Updated the Arabic formatter to show only the highest audio channel value.
- Updated Arabic quality labels for DVDRip and Remux.
- Updated formatter and addon option labels, Stream Expression comments, and the result count description to clarify that Usenet results have separate limits.

## 1.0.4 (2026-10-02)

Changes

- Changed the template summary.
- Updated the addon description.
- Updated the English and Arabic formatters.

## 1.0.3 (2026-10-02)

Changes

- Removed the 111477 addon from the P2P and HTTP profile and its exit conditions.
- Fixed the default search option so it selects the Default Addon Fetching Strategy instead of Dynamic. The fast option remains Dynamic with a 3.5-second exit condition.
- Updated the English and Arabic formatters.

## 1.0.2 (2026-10-02)

New

- Added the 111477 addon to the P2P and HTTP profile.
- Updated the Arabic formatter to display the addon name as ١١١٤٧٧.

Changes

- Fixed P2P template validation by supplying empty arrays for services and variants when no service is selected.
- Corrected the Addon Fetching Strategy mapping so the five-second option uses the default exit condition.

## 1.0.1 (2026-09-28)

New

- Added Tamtaro and Jellyfin formatter options.

Changes

- Made Quality First the default sorting priority. Resolution First and Subtitles First remain available.
- Updated the template version.

## 1.0.0 (2026-09-28)

- Initial release of the StremioLabAR template.
