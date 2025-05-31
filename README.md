# Overhead Whitelist System

This script checks whether the game PlaceId is allowed to load the Overhead UI by checking a JSON file hosted on GitHub.

## Usage
1. Replace `yourusername` in the loader URL with your GitHub username.
2. Add your place IDs to `whitelist.json`.
3. Put your actual Overhead system in a ModuleScript named `OverheadSystem`.

If the PlaceId is not listed in `whitelist.json`, the script will stop and print a warning.
