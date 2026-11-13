# Changes in can4vscp-beijing

Every change that goes into a release is listed here, newest release first.
Add each change under **Unreleased** when it is made. When a release is
tagged, rename **Unreleased** to the version and date, and start a new
**Unreleased** section above it.

## Unreleased

- Updated license to CERN (77ff77d)
- Transfered docs to Markdown (726d3e0)
- Fixed link to issues (f2f3a27)
- /home/akhe/development/VSCP/can4vscp-odessa/LICENSE (f71f64b)
- Fixed links to chnaged URL's (4a3011c)
- Removed dangerous plugins from old wiki (b9c575b)
- Fixed files for the new naming convention (32fb1bf)
- Added nojekyll (e5cb1c0)
- Smaller VSCP logo on cover page (54ba827)
- Added logo files (9899a0a)
- Fixed index links (8db33c8)
- Changed log path (570fd23)
- Changed path for logo (1e59297)
- Added missing logo file (c99888f)
- Corrected schema rev B path again (94d5df1)
- Correcyed schema rev B path (8136b49)
- Moved images to docs (a71264e)
- Initial manual (7d18c75)
- Convert schema to kicad (0fb9511)
- Removed patreon funding option (6f08ac9)
- mdf: Added target code to firmware (31c8523)
- Updated picture content in MDF (3d8fb40)
- Renamed missnamed files (5d35dfa)
- kicad conversion of schema and board (d248145)
- Updated copyright dates (6a7a7b3)
- Updated copyright dates (57b4af4)

## v1.1.6 - 2020-05-14

- init button now at 2500 ms, seconds counter fixed. VSCP core 1.6.3 (6743215)
- on/off events now only when enabled also for short pulse (d1108a9)
- Fixed init. problem for protection timer reported by Steve Skula (6b49bba)
- Added subzone specific check to short pulse (b31d2c7)
- Added event logic to pulse output addition (1dfeaca)
- Added missing on-event flaggings as ntified by Steve Skula (81eace8)
- Pulse output in place. Changed to 1 ms resolution instead of 10 ms. (2e825b8)
- Added some stock images (a706ba0)
- MDF for short pulse had wrong action code (6), should be 8. (9846a42)
- Fixes #5 (0ccd58a)
- Added a new action shortpulse and a new register (0:47) for the timing. The shortpulse functionality is intended for bistable relays. (d8cd348)
- Added pullup picture (1513b2c)
- Fixed typo in doActionOff, do ActionPulseOn and do ActionPulseOff  Credets Steve S. (b498ca1)
- Acrion on for channel 9 wrong, fixed. Credits Steve Skula (28ce8fb)
- Wrong mask used. Thanks Steve (07b4f0d)
- Changed bit time calculation link (feda5fb)
- RA4 set to input to prevent collision with VCAP circuits in PIC18F2580. Brown out raised to maximum (3V & 4.6V). Valuable input from Anders Forsgren, AJE Electronics AB. (cbc64f9)
- vscp_getMatrixInfo nw use the pointer supplied by the framework. (654830b)
- Changed value of C14 to 10uF (284b23d)
- D (e02c6c8)
- Delete Bejing.X.production.hex (aefb4c3)
- Delete Bejing.X.production.map (d24a064)
- Delete Bejing.X.production.hex (413f2b4)
- Delete Bejing.X.production.map (d901fee)
- Delete Bejing.X.production.mum (7378a77)
- Delete Bejing.X.production.hex (3d362f4)
