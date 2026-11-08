# Will-o-Plugins

One Dalamud custom repository for all of Will o' Cinnamon's FFXIV plugins:

| Plugin | What it does |
|---|---|
| **Will-o-Patchwisp** | Patch notes for your Dalamud plugins: changelogs when they update, available updates with one-click install, GitHub release notes when a plugin has no changelog. |
| **Will-o-Muter** | Mutes the ambient sounds when a crowd gathers around you, and restores them when it thins out. |

## Install

1. In game, type `/xlsettings` and open the **Experimental** tab.
2. Under **Custom Plugin Repositories**, paste this URL, click **+**, tick **Enabled** and **Save and Close**:

   ```
   https://raw.githubusercontent.com/NeonGhostCinnamon/WillOPlugins/HEAD/repo.json
   ```

3. Type `/xlplugins` and install **Will-o-Patchwisp** and/or **Will-o-Muter**.

## How this repository works (for the author)

`repo.json` is built automatically from each plugin's own `repo.json` (listed in `sources.json`) every 30 minutes.
After releasing a plugin you can also open **Actions → Update plugin list → Run workflow** to update it right away.
To add another plugin later, add a line to `sources.json`.
