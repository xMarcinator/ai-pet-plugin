# AiPet plugin: release builds

The release workflow of [xMarcinator/ai-pet](https://github.com/xMarcinator/ai-pet) writes this repository.
Each commit is one release of the AiPet plugin for Claude Code and Codex, tagged with its version, with the
hook binaries in `plugins/aipet/native/`. The marketplaces in ai-pet pin each release by tag and commit.

Don't change anything here by hand: change the plugin in ai-pet, and release it from there. To install AiPet
and the plugin, see the [ai-pet README](https://github.com/xMarcinator/ai-pet#readme).
