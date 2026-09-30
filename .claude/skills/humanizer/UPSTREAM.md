# Upstream

This skill is a vendored copy of a third-party skill. It was not written here.

- **Source:** https://github.com/blader/humanizer
- **Author:** Siqi Chen
- **License:** MIT (see `LICENSE`)
- **Skill version:** 3.0.0
- **Vendored at commit:** `9862685f575c65a8247f90369951df1b3416e3d6` (2026-09-06)

Only `SKILL.md` is needed at runtime; it is self-contained and references no other
files. The upstream repo also carries a README, plugin manifests and a validation
script, none of which the skill needs to run.

## Updating

    git clone --depth 1 https://github.com/blader/humanizer.git /tmp/humanizer
    cp /tmp/humanizer/SKILL.md /tmp/humanizer/LICENSE .claude/skills/humanizer/

Then bump the version and commit hash recorded above.
