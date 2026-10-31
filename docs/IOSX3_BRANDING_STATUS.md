# iOSX3 branding status

## 2026-10-31 source and repository rename

- Public project name: iOSX3. This repository remains a fork of
  `ARMSX2/ARMSX3`, with original history, attribution, and GPL licensing.
- `master` is an overview/publication branch. Current app and core source
  are on `ios-core`; the branches are intentionally not bulk-synchronized.
- The existing bundle identifier and user-data keys remain unchanged for
  in-place updates. Current app display strings and icon assets are changed
  on `ios-core`, but no renamed IPA is released or physically qualified yet.
- V0.35 release assets and screenshots predate the rename and are still
  accurately labeled ARMSX3. Do not relabel historical device evidence.
- GTA V gameplay on the modern iPad is still a separate failed gate; the
  branding change does not imply compatibility or performance. Relevant
  upstream implementation changes will be reviewed only after that gate
  passes, as requested by the owner.

Rollback: restore the prior branch commits and repository name. Do not
change the bundle identifier or delete either app container during rollback.
