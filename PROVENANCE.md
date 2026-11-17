# Provenance — Atlas Factory

**Atlas Factory is a fork.** It is the house's name and the house's roster on top of a design that
someone else wrote, and this file says exactly whose.

| Field | Value |
|---|---|
| Upstream | `disler/super-simple-software-factory` (via the `Way-Of` fork) |
| Upstream author | IndyDevDan |
| Licence | **MIT** — kept verbatim in `LICENSE`, as MIT requires |
| Our change | **the name**: Super Simple Software Factory → **Atlas Factory**; every identifier follows (`atlas_factory.config.yaml`, `adws/adw_atlas_factory/`, `atlas_factory.db`, `ATLAS_FACTORY_*` env), the skill is `.claude/skills/atlas-factory/`, and the visualizer is `atlas-factory-visualizer` |
| Not changed | the architecture: deterministic Python owns the graph, agents are bounded phase nodes, typed envelopes cross the seams, SQLite traces every event |
| Our additions | see `ATLAS.md` — the roster, the gates, and the phases that make it Atlas's factory rather than a demo |

**Why the rename is not cosmetic.** A skill is read by an agent, and a name is what the agent reaches
for. `sssf` names another project's product; `atlas-factory` names ours, appears in our paths, and is
the string a person will type. R-02 in the house law is the same rule from the other side: never let
another product's name into our tools.

**Updating from upstream:** `git fetch upstream && git diff main upstream/main` — read it as a proposal,
never merge blind. The upstream is a teaching repo that changes shape; this fork is a working tool.
