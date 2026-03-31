# Ascend

A stealth-traversal game prototype built in Unreal Engine, developed as part of a Master's thesis at Darmstadt University of Applied Sciences. The game runs on both VR (Meta Quest, SteamVR) and PC from a single codebase, with only three configuration changes between platforms.

Ascend was designed as a research instrument to compare sensory engagement, user control, and comfort between Virtual Reality and traditional screen-based gaming. Ten participants played both versions, and their experiences were analyzed using reflexive thematic analysis.

## About the Research

**Thesis:** Comparative Analysis of Sensory Engagement, User Control, and Comfort in Virtual Reality and non-Virtual Reality Games

**Author:** Mesbah Ur Rahman

**Supervisors:** Prof. Claudius Coenen, Owi Mahn

**University:** Darmstadt University of Applied Sciences, M.A. Expanded Media

**Semester:** Winter Semester 2025/26

The full thesis is available on [Zenodo](https://zenodo.org/records/19340693).

## Gameplay Overview

The player takes on the role of a character navigating a stealth-based environment with traversal mechanics. The game features one blockout level combining:

- Stealth-based AI encounters with a four-state detection system
- Six traversal types including rope climbing, ziplines, balance beams, and elevators
- Checkpoint and sonar scan systems
- Narrative and dialogue with voice-over

Each mechanic is adapted for both VR and PC interaction models.

## Technical Highlights

- **Single codebase** for VR and PC with minimal platform-specific branching
- **Four-state stealth AI** with a visible detection bar and tunable thresholds exposed to designers
- **Traversal system** with six distinct movement types, each handling VR and PC input independently
- **Blueprint-driven** architecture for rapid iteration and easy modification

## Built With

- Unreal Engine 5.4.4
- Blueprint Visual Scripting
- Blender 3D
- Krita

## Platforms

- PC (Windows)
- VR (Meta Quest via Link, SteamVR)

## Note on Third-Party Assets

During the development of the game prototype, I utilized a blockout tool and two animation packs available through the Fab marketplace (https://www.fab.com/). These marketplaces do not allow for open-source access. To make my source code publicly available via a GitHub repository or another public repository in the near future, I had to remove all paid assets from the prototype and provide only those I owned or could use under an open-source license. The prototype is mostly running fine with few minor issues, and I have included test builds for anyone who wishes to run the original version at full capacity. Some animation and art glitches, along with minor optimization issues in VR, may arise due to the underlying asset structure changes.

## Third-Party Credits

- [Sci-Fi Gun](https://sketchfab.com/3d-models/sci-fi-gun-82ea4530b9a44829967bcd6f699aae49) by chanmagomed (Sketchfab)
- [Meta Quest Controller Models](https://developers.meta.com/horizon/downloads/package/oculus-controller-art/) by Meta
- Game UI Font sourced from [dafont.com](https://www.dafont.com/)

## Getting Started

### Prerequisites

- Unreal Engine 5.4.4
- Git
- VR headset (optional, for VR mode)

### Setup

1. Clone the repository
   ```
   git clone https://github.com/murahman-dev/ASCEND.git
   ```
2. Open the `.uproject` file in Unreal Engine
3. To switch between VR and PC mode, refer to the platform configuration notes in the project

## Test Builds

Playable builds of the original version with all assets intact are available on [itch.io](https://mrahman.itch.io/ascend).

## Playthrough Videos

- [PC Walkthrough](https://www.youtube.com/watch?v=peVHwaFNngI)
- [VR Walkthrough](https://www.youtube.com/watch?v=4j5ZMWEEl2E)

## License

This project is open-source under the [MIT License](LICENSE).

The accompanying thesis and research data are licensed separately under [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/).

## Citation

If you use this prototype or reference this work in your research, please cite:

```
Rahman, M. U. (2026). Comparative Analysis of Sensory Engagement, User Control,
and Comfort in Virtual Reality and non-Virtual Reality Games.
Master's Thesis, Darmstadt University of Applied Sciences.
DOI: 10.5281/zenodo.19340693
```

## Contact

Mesbah Ur Rahman
- Email: mesbah@murahman.com
- LinkedIn: [linkedin.com/in/mesbah-ur-rahman997](https://www.linkedin.com/in/mesbah-ur-rahman997)
