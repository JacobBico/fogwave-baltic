# Notice

## Original work

Fogwave was created by **kalarina** and is available at:

- https://git.skysparkle.cc/kalarina/Fogwave
- https://github.com/kalarina-bit/Fogwave

It is licensed under the GNU General Public License v3.0 only (see [LICENSE](LICENSE)).

## This fork

This repository, https://github.com/JacobBico/fogwave-baltic, is a modified version of Fogwave. It was modified by JacobBico on 2026-11-07. The modifications are:

- **Stations added** (`app/src/main/java/cc/skysparkle/fogwave/data/repository/RadioRepository.kt`): LRT Radijas and Žinių radijas (Lithuania), Latvijas Radio 1 and Latvijas Radio 2 (Latvia).
- **Genres added** (`app/src/main/java/cc/skysparkle/fogwave/data/model/RadioStation.kt`): News & talk, and Latvian.
- **Translations** of the new station descriptions and genres (`app/src/main/res/values*/strings.xml`).
- **Application ID changed** to `io.github.jacobbico.fogwave.baltic` so this build can be installed next to the original (`app/build.gradle.kts`).
- **About screen** links to this repository and to the original (`app/src/main/java/cc/skysparkle/fogwave/ui/components/AboutPanel.kt`).
- **App name** changed to `fogwave-baltic` (`app/src/main/res/values*/strings.xml`, store titles).
- **Documentation and store text**: README, CONTRIBUTING, fastlane store descriptions, and the issue templates (moved from `.gitea/` to `.github/`).

Everything else is unchanged from the original.

## Third-party content

Station names, logos and audio streams belong to their broadcasters. Their use here is limited to the app's function of playing the public streams.
