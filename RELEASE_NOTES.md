# Release Notes

## 2026-10-03

* docs: update RELEASE_NOTES.md (b951d91d)
* chore: add missing GitHub files (4258e080)
* ci: add Gource visualization workflow + README section (a141765f)
* feat(codex): resume host Codex panes from their SessionStart id (#4098) (af559889)
* chore(deps): bump the web-minor-patch group across 1 directory with 6 updates (#4163) (218d6ce5)
* fix(migrations): name the path when v027 fails to copy a store tree (#4175) (#4176) (2b546424)
* chore(deps): bump @assistant-ui/react from 0.15.19 to 0.15.21 in /web (#4165) (1d978605)
* chore(deps): bump zod (#4171) (6064668c)
* chore(deps): bump the ai-sdk group (#4170) (015e931b)
* chore(deps): bump the cargo-minor-patch group with 4 updates (#4162) (b5fe4877)
* chore(deps): bump react-dom and @types/react-dom in /web (#4164) (ea3d22d9)
* chore(deps): bump the actions-minor-patch group across 1 directory with 7 updates (#4172) (ba6f9da0)
* fix: cast the explicit file mode to mode_t so the Darwin build compiles (#4174) (9d1d3956)
* feat(session): add smart-rename override for scratch sessions (#4138) (64ce01ac)
* fix(migrations): take a recovery backup before a migration retypes a field (#4152) (859def7d)
* fix(session): report why an explicit resume or fork is refused (#4137 point 3) (#4147) (942407c2)
* fix(session): compare sandboxed capture peers on their per-session store (#4143) (b38a3641)
* fix(session): re-probe on a schedule when a session has nothing to poll (#4141) (9dc6fcac)
* fix(session): warn when a recorded Claude store overrides agent_config_dir (#4142) (a9da36f2)
* fix(plugin): count only in-flight sessions against the per-plugin cap (#4120) (16ca70d1)
