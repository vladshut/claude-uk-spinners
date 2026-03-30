Read the `spinners.json` file from the repository root directory.

Then read the user's `~/.claude/settings.json` file.

Copy the `spinnerVerbs` field from `spinners.json` into `~/.claude/settings.json`.

If `spinnerVerbs` already exists in `settings.json`, replace it entirely with the new value. If it does not exist, add it as a new field.

Do not modify any other fields in `settings.json` — only change `spinnerVerbs`.

After writing the file, confirm to the user that the Ukrainian spinner phrases have been installed successfully.
