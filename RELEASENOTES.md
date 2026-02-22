# Hotfix Release - v01.10

This is a critical stability update to fix the C2-12828-1 system crash and update theme assets.

## Changes in v01.10

* **Fixed C2-12828-1 Crash:** Reorganized the `theme.xml` structure to match requirements. Internal parser requires a specific tag order to load theme data into memory; this has now been corrected and verified working.
* **Updated Preview Asset:** Updated `preview_thumbnail.png` with a new design.

## Installation Note

If you have a previous version installed that is causing crashes, please delete the theme folder from `ux0:theme/`, copy the new v01.10 folder, and reinstall via Theme Manager EX.
