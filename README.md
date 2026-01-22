# Molecular-Analysis
Molecular Analysis Vector Definition and Visualization of 5CB LCs


# OVITO Export (Twist angle + colored molecules)

Small GUI tool to:
1) Read snapshot files `SnapShot#.txt` containing atom coordinates for multiple molecules (38 atoms per molecule)
2) Compute a per-molecule twist angle from ring normals
3) Export an OVITO-readable XYZ-like file: `OvitoFile2_#.txt` including angle (deg), radius, and RGB color

## Input format
Each atom row is expected to have 6 tokens.
Coordinates are taken from tokens 4-6 (0-index: 3,4,5).

Snapshot files must be named:
- `SnapShot1.txt`, `SnapShot2.txt`, ...

## Install
```bash
pip install -r requirements.txt
