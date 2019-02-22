This repository contains all localizations for the Sophos Central UI.

English language files only (named en-us.json) exist in various directories in the UI repository.
That other repository is at https://git.cloud.sophos/projects/CLOUD/repos/ui/browse

At build time, the Central build will take the most recent release branch from *this* repository and
fold it in with the English language files to form a set of directories that can be pushed to
the CDN which Sophos uses to store UI assets.

This repo should be written to only by members of the localization team, not by Sophos engineering.

