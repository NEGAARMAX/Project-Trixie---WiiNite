# Changelog

All notable public changes to **Project Trixie — WiiNite** are documented here.

This changelog describes the consolidated **1.0.0** release and summarizes major development milestones. The many internal experiments and beta builds are grouped by phase rather than listed individually.

## [1.0.0] — Initial Public Release

### General

- Released four Wii-inspired themes for Playnite: **Desktop Light**, **Desktop Dark**, **Fullscreen Original**, and **Fullscreen Dark**.
- Assigned independent theme identifiers so the color variants of each mode can be installed separately.
- Prepared public **Bring Your Own Assets (BYOA)** editions, distinct from the author's personal setup. Personal artwork, collected game/platform icon packs, and original Nintendo Wii audio are not included.
- Added shared documentation for installation, optional integrations, asset customization, screenshots, development history, and third-party acknowledgments.

### Desktop — Light & Dark

- Adapted the **KNARZnite** desktop theme into a Wii-inspired interface, with customized frames, colors, and play/info controls.
- Refined the grid and game-details presentation, including a full-width **16:9** game-background area and positioning for logos supplied through **Extra Metadata Loader**.
- Retained integration points for **Moondancer Media Manager**, **ThemeModifier**, **ThemeExtras**, and **LibraryManagement**.
- Preserved empty banner directories for user-supplied artwork instead of distributing the original library banners.
- Included two interchangeable Desktop theme-icon images, with support for replacing the default icon with user artwork. Icon switching is performed by renaming/replacing files, not through an in-app selector.
- Refined the Light and Dark editions independently and corrected the `themeExtras.yaml` theme identifier for each.

### Fullscreen — Original & Dark

- Developed a Wii-inspired Fullscreen interface with channel-style presentation, custom controls, and dedicated game views.
- Reworked controller navigation and channel selection through successive beta phases, including refinements to button behavior and transitions between views.
- Improved the game-details experience and its visual hierarchy, including background/logo presentation and the arrangement of interface elements.
- Added mouse-based movement between channels and refined the remaining visual details.
- Iteratively corrected inconsistent colors and styling across controls, menus, and views to achieve a more uniform appearance.
- Developed a separately installable Dark edition and refined its colors and visual consistency.
- Developed sound integration during internal testing; the public BYOA packages include **replaceable placeholder audio**, not original Wii recordings.
- Kept the icon directories ready for user-supplied artwork without bundling the author's collected icon sets.

### Packaging and documentation

- Prepared separate installable packages for all four editions.
- Documented the BYOA workflow, optional Playnite extensions, and Desktop-only icon customization.
- Consolidated acknowledgments and licensing notices for the projects used as bases or development references.

## Development history — Before 1.0.0

Project Trixie did not follow a single uninterrupted development path. Several prototypes were abandoned or rebuilt before the final interface took shape. The counts below reflect the author's development records and recollections; some short-lived debugging builds were never individually counted.

### Fullscreen development

- **Initial experiments — more than 50 attempts:** Early approaches exposed limitations in artwork presentation. Addressing those needs eventually led to the separate **Moondancer Media Manager** extension.
- **Aniki Remake prototype — approximately 20 attempts:** Development restarted using Aniki Remake as a base, but that approach was discontinued when it failed to provide a sufficiently solid direction.
- **Rebuilding from scratch — more than 30 betas (0.1.00–0.4.00):** The theme acquired its own structure and Wii-inspired visual identity, with **Duk FST** serving as a development reference.
- **Visual consistency — 78 betas:** Numerous styling issues and difficult-to-correct color inconsistencies were resolved across the interface.
- **Mouse navigation and final visual refinements — 14 betas (0.5.00 series):** Added movement between channels using the mouse and polished the remaining presentation details.
- **Sound integration — 6 betas:** Tested and integrated sound behavior during development.
- **Dark edition — 48 betas (0.7.00 series):** Refined the dark color scheme and made its appearance consistent throughout the interface.

### Desktop development

- **Light edition — 30 betas:** Developed and polished the Wii-inspired desktop layout.
- **Dark edition — 8 betas:** Adjusted and refined the darker visual variant.
- Earlier development foundations, including the **0.4.8** and **0.3.0** branches referenced in the author's records, informed the final **1.0.0** editions.

### About the beta count

The phases above account for **more than 284** recorded attempts and beta iterations across Desktop and Fullscreen. Additional uncounted troubleshooting builds, including experiments that introduced bugs or crashes and required further fixes, bring the author's overall development count to **more than 300**. These were internal builds, not 300 public releases.

## Notes

- Version **1.0.0** is the first consolidated public release; intermediate experimental versions are not individually published in this changelog.
- The public BYOA packages intentionally differ from the author's private installation.
- Third-party copyright, licensing, and asset-provenance information is documented separately in `THIRD-PARTY-NOTICES.md`.
