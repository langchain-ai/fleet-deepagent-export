# fleet/

Your LangSmith Fleet export goes here.

```bash
unzip path/to/my-export.zip -d fleet/
```

After unzipping, this directory should contain `AGENTS.md`, `config.json`,
`tools.json`, and (optionally) `skills/` and `subagents/`. The runtime reads
those files to wire up the agent — see the top-level `README.md` for the full
flow.

Re-exporting later? Wipe and re-unzip; nothing else in the project is touched:

```bash
rm -rf fleet && unzip path/to/my-new-export.zip -d fleet/
```
