# contribution tracker

[contributions.tscircuit.com](https://contributions.tscircuit.com) ・ [tscircuit.com](https://tscircuit.com) ・ [Contribution Overviews](./contribution-overviews/) ・ [Changelogs](./changelogs/)

Generates weekly contribution overviews for tscircuit contributors. Check out all
the [contribution overviews here](./contribution-overviews/)
You can find AI-generated monthly changelogs in the [changelogs directory](./changelogs/)

- All PRs in the tscircuit org are scanned/summarized via an LLM
- The LLM classifies each Diff/PR as into a set of attributes for scoring
- All the PRs, summaries, and classifications are organized into charts and tables for [the website](https://contributions.tscircuit.com)

> Want to run locally? See the [Development Section](#development)

## Current Week

<!-- START_CURRENT_WEEK -->

# Contribution Overview 2026-04-21

The current week is shown below. There are 3 major sections:

- [Contributor Overview](#contributor-overview)
- [PRs by Repository](#prs-by-repository)
- [PRs by Contributor](#changes-by-contributor)
- [Scoring & Sponsorship Details](/docs/sponsorship-calculation-explanation.md)

## PRs by Repository

```mermaid
pie
    "tscircuit/tscircuit" : 14
    "tscircuit/circuit-json" : 2
    "tscircuit/core" : 16
    "tscircuit/tscircuit.com" : 34
    "tscircuit/eval" : 28
    "tscircuit/runframe" : 39
    "tscircuit/cli" : 41
    "tscircuit/svg.tscircuit.com" : 2
    "tscircuit/tscircuit-autorouter" : 12
    "tscircuit/test-github-automerge" : 1
    "tscircuit/circuit-json-to-kicad" : 9
    "tscircuit/rectdiff" : 3
    "tscircuit/high-density-a01" : 2
    "tscircuit/circuit-json-util" : 1
    "tscircuit/circuit-to-svg" : 1
    "tscircuit/checks" : 5
    "tscircuit/props" : 3
    "tscircuit/kicad-to-circuit-json" : 1
    "tscircuit/jlcpcb-manufacturing-specs" : 1
    "tscircuit/easyeda-converter" : 1
    "tscircuit/3d-viewer" : 1
    "tscircuit/high-density-repair03" : 1
    "tscircuit/jscad-electronics" : 1
    "tscircuit/circuit-json-to-gltf" : 1
    "tscircuit/circuit-json-to-gerber" : 1
    "tscircuit/tscircuit.com-landing" : 3
    "tscircuit/docs" : 1
    "tscircuit/high-density-repair01" : 2
    "tscircuit/schematic-trace-solver" : 2
```

## Contributor Overview

| Contributor | 🐳 Major | 🐙 Minor | 🐌 Tiny | Score | ⭐ | Discussion Contributions |
|-------------|---------|---------|---------|-------|-----|--------------------------|
| [ShiboSoftwareDev](#ShiboSoftwareDev) | 4 | 5 | 2 | 30 | ⭐⭐ | 0🔹 0🔶 0💎 |
| [Abse2001](#Abse2001) | 4 | 0 | 3 | 21 | ⭐⭐ | 0🔹 0🔶 0💎 |
| [AnasSarkiz](#AnasSarkiz) | 4 | 1 | 0 | 21 | ⭐⭐ | 0🔹 0🔶 0💎 |
| [imrishabh18](#imrishabh18) | 0 | 3 | 9 | 16 | ⭐⭐ | 0🔹 0🔶 0💎 |
| [tscircuitbot](#tscircuitbot) | 0 | 0 | 169 | 13.5 | ⭐⭐ | 0🔹 0🔶 0💎 |
| [techmannih](#techmannih) | 0 | 4 | 4 | 13 | ⭐⭐ | 0🔹 0🔶 0💎 |
| [rushabhcodes](#rushabhcodes) | 0 | 0 | 6 | 7 | ⭐ | 0🔹 0🔶 0💎 |
| [0hmX](#0hmX) | 1 | 0 | 3 | 7 | ⭐ | 0🔹 0🔶 0💎 |
| [mohan-bee](#mohan-bee) | 0 | 2 | 1 | 5 | ⭐ | 0🔹 0🔶 0💎 |
| [seveibar](#seveibar) | 1 | 0 | 0 | 5 | ⭐ | 0🔹 0🔶 0💎 |
| [Sang-it](#Sang-it) | 0 | 1 | 2 | 4 | ⭐ | 0🔹 0🔶 0💎 |

## Staff Pass Ratio (SPR)

| Contributor | Reviewed PRs | Rejections | Approvals | SPR |
|-------------|--------------|------------|-----------|-----|
| [ShiboSoftwareDev](#ShiboSoftwareDev) | 8 | 0 | 8 | 100.0% |
| [techmannih](#techmannih) | 4 | 0 | 4 | 100.0% |
| [mohan-bee](#mohan-bee) | 3 | 0 | 3 | 100.0% |
| [AnasSarkiz](#AnasSarkiz) | 2 | 0 | 2 | 100.0% |
| [0hmX](#0hmX) | 2 | 0 | 2 | 100.0% |
| [imrishabh18](#imrishabh18) | 1 | 0 | 1 | 100.0% |
| [Abse2001](#Abse2001) | 1 | 0 | 1 | 100.0% |
| [Sang-it](#Sang-it) | 1 | 1 | 0 | 0.0% |

<details>
<summary>ShiboSoftwareDev SPR PRs (8)</summary>

- [#94](https://github.com/tscircuit/circuit-json-util/pull/94) Transform pcb_component insertion metadata in transformPCBElements
- [#2178](https://github.com/tscircuit/core/pull/2178) Bump @tscircuit/checks and add connector orientation regression tests
- [#2165](https://github.com/tscircuit/core/pull/2165) Wire footprint insertion direction into PCB components and align board DRC fields
- [#2168](https://github.com/tscircuit/core/pull/2168)  Align sim graph colors with differential probe names and refresh palette
- [#2169](https://github.com/tscircuit/core/pull/2169) Propagate board min via dimensions through autorouting
- [#2162](https://github.com/tscircuit/core/pull/2162) Infer internal footprint connections for split pins and shared aliases
- [#141](https://github.com/tscircuit/checks/pull/141) Use insertion_direction for connector accessibility checks
- [#950](https://github.com/tscircuit/tscircuit-autorouter/pull/950) Honor explicit via pad/hole dimensions across autorouters

</details>

<details>
<summary>techmannih SPR PRs (4)</summary>

- [#2170](https://github.com/tscircuit/core/pull/2170) Add rectBorderRadius support to pill_hole_with_rect_pad plated holes
- [#232](https://github.com/tscircuit/circuit-json-to-kicad/pull/232) feat: include supplier part number in KiCad footprint properties
- [#233](https://github.com/tscircuit/circuit-json-to-kicad/pull/233) feat: implement rotation support for circular_hole_with_rect_pad and rotated_pill_hole_with_rect_pad
- [#62](https://github.com/tscircuit/kicad-to-circuit-json/pull/62) feat: Add support for pill_hole_with_rect_pad shape plated hole

</details>

<details>
<summary>mohan-bee SPR PRs (3)</summary>

- [#3197](https://github.com/tscircuit/runframe/pull/3197) Fix package details dialog stacking in Import Component flow
- [#241](https://github.com/tscircuit/circuit-json-to-kicad/pull/241) Use manufacturer part number for simple chip schematic values
- [#235](https://github.com/tscircuit/circuit-json-to-kicad/pull/235) Fix component-owned silkscreen paths exporting as board graphics

</details>

<details>
<summary>AnasSarkiz SPR PRs (2)</summary>

- [#949](https://github.com/tscircuit/tscircuit-autorouter/pull/949) improves margin-aware violation detection
- [#5](https://github.com/tscircuit/high-density-repair01/pull/5) Introduce projection-based clearance optimization to eliminate dense-node via and trace collisions

</details>

<details>
<summary>0hmX SPR PRs (2)</summary>

- [#959](https://github.com/tscircuit/tscircuit-autorouter/pull/959) update url for rectdiff
- [#953](https://github.com/tscircuit/tscircuit-autorouter/pull/953) add focused repro for high-density solver issue caused by reentry in nodeWithPortPoints input

</details>

<details>
<summary>imrishabh18 SPR PRs (1)</summary>

- [#137](https://github.com/tscircuit/checks/pull/137) Use pcb_board DRC values and remove JLC specs dependency import

</details>

<details>
<summary>Abse2001 SPR PRs (1)</summary>

- [#384](https://github.com/tscircuit/easyeda-converter/pull/384) Refactor CAD offset logic to use model bounds + SVG origin extraction

</details>

<details>
<summary>Sang-it SPR PRs (1)</summary>

- [#209](https://github.com/tscircuit/schematic-trace-solver/pull/209) fix single port netlabelplacemet

</details>

> Note: AI evaluates PRs and assigns 1-3 star ratings automatically. 4 and 5 star ratings require manual staff review.

### Discussion Contribution Legend

- 🔹 Normal Comments: Basic participation with minimal effort
- 🔶 Great Informative Comments: Thoughtful participation that adds value
- 💎 Incredible Comments: Exceptional participation with high-quality content

## Review Table

[reviews-received-hover]: ## "Number of reviews received for PRs for this contributor"
[approvals-received-hover]: ## "Number of approvals received for PRs this contributor authored"
[rejections-received-hover]: ## "Number of rejections received for PRs this contributor authored"
[prs-opened-hover]: ## "Number of PRs opened by this contributor"
[issues-created-hover]: ## "Number of issues created by this contributor"

| Contributor | Reviews Received | Approvals Received | Rejections Received | Approvals | Rejections Given | PRs Opened | PRs Merged | Issues Created |
|---|---|---|---|---|---|---|---|---|
| [tscircuitbot](#tscircuitbot) | 0 | 0 | 0 | 0 | 0 | 214 | 169 | 0 |
| [techmannih](#techmannih) | 11 | 9 | 0 | 1 | 0 | 9 | 8 | 0 |
| [imrishabh18](#imrishabh18) | 7 | 7 | 0 | 6 | 1 | 14 | 12 | 0 |
| [ShiboSoftwareDev](#ShiboSoftwareDev) | 11 | 11 | 0 | 2 | 0 | 12 | 11 | 0 |
| [seveibar](#seveibar) | 0 | 0 | 0 | 34 | 1 | 1 | 1 | 0 |
| [Wong789](#Wong789) | 0 | 0 | 0 | 0 | 0 | 1 | 0 | 0 |
| [mohan-bee](#mohan-bee) | 17 | 5 | 2 | 0 | 0 | 9 | 3 | 0 |
| [Abse2001](#Abse2001) | 6 | 6 | 0 | 2 | 0 | 10 | 7 | 0 |
| [AnasSarkiz](#AnasSarkiz) | 5 | 5 | 0 | 3 | 0 | 8 | 5 | 0 |
| [Lumantis](#Lumantis) | 1 | 0 | 1 | 0 | 0 | 1 | 0 | 0 |
| [rushabhcodes](#rushabhcodes) | 11 | 3 | 0 | 2 | 1 | 7 | 6 | 0 |
| [selenaalpha77-sketch](#selenaalpha77-sketch) | 0 | 0 | 0 | 0 | 0 | 2 | 0 | 0 |
| [premsreelathasugeendran](#premsreelathasugeendran) | 0 | 0 | 0 | 0 | 0 | 1 | 0 | 0 |
| [YPC0813](#YPC0813) | 0 | 0 | 0 | 0 | 0 | 1 | 0 | 0 |
| [0hmX](#0hmX) | 3 | 2 | 0 | 0 | 0 | 8 | 4 | 0 |
| [Angelebeats](#Angelebeats) | 0 | 0 | 0 | 0 | 0 | 3 | 0 | 0 |
| [pavel493](#pavel493) | 0 | 0 | 0 | 0 | 0 | 1 | 0 | 0 |
| [Myc911](#Myc911) | 0 | 0 | 0 | 0 | 0 | 1 | 0 | 0 |
| [Sang-it](#Sang-it) | 14 | 3 | 1 | 0 | 0 | 6 | 3 | 0 |
| [emabarrera](#emabarrera) | 0 | 0 | 0 | 0 | 0 | 2 | 0 | 0 |
| [Ingenieralejo](#Ingenieralejo) | 0 | 0 | 0 | 0 | 0 | 1 | 0 | 0 |
| [MustafaMulla29](#MustafaMulla29) | 0 | 0 | 0 | 1 | 1 | 0 | 0 | 0 |

## Changes by Repository

### [tscircuit/tscircuit](https://github.com/tscircuit/tscircuit)


<details>
<summary>🐌 Tiny Contributions (14)</summary>

| PR # | Impact | Contributor | Description |
|------|--------|-------------|-------------|
| [#2999](https://github.com/tscircuit/tscircuit/pull/2999) | 🐌 Tiny | tscircuitbot | Updates the package version from 0.0.1666 to 0.0.1667 in package.json |
| [#2998](https://github.com/tscircuit/tscircuit/pull/2998) | 🐌 Tiny | tscircuitbot | Automated package update |
| [#2997](https://github.com/tscircuit/tscircuit/pull/2997) | 🐌 Tiny | tscircuitbot | Automated package update |
| [#2996](https://github.com/tscircuit/tscircuit/pull/2996) | 🐌 Tiny | tscircuitbot | Automated package update |
| [#2995](https://github.com/tscircuit/tscircuit/pull/2995) | 🐌 Tiny | tscircuitbot | Automated package update |
| [#2994](https://github.com/tscircuit/tscircuit/pull/2994) | 🐌 Tiny | tscircuitbot | Automated package update |
| [#2993](https://github.com/tscircuit/tscircuit/pull/2993) | 🐌 Tiny | tscircuitbot | Automated package update |
| [#2992](https://github.com/tscircuit/tscircuit/pull/2992) | 🐌 Tiny | tscircuitbot | Updates the version of several dependencies in the package.json file, including tscircuitcli, tscircuitcore, tscircuiteval, and circuit-json-to-gltf. |
| [#2991](https://github.com/tscircuit/tscircuit/pull/2991) | 🐌 Tiny | tscircuitbot | Updates the package version from 0.0.1662 to 0.0.1663 in package.json |
| [#2990](https://github.com/tscircuit/tscircuit/pull/2990) | 🐌 Tiny | tscircuitbot | Automated package update |
| [#2983](https://github.com/tscircuit/tscircuit/pull/2983) | 🐌 Tiny | tscircuitbot | Automated package update |
| [#2975](https://github.com/tscircuit/tscircuit/pull/2975) | 🐌 Tiny | tscircuitbot | Automated package update |
| [#2974](https://github.com/tscircuit/tscircuit/pull/2974) | 🐌 Tiny | ShiboSoftwareDev | Prevents synchronization of the tscircuitjlcpcb-manufacturing-specs package during the core version copying process. |
| [#2978](https://github.com/tscircuit/tscircuit/pull/2978) | 🐌 Tiny | techmannih | Updates the tscircuitprops dependency version from 0.0.508 to 0.0.512 in package.json |

</details>

### [tscircuit/circuit-json](https://github.com/tscircuit/circuit-json)


<details>
<summary>🐌 Tiny Contributions (2)</summary>

| PR # | Impact | Contributor | Description |
|------|--------|-------------|-------------|
| [#563](https://github.com/tscircuit/circuit-json/pull/563) | 🐌 Tiny | tscircuitbot | Automated package update |
| [#562](https://github.com/tscircuit/circuit-json/pull/562) | 🐌 Tiny | imrishabh18 | Renames DRC properties for clarity and consistency in the manufacturing DRC properties interface. |

</details>

### [tscircuit/core](https://github.com/tscircuit/core)

| PR # | Impact | Rating | Contributor | Description |
|------|--------|--------|-------------|-------------|
| [#2165](https://github.com/tscircuit/core/pull/2165) | 🐳 Major | ⭐⭐⭐ | ShiboSoftwareDev | Propagates footprint.insertionDirection onto pcb_component.insertion_direction using the components global pre-layout rotation plus bottom-side mirroring, ensuring correct behavior for bottom-authored footprints and footprint constraints, while aligning board manufacturing defaults and tests with new clearance field names in circuit-json. |
| [#2169](https://github.com/tscircuit/core/pull/2169) | 🐳 Major | ⭐⭐⭐ | ShiboSoftwareDev | Propagates board minimum via dimensions through autorouting by updating the autorouter to use specific via dimensions from the board, ensuring routed via dimensions are preserved and not overwritten by defaults. |
| [#2162](https://github.com/tscircuit/core/pull/2162) | 🐳 Major | ⭐⭐⭐ | ShiboSoftwareDev | This change makes repeated non-overlapping footprint contacts behave like implicit internally connected pins instead of ambiguous PCB targets, allowing traces to target shared aliases directly and updating port matching accordingly. |
| [#2175](https://github.com/tscircuit/core/pull/2175) | 🐳 Major | ⭐⭐⭐ | Abse2001 | Adds a test for rendering a double-row pinheader and updates the circuit-json-to-gltf dependency version. |
| [#2178](https://github.com/tscircuit/core/pull/2178) | 🐙 Minor | ⭐⭐ | ShiboSoftwareDev | Bumps the version of tscircuitchecks to 0.0.122 and adds regression tests for connector orientation warnings. |
| [#2168](https://github.com/tscircuit/core/pull/2168) | 🐙 Minor | ⭐⭐ | ShiboSoftwareDev | Maps simulation voltage graphs to their corresponding probes, ensuring differential ngspice graphs inherit colors from schematicsimulation probes and updates the default simulation color palette. |
| [#2170](https://github.com/tscircuit/core/pull/2170) | 🐙 Minor | ⭐⭐ | techmannih | Adds support for rectBorderRadius in pill_hole_with_rect_pad plated holes, allowing for customizable corner rounding in PCB design. |
| [#2181](https://github.com/tscircuit/core/pull/2181) | 🐙 Minor | ⭐⭐ | imrishabh18 | Updates dependencies to the latest versions and migrates PCB manufacturing DRC field names to match the new schema in the circuit JSON. |
| [#2163](https://github.com/tscircuit/core/pull/2163) | 🐙 Minor | ⭐⭐ | imrishabh18 | Updates DRC properties in the board schema from spacing to clearance to align with upstream package changes and resolves TypeScript errors. |

<details>
<summary>🐌 Tiny Contributions (7)</summary>

| PR # | Impact | Contributor | Description |
|------|--------|-------------|-------------|
| [#2180](https://github.com/tscircuit/core/pull/2180) | 🐌 Tiny | tscircuitbot | Updates the tscircuitchecks package from version 0.0.123 to 0.0.124 |
| [#2179](https://github.com/tscircuit/core/pull/2179) | 🐌 Tiny | tscircuitbot | Updates the tscircuitchecks package from version 0.0.122 to 0.0.123 |
| [#2177](https://github.com/tscircuit/core/pull/2177) | 🐌 Tiny | tscircuitbot | Updates the tscircuitchecks package from version 0.0.121 to 0.0.122 |
| [#2172](https://github.com/tscircuit/core/pull/2172) | 🐌 Tiny | tscircuitbot | Updates the tscircuitchecks package from version 0.0.120 to 0.0.121 |
| [#2167](https://github.com/tscircuit/core/pull/2167) | 🐌 Tiny | tscircuitbot | Updates the tscircuitchecks package from version 0.0.119 to 0.0.120 in the package.json file. |
| [#2171](https://github.com/tscircuit/core/pull/2171) | 🐌 Tiny | imrishabh18 | Bundles the tscircuitjlcpcb-manufacturing-specs package with the core package, modifying the build process and configuration. |
| [#2164](https://github.com/tscircuit/core/pull/2164) | 🐌 Tiny | Abse2001 | Updates the version of the tscircuitfootprinter dependency from 0.0.349 to 0.0.351 in package.json |

</details>

### [tscircuit/tscircuit.com](https://github.com/tscircuit/tscircuit.com)


<details>
<summary>🐌 Tiny Contributions (34)</summary>

| PR # | Impact | Contributor | Description |
|------|--------|-------------|-------------|
| [#3248](https://github.com/tscircuit/tscircuit.com/pull/3248) | 🐌 Tiny | tscircuitbot | Updates the tscircuitrunframe package from version 0.0.1868 to 0.0.1869 |
| [#3247](https://github.com/tscircuit/tscircuit.com/pull/3247) | 🐌 Tiny | tscircuitbot | Updates the tscircuiteval package to version 0.0.783 |
| [#3246](https://github.com/tscircuit/tscircuit.com/pull/3246) | 🐌 Tiny | tscircuitbot | Updates the tscircuitrunframe package from version 0.0.1867 to 0.0.1868 |
| [#3245](https://github.com/tscircuit/tscircuit.com/pull/3245) | 🐌 Tiny | tscircuitbot | Updates the tscircuiteval package from version 0.0.781 to 0.0.782 |
| [#3244](https://github.com/tscircuit/tscircuit.com/pull/3244) | 🐌 Tiny | tscircuitbot | Updates the tscircuiteval package from version 0.0.780 to 0.0.781 |
| [#3243](https://github.com/tscircuit/tscircuit.com/pull/3243) | 🐌 Tiny | tscircuitbot | Updates the tscircuitrunframe package from version 0.0.1866 to 0.0.1867 |
| [#3242](https://github.com/tscircuit/tscircuit.com/pull/3242) | 🐌 Tiny | tscircuitbot | Updates the tscircuiteval package to version 0.0.780 |
| [#3241](https://github.com/tscircuit/tscircuit.com/pull/3241) | 🐌 Tiny | tscircuitbot | Automated package update |
| [#3240](https://github.com/tscircuit/tscircuit.com/pull/3240) | 🐌 Tiny | tscircuitbot | Updates the tscircuiteval package from version 0.0.778 to 0.0.779 |
| [#3239](https://github.com/tscircuit/tscircuit.com/pull/3239) | 🐌 Tiny | tscircuitbot | Updates the tscircuitrunframe package from version 0.0.1864 to 0.0.1865 |
| [#3238](https://github.com/tscircuit/tscircuit.com/pull/3238) | 🐌 Tiny | tscircuitbot | Updates the tscircuiteval package version from 0.0.777 to 0.0.778 |
| [#3237](https://github.com/tscircuit/tscircuit.com/pull/3237) | 🐌 Tiny | tscircuitbot | Updates the tscircuitrunframe package from version 0.0.1863 to 0.0.1864 |
| [#3236](https://github.com/tscircuit/tscircuit.com/pull/3236) | 🐌 Tiny | tscircuitbot | Updates the tscircuiteval package version from 0.0.776 to 0.0.777 in package.json |
| [#3229](https://github.com/tscircuit/tscircuit.com/pull/3229) | 🐌 Tiny | tscircuitbot | Updates the tscircuitrunframe package to version 0.0.1859 |
| [#3230](https://github.com/tscircuit/tscircuit.com/pull/3230) | 🐌 Tiny | tscircuitbot | Updates the tscircuiteval package to version 0.0.776 in the package.json file. |
| [#3227](https://github.com/tscircuit/tscircuit.com/pull/3227) | 🐌 Tiny | tscircuitbot | Automated package update |
| [#3234](https://github.com/tscircuit/tscircuit.com/pull/3234) | 🐌 Tiny | tscircuitbot | Updates the tscircuitrunframe package from version 0.0.1861 to 0.0.1862 |
| [#3233](https://github.com/tscircuit/tscircuit.com/pull/3233) | 🐌 Tiny | tscircuitbot | Updates the tscircuitrunframe package from version 0.0.1860 to 0.0.1861 |
| [#3226](https://github.com/tscircuit/tscircuit.com/pull/3226) | 🐌 Tiny | tscircuitbot | Updates the tscircuiteval package to version 0.0.774 |
| [#3235](https://github.com/tscircuit/tscircuit.com/pull/3235) | 🐌 Tiny | tscircuitbot | Updates the tscircuitrunframe package from version 0.0.1862 to 0.0.1863 |
| [#3231](https://github.com/tscircuit/tscircuit.com/pull/3231) | 🐌 Tiny | tscircuitbot | Automated package update |
| [#3228](https://github.com/tscircuit/tscircuit.com/pull/3228) | 🐌 Tiny | tscircuitbot | Updates the tscircuiteval package from version 0.0.774 to 0.0.775 |
| [#3212](https://github.com/tscircuit/tscircuit.com/pull/3212) | 🐌 Tiny | tscircuitbot | Automated package update |
| [#3215](https://github.com/tscircuit/tscircuit.com/pull/3215) | 🐌 Tiny | tscircuitbot | Updates the tscircuitrunframe package from version 0.0.1852 to 0.0.1853 |
| [#3222](https://github.com/tscircuit/tscircuit.com/pull/3222) | 🐌 Tiny | tscircuitbot | Updates the tscircuitrunframe package from version 0.0.1854 to 0.0.1855 |
| [#3219](https://github.com/tscircuit/tscircuit.com/pull/3219) | 🐌 Tiny | tscircuitbot | Automated package update |
| [#3221](https://github.com/tscircuit/tscircuit.com/pull/3221) | 🐌 Tiny | tscircuitbot | Updates the tscircuiteval package from version 0.0.772 to 0.0.773 |
| [#3223](https://github.com/tscircuit/tscircuit.com/pull/3223) | 🐌 Tiny | tscircuitbot | Updates the tscircuitrunframe package from version 0.0.1855 to 0.0.1857 |
| [#3217](https://github.com/tscircuit/tscircuit.com/pull/3217) | 🐌 Tiny | tscircuitbot | Automated package update |
| [#3213](https://github.com/tscircuit/tscircuit.com/pull/3213) | 🐌 Tiny | tscircuitbot | Updates the tscircuitrunframe package to version 0.0.1852 |
| [#3214](https://github.com/tscircuit/tscircuit.com/pull/3214) | 🐌 Tiny | tscircuitbot | Automated package update |
| [#3218](https://github.com/tscircuit/tscircuit.com/pull/3218) | 🐌 Tiny | tscircuitbot | Updates the tscircuitrunframe package from version 0.0.1853 to 0.0.1854 |
| [#3225](https://github.com/tscircuit/tscircuit.com/pull/3225) | 🐌 Tiny | imrishabh18 | Updates the website URL in the about section to use the package release website URL instead of the previous method of determining the URL. |
| [#3216](https://github.com/tscircuit/tscircuit.com/pull/3216) | 🐌 Tiny | rushabhcodes | Removes the local BomTable component and its associated logic as it is no longer referenced in the application, streamlining the codebase without affecting runtime behavior. |

</details>

### [tscircuit/eval](https://github.com/tscircuit/eval)


<details>
<summary>🐌 Tiny Contributions (28)</summary>

| PR # | Impact | Contributor | Description |
|------|--------|-------------|-------------|
| [#2490](https://github.com/tscircuit/eval/pull/2490) | 🐌 Tiny | tscircuitbot | Automated package update |
| [#2489](https://github.com/tscircuit/eval/pull/2489) | 🐌 Tiny | tscircuitbot | Automated package update |
| [#2487](https://github.com/tscircuit/eval/pull/2487) | 🐌 Tiny | tscircuitbot | Automated package update |
| [#2486](https://github.com/tscircuit/eval/pull/2486) | 🐌 Tiny | tscircuitbot | Updates the versions of several dependencies in the package.json file. |
| [#2484](https://github.com/tscircuit/eval/pull/2484) | 🐌 Tiny | tscircuitbot | Automated package update |
| [#2483](https://github.com/tscircuit/eval/pull/2483) | 🐌 Tiny | tscircuitbot | Updates the version of several dependencies in the package.json file. |
| [#2481](https://github.com/tscircuit/eval/pull/2481) | 🐌 Tiny | tscircuitbot | Automated package update |
| [#2480](https://github.com/tscircuit/eval/pull/2480) | 🐌 Tiny | tscircuitbot | Updates package versions in package.json to their latest compatible versions. |
| [#2478](https://github.com/tscircuit/eval/pull/2478) | 🐌 Tiny | tscircuitbot | Automated package update |
| [#2477](https://github.com/tscircuit/eval/pull/2477) | 🐌 Tiny | tscircuitbot | Updates package dependencies to their latest versions as part of routine maintenance. |
| [#2475](https://github.com/tscircuit/eval/pull/2475) | 🐌 Tiny | tscircuitbot | Automated package update |
| [#2474](https://github.com/tscircuit/eval/pull/2474) | 🐌 Tiny | tscircuitbot | Automated package update |
| [#2472](https://github.com/tscircuit/eval/pull/2472) | 🐌 Tiny | tscircuitbot | Automated package update |
| [#2471](https://github.com/tscircuit/eval/pull/2471) | 🐌 Tiny | tscircuitbot | Updates the version of the tscircuitcore package from 0.0.1185 to 0.0.1186 in package.json |
| [#2469](https://github.com/tscircuit/eval/pull/2469) | 🐌 Tiny | tscircuitbot | Automated package update to version 0.0.776 |
| [#2466](https://github.com/tscircuit/eval/pull/2466) | 🐌 Tiny | tscircuitbot | Automated package update to version 0.0.775 |
| [#2465](https://github.com/tscircuit/eval/pull/2465) | 🐌 Tiny | tscircuitbot | Automated package update |
| [#2461](https://github.com/tscircuit/eval/pull/2461) | 🐌 Tiny | tscircuitbot | Automated package update |
| [#2460](https://github.com/tscircuit/eval/pull/2460) | 🐌 Tiny | tscircuitbot | Automated package update |
| [#2468](https://github.com/tscircuit/eval/pull/2468) | 🐌 Tiny | tscircuitbot | Updates the version of the tscircuitcore and tscircuitprops packages in package.json |
| [#2458](https://github.com/tscircuit/eval/pull/2458) | 🐌 Tiny | tscircuitbot | Automated package update |
| [#2457](https://github.com/tscircuit/eval/pull/2457) | 🐌 Tiny | tscircuitbot | Automated package update |
| [#2456](https://github.com/tscircuit/eval/pull/2456) | 🐌 Tiny | tscircuitbot | Automated package update |
| [#2455](https://github.com/tscircuit/eval/pull/2455) | 🐌 Tiny | tscircuitbot | Updates package dependencies to their latest versions as part of routine maintenance. |
| [#2453](https://github.com/tscircuit/eval/pull/2453) | 🐌 Tiny | tscircuitbot | Automated package update |
| [#2452](https://github.com/tscircuit/eval/pull/2452) | 🐌 Tiny | tscircuitbot | Automated package update |
| [#2450](https://github.com/tscircuit/eval/pull/2450) | 🐌 Tiny | tscircuitbot | Automated package update |
| [#2449](https://github.com/tscircuit/eval/pull/2449) | 🐌 Tiny | tscircuitbot | Automated package update |

</details>

### [tscircuit/runframe](https://github.com/tscircuit/runframe)

| PR # | Impact | Rating | Contributor | Description |
|------|--------|--------|-------------|-------------|
| [#3197](https://github.com/tscircuit/runframe/pull/3197) | 🐙 Minor | ⭐⭐ | mohan-bee | Fixes the Import Component package details view so clicking See Details no longer appears broken when the details dialog opens behind the search dialog. |

<details>
<summary>🐌 Tiny Contributions (38)</summary>

| PR # | Impact | Contributor | Description |
|------|--------|-------------|-------------|
| [#3222](https://github.com/tscircuit/runframe/pull/3222) | 🐌 Tiny | tscircuitbot | Automated package update |
| [#3221](https://github.com/tscircuit/runframe/pull/3221) | 🐌 Tiny | tscircuitbot | Updates the tscircuiteval package to version 0.0.783 in the package.json file. |
| [#3220](https://github.com/tscircuit/runframe/pull/3220) | 🐌 Tiny | tscircuitbot | Automated package update |
| [#3219](https://github.com/tscircuit/runframe/pull/3219) | 🐌 Tiny | tscircuitbot | Updates the tscircuiteval package version from 0.0.780 to 0.0.782 in package.json |
| [#3218](https://github.com/tscircuit/runframe/pull/3218) | 🐌 Tiny | tscircuitbot | Automated package update |
| [#3217](https://github.com/tscircuit/runframe/pull/3217) | 🐌 Tiny | tscircuitbot | Updates the tscircuiteval package from version 0.0.779 to 0.0.780 |
| [#3216](https://github.com/tscircuit/runframe/pull/3216) | 🐌 Tiny | tscircuitbot | Automated package update |
| [#3215](https://github.com/tscircuit/runframe/pull/3215) | 🐌 Tiny | tscircuitbot | Updates the tscircuiteval package from version 0.0.778 to 0.0.779 in the package.json file. |
| [#3214](https://github.com/tscircuit/runframe/pull/3214) | 🐌 Tiny | tscircuitbot | Automated package update |
| [#3213](https://github.com/tscircuit/runframe/pull/3213) | 🐌 Tiny | tscircuitbot | Updates the tscircuiteval package to version 0.0.778 in the package.json file. |
| [#3212](https://github.com/tscircuit/runframe/pull/3212) | 🐌 Tiny | tscircuitbot | Automated package update |
| [#3211](https://github.com/tscircuit/runframe/pull/3211) | 🐌 Tiny | tscircuitbot | Updates the tscircuiteval package from version 0.0.776 to 0.0.777 in the package.json file. |
| [#3200](https://github.com/tscircuit/runframe/pull/3200) | 🐌 Tiny | tscircuitbot | Updates the tscircuiteval package from version 0.0.774 to 0.0.775 in the package.json file. |
| [#3199](https://github.com/tscircuit/runframe/pull/3199) | 🐌 Tiny | tscircuitbot | Automated package update |
| [#3209](https://github.com/tscircuit/runframe/pull/3209) | 🐌 Tiny | tscircuitbot | Updates the circuit-json-to-gerber package from version 0.0.48 to 0.0.49 |
| [#3198](https://github.com/tscircuit/runframe/pull/3198) | 🐌 Tiny | tscircuitbot | Updates the tscircuiteval package to version 0.0.774 in the package.json file. |
| [#3210](https://github.com/tscircuit/runframe/pull/3210) | 🐌 Tiny | tscircuitbot | Automated package update |
| [#3208](https://github.com/tscircuit/runframe/pull/3208) | 🐌 Tiny | tscircuitbot | Updates the circuit-json-to-kicad package version from 0.0.117 to 0.0.118 in package.json |
| [#3201](https://github.com/tscircuit/runframe/pull/3201) | 🐌 Tiny | tscircuitbot | Automated package update |
| [#3202](https://github.com/tscircuit/runframe/pull/3202) | 🐌 Tiny | tscircuitbot | Updates the tscircuiteval package from version 0.0.775 to 0.0.776 |
| [#3206](https://github.com/tscircuit/runframe/pull/3206) | 🐌 Tiny | tscircuitbot | Automated package update |
| [#3203](https://github.com/tscircuit/runframe/pull/3203) | 🐌 Tiny | tscircuitbot | Automated package update |
| [#3207](https://github.com/tscircuit/runframe/pull/3207) | 🐌 Tiny | tscircuitbot | Automated package update |
| [#3205](https://github.com/tscircuit/runframe/pull/3205) | 🐌 Tiny | tscircuitbot | Updates the circuit-json-to-kicad package from version 0.0.116 to 0.0.117 |
| [#3180](https://github.com/tscircuit/runframe/pull/3180) | 🐌 Tiny | tscircuitbot | Updates the tscircuit3d-viewer package to version 0.0.556 in package.json |
| [#3190](https://github.com/tscircuit/runframe/pull/3190) | 🐌 Tiny | tscircuitbot | Updates the tscircuiteval package from version 0.0.771 to 0.0.772 in the package.json file. |
| [#3192](https://github.com/tscircuit/runframe/pull/3192) | 🐌 Tiny | tscircuitbot | Updates the tscircuiteval package from version 0.0.772 to 0.0.773 in the package.json file. |
| [#3188](https://github.com/tscircuit/runframe/pull/3188) | 🐌 Tiny | tscircuitbot | Updates the tscircuiteval package from version 0.0.770 to 0.0.771 in the package.json file. |
| [#3195](https://github.com/tscircuit/runframe/pull/3195) | 🐌 Tiny | tscircuitbot | Updates the circuit-json-to-kicad package from version 0.0.115 to 0.0.116 in package.json |
| [#3196](https://github.com/tscircuit/runframe/pull/3196) | 🐌 Tiny | tscircuitbot | Automated package update |
| [#3193](https://github.com/tscircuit/runframe/pull/3193) | 🐌 Tiny | tscircuitbot | Automated package update |
| [#3191](https://github.com/tscircuit/runframe/pull/3191) | 🐌 Tiny | tscircuitbot | Automated package update |
| [#3183](https://github.com/tscircuit/runframe/pull/3183) | 🐌 Tiny | tscircuitbot | Updates the circuit-json-to-kicad package version from 0.0.114 to 0.0.115 in package.json |
| [#3181](https://github.com/tscircuit/runframe/pull/3181) | 🐌 Tiny | tscircuitbot | Automated package update |
| [#3186](https://github.com/tscircuit/runframe/pull/3186) | 🐌 Tiny | tscircuitbot | Automated package update |
| [#3189](https://github.com/tscircuit/runframe/pull/3189) | 🐌 Tiny | tscircuitbot | Updates the package version from v0.0.1853 to v0.0.1854 in package.json |
| [#3185](https://github.com/tscircuit/runframe/pull/3185) | 🐌 Tiny | tscircuitbot | Updates the tscircuiteval package from version 0.0.769 to 0.0.770 |
| [#3184](https://github.com/tscircuit/runframe/pull/3184) | 🐌 Tiny | tscircuitbot | Automated package update |

</details>

### [tscircuit/cli](https://github.com/tscircuit/cli)


<details>
<summary>🐌 Tiny Contributions (41)</summary>

| PR # | Impact | Contributor | Description |
|------|--------|-------------|-------------|
| [#2790](https://github.com/tscircuit/cli/pull/2790) | 🐌 Tiny | tscircuitbot | Automated package update |
| [#2789](https://github.com/tscircuit/cli/pull/2789) | 🐌 Tiny | tscircuitbot | Updates the tscircuitrunframe package from version 0.0.1868 to 0.0.1869 |
| [#2788](https://github.com/tscircuit/cli/pull/2788) | 🐌 Tiny | tscircuitbot | Automated package update |
| [#2787](https://github.com/tscircuit/cli/pull/2787) | 🐌 Tiny | tscircuitbot | Updates the tscircuitrunframe package from version 0.0.1867 to 0.0.1868 |
| [#2786](https://github.com/tscircuit/cli/pull/2786) | 🐌 Tiny | tscircuitbot | Automated package update |
| [#2785](https://github.com/tscircuit/cli/pull/2785) | 🐌 Tiny | tscircuitbot | Updates the tscircuitrunframe package from version 0.0.1866 to 0.0.1867 |
| [#2784](https://github.com/tscircuit/cli/pull/2784) | 🐌 Tiny | tscircuitbot | Automated package update |
| [#2783](https://github.com/tscircuit/cli/pull/2783) | 🐌 Tiny | tscircuitbot | Updates the tscircuitrunframe package from version 0.0.1865 to 0.0.1866 |
| [#2782](https://github.com/tscircuit/cli/pull/2782) | 🐌 Tiny | tscircuitbot | Automated package update |
| [#2781](https://github.com/tscircuit/cli/pull/2781) | 🐌 Tiny | tscircuitbot | Updates the tscircuitrunframe package from version 0.0.1864 to 0.0.1865 |
| [#2780](https://github.com/tscircuit/cli/pull/2780) | 🐌 Tiny | tscircuitbot | Automated package update |
| [#2779](https://github.com/tscircuit/cli/pull/2779) | 🐌 Tiny | tscircuitbot | Updates the tscircuitrunframe package from version 0.0.1862 to 0.0.1864 |
| [#2778](https://github.com/tscircuit/cli/pull/2778) | 🐌 Tiny | tscircuitbot | Automated package update |
| [#2777](https://github.com/tscircuit/cli/pull/2777) | 🐌 Tiny | tscircuitbot | Automated README update with latest CLI usage output. |
| [#2776](https://github.com/tscircuit/cli/pull/2776) | 🐌 Tiny | tscircuitbot | Automated package update |
| [#2773](https://github.com/tscircuit/cli/pull/2773) | 🐌 Tiny | tscircuitbot | Automated package update |
| [#2772](https://github.com/tscircuit/cli/pull/2772) | 🐌 Tiny | tscircuitbot | Updates the tscircuitrunframe package from version 0.0.1861 to 0.0.1862 |
| [#2771](https://github.com/tscircuit/cli/pull/2771) | 🐌 Tiny | tscircuitbot | Automated package update |
| [#2770](https://github.com/tscircuit/cli/pull/2770) | 🐌 Tiny | tscircuitbot | Updates the tscircuitrunframe package from version 0.0.1860 to 0.0.1861 |
| [#2769](https://github.com/tscircuit/cli/pull/2769) | 🐌 Tiny | tscircuitbot | Automated package update |
| [#2768](https://github.com/tscircuit/cli/pull/2768) | 🐌 Tiny | tscircuitbot | Updates the tscircuitrunframe package to version 0.0.1860 |
| [#2767](https://github.com/tscircuit/cli/pull/2767) | 🐌 Tiny | tscircuitbot | Automated package update |
| [#2766](https://github.com/tscircuit/cli/pull/2766) | 🐌 Tiny | tscircuitbot | Updates the tscircuitrunframe package to version 0.0.1859 in the package.json file |
| [#2765](https://github.com/tscircuit/cli/pull/2765) | 🐌 Tiny | tscircuitbot | Automated package update |
| [#2764](https://github.com/tscircuit/cli/pull/2764) | 🐌 Tiny | tscircuitbot | Updates the tscircuitrunframe package to version 0.0.1858 in the package.json file. |
| [#2762](https://github.com/tscircuit/cli/pull/2762) | 🐌 Tiny | tscircuitbot | Updates the tscircuitrunframe package from version 0.0.1855 to 0.0.1857 |
| [#2760](https://github.com/tscircuit/cli/pull/2760) | 🐌 Tiny | tscircuitbot | Automated package update |
| [#2759](https://github.com/tscircuit/cli/pull/2759) | 🐌 Tiny | tscircuitbot | Automated package update |
| [#2748](https://github.com/tscircuit/cli/pull/2748) | 🐌 Tiny | tscircuitbot | Updates the tscircuitrunframe package from version 0.0.1849 to 0.0.1850 |
| [#2763](https://github.com/tscircuit/cli/pull/2763) | 🐌 Tiny | tscircuitbot | Automated package update |
| [#2761](https://github.com/tscircuit/cli/pull/2761) | 🐌 Tiny | tscircuitbot | Automated package update |
| [#2758](https://github.com/tscircuit/cli/pull/2758) | 🐌 Tiny | tscircuitbot | Updates the tscircuitrunframe package to version 0.0.1854 |
| [#2756](https://github.com/tscircuit/cli/pull/2756) | 🐌 Tiny | tscircuitbot | Updates the tscircuitrunframe package to version 0.0.1853 |
| [#2755](https://github.com/tscircuit/cli/pull/2755) | 🐌 Tiny | tscircuitbot | Automated package update |
| [#2754](https://github.com/tscircuit/cli/pull/2754) | 🐌 Tiny | tscircuitbot | Updates the tscircuitrunframe package from version 0.0.1851 to 0.0.1852 |
| [#2753](https://github.com/tscircuit/cli/pull/2753) | 🐌 Tiny | tscircuitbot | Automated package update |
| [#2752](https://github.com/tscircuit/cli/pull/2752) | 🐌 Tiny | tscircuitbot | Updates the tscircuitrunframe package from version 0.0.1850 to 0.0.1851 |
| [#2750](https://github.com/tscircuit/cli/pull/2750) | 🐌 Tiny | tscircuitbot | Automated package update |
| [#2757](https://github.com/tscircuit/cli/pull/2757) | 🐌 Tiny | tscircuitbot | Automated package update |
| [#2749](https://github.com/tscircuit/cli/pull/2749) | 🐌 Tiny | techmannih | Updates the version of the circuit-json-to-kicad dependency from 0.0.109 to 0.0.114 in package.json |
| [#2774](https://github.com/tscircuit/cli/pull/2774) | 🐌 Tiny | rushabhcodes | Updates the versions of the dependencies circuit-json-to-gerber and poppygl in the package.json file to their latest versions, ensuring compatibility with recent features and bug fixes. |

</details>

### [tscircuit/svg.tscircuit.com](https://github.com/tscircuit/svg.tscircuit.com)


<details>
<summary>🐌 Tiny Contributions (2)</summary>

| PR # | Impact | Contributor | Description |
|------|--------|-------------|-------------|
| [#1355](https://github.com/tscircuit/svg.tscircuit.com/pull/1355) | 🐌 Tiny | tscircuitbot | Updates the tscircuit package version from 0.0.1661 to 0.0.1662 in package.json |
| [#1354](https://github.com/tscircuit/svg.tscircuit.com/pull/1354) | 🐌 Tiny | tscircuitbot | Updates the tscircuit package version from 0.0.1660 to 0.0.1661 in package.json |

</details>

### [tscircuit/tscircuit-autorouter](https://github.com/tscircuit/tscircuit-autorouter)

| PR # | Impact | Rating | Contributor | Description |
|------|--------|--------|-------------|-------------|
| [#950](https://github.com/tscircuit/tscircuit-autorouter/pull/950) | 🐳 Major | ⭐⭐⭐ | ShiboSoftwareDev | Normalizes via dimensions across autorouters by using a shared helper function, ensuring all autorouting pipelines utilize the specified pad and hole diameters, and updates circuit-json export and SVG rendering accordingly. |
| [#974](https://github.com/tscircuit/tscircuit-autorouter/pull/974) | 🐳 Major | ⭐⭐⭐ | AnasSarkiz | Enhances benchmark feedback by incorporating early results, comparing with main branch deltas, and implementing timeouts for profile solvers. |
| [#949](https://github.com/tscircuit/tscircuit-autorouter/pull/949) | 🐳 Major | ⭐⭐⭐ | AnasSarkiz | Enhances margin-aware violation detection in the autorouting process to improve design rule checking accuracy. |
| [#953](https://github.com/tscircuit/tscircuit-autorouter/pull/953) | 🐳 Major | ⭐⭐⭐ | 0hmX | Adds a focused reproduction for a high-density solver issue related to reentry in nodeWithPortPoints input, including new test cases and fixtures. |
| [#972](https://github.com/tscircuit/tscircuit-autorouter/pull/972) | 🐙 Minor | ⭐⭐ | AnasSarkiz | Adds --profile-solvers support to benchmark CI, enabling profile comparison tables for PR and main in benchmark results. |

<details>
<summary>🐌 Tiny Contributions (7)</summary>

| PR # | Impact | Contributor | Description |
|------|--------|-------------|-------------|
| [#975](https://github.com/tscircuit/tscircuit-autorouter/pull/975) | 🐌 Tiny | tscircuitbot | Automated package update |
| [#971](https://github.com/tscircuit/tscircuit-autorouter/pull/971) | 🐌 Tiny | tscircuitbot | Automated package update |
| [#966](https://github.com/tscircuit/tscircuit-autorouter/pull/966) | 🐌 Tiny | tscircuitbot | Automated package update |
| [#962](https://github.com/tscircuit/tscircuit-autorouter/pull/962) | 🐌 Tiny | tscircuitbot | Automated package update |
| [#958](https://github.com/tscircuit/tscircuit-autorouter/pull/958) | 🐌 Tiny | tscircuitbot | Automated package update |
| [#970](https://github.com/tscircuit/tscircuit-autorouter/pull/970) | 🐌 Tiny | imrishabh18 | This pull request adds a new bug report fixture for bug report ID 51, including a JSON representation of the bug report and a corresponding React component for testing. |
| [#956](https://github.com/tscircuit/tscircuit-autorouter/pull/956) | 🐌 Tiny | 0hmX | Removes the SVG snapshot test for bugreport49 from the test suite. |

</details>

### [tscircuit/test-github-automerge](https://github.com/tscircuit/test-github-automerge)


<details>
<summary>🐌 Tiny Contributions (1)</summary>

| PR # | Impact | Contributor | Description |
|------|--------|-------------|-------------|
| [#43](https://github.com/tscircuit/test-github-automerge/pull/43) | 🐌 Tiny | tscircuitbot | Updates the tscircuitcircuit-json-util package from version 0.0.93 to 0.0.94 in the development dependencies. |

</details>

### [tscircuit/circuit-json-to-kicad](https://github.com/tscircuit/circuit-json-to-kicad)

| PR # | Impact | Rating | Contributor | Description |
|------|--------|--------|-------------|-------------|
| [#232](https://github.com/tscircuit/circuit-json-to-kicad/pull/232) | 🐙 Minor | ⭐⭐ | techmannih | Enables the inclusion of supplier part numbers (specifically from jlcpcb) as properties in the generated KiCad PCB footprints. |
| [#233](https://github.com/tscircuit/circuit-json-to-kicad/pull/233) | 🐙 Minor | ⭐⭐ | techmannih | Adds rotation support for circular and rotated pill holes with rectangular pads in PCB design, enhancing the flexibility of hole placement. |
| [#235](https://github.com/tscircuit/circuit-json-to-kicad/pull/235) | 🐙 Minor | ⭐⭐ | mohan-bee | Fixes KiCad export for pcb_silkscreen_path objects that belong to a component, ensuring they are exported as footprint-local primitives instead of board-level graphics. |
| [#229](https://github.com/tscircuit/circuit-json-to-kicad/pull/229) | 🐙 Minor | ⭐⭐ | Sang-it | Fixes KiCad pad labeling to preserve source pin identity instead of array order, ensuring correct pad numbering for custom footprints. |

<details>
<summary>🐌 Tiny Contributions (5)</summary>

| PR # | Impact | Contributor | Description |
|------|--------|-------------|-------------|
| [#237](https://github.com/tscircuit/circuit-json-to-kicad/pull/237) | 🐌 Tiny | tscircuitbot | Automated package update |
| [#239](https://github.com/tscircuit/circuit-json-to-kicad/pull/239) | 🐌 Tiny | tscircuitbot | Automated package update |
| [#231](https://github.com/tscircuit/circuit-json-to-kicad/pull/231) | 🐌 Tiny | tscircuitbot | Automated package update |
| [#234](https://github.com/tscircuit/circuit-json-to-kicad/pull/234) | 🐌 Tiny | tscircuitbot | Automated package update |
| [#236](https://github.com/tscircuit/circuit-json-to-kicad/pull/236) | 🐌 Tiny | techmannih | Adds a test to ensure that 0402 footprints maintain pad rotation when components are rotated 45 degrees in the circuit. |

</details>

### [tscircuit/rectdiff](https://github.com/tscircuit/rectdiff)


<details>
<summary>🐌 Tiny Contributions (3)</summary>

| PR # | Impact | Contributor | Description |
|------|--------|-------------|-------------|
| [#97](https://github.com/tscircuit/rectdiff/pull/97) | 🐌 Tiny | tscircuitbot | Automated package update |
| [#96](https://github.com/tscircuit/rectdiff/pull/96) | 🐌 Tiny | 0hmX | Adds a test for generating a multi-layer node summary from SRJ files, ensuring correct volume calculations and obstacle handling. |
| [#94](https://github.com/tscircuit/rectdiff/pull/94) | 🐌 Tiny | 0hmX | This pull request introduces new fixtures for the Arduino Uno plane-layer rectdiff functionality. It includes new page components and JSON assets that define the routing and layout for the Arduino Uno, enhancing the existing rectdiff capabilities. |

</details>

### [tscircuit/high-density-a01](https://github.com/tscircuit/high-density-a01)

| PR # | Impact | Rating | Contributor | Description |
|------|--------|--------|-------------|-------------|
| [#74](https://github.com/tscircuit/high-density-a01/pull/74) | 🐳 Major | ⭐⭐⭐ | seveibar | Adds a new solver (A09) to the high-density routing system, enhancing routing capabilities with new parameters and functionality. |

<details>
<summary>🐌 Tiny Contributions (1)</summary>

| PR # | Impact | Contributor | Description |
|------|--------|-------------|-------------|
| [#75](https://github.com/tscircuit/high-density-a01/pull/75) | 🐌 Tiny | tscircuitbot | Automated package update |

</details>

### [tscircuit/circuit-json-util](https://github.com/tscircuit/circuit-json-util)

| PR # | Impact | Rating | Contributor | Description |
|------|--------|--------|-------------|-------------|
| [#94](https://github.com/tscircuit/circuit-json-util/pull/94) | 🐙 Minor | ⭐⭐ | ShiboSoftwareDev | Updates transformPCBElement to maintain consistent pcb_component geometric metadata by transforming insertion_direction and moving cable_insertion_center with the applied matrix, while ensuring correct handling of quarter-turns for negative rotations. |

### [tscircuit/circuit-to-svg](https://github.com/tscircuit/circuit-to-svg)

| PR # | Impact | Rating | Contributor | Description |
|------|--------|--------|-------------|-------------|
| [#548](https://github.com/tscircuit/circuit-to-svg/pull/548) | 🐙 Minor | ⭐⭐ | ShiboSoftwareDev | Switch simulation graphs to a dedicated default palette with conventional plot colors so early traces use familiar blueredgreen-style ordering. |

### [tscircuit/checks](https://github.com/tscircuit/checks)

| PR # | Impact | Rating | Contributor | Description |
|------|--------|--------|-------------|-------------|
| [#141](https://github.com/tscircuit/checks/pull/141) | 🐙 Minor | ⭐⭐ | ShiboSoftwareDev | Update connector accessibility checks to use pcb_component.insertion_direction when available, with fallback to cable_insertion_center for older data. This maps side-entry directions to facing axes, skips from_above, and no longer requires cable_insertion_center to run the check. |
| [#136](https://github.com/tscircuit/checks/pull/136) | 🐙 Minor | ⭐⭐ | imrishabh18 | Aligns local DRC default values with the published JLCPCB minimum manufacturing tolerances, replacing hardcoded values with dynamic values from the jlcMinTolerances package. |

<details>
<summary>🐌 Tiny Contributions (3)</summary>

| PR # | Impact | Contributor | Description |
|------|--------|-------------|-------------|
| [#139](https://github.com/tscircuit/checks/pull/139) | 🐌 Tiny | imrishabh18 | Sets default clearance values for PCB components based on the PCB board specifications and JLCPCB manufacturing tolerances. |
| [#140](https://github.com/tscircuit/checks/pull/140) | 🐌 Tiny | imrishabh18 | Fixes the wording of error messages related to PCB trace overlaps and gaps to provide clearer information to users. |
| [#138](https://github.com/tscircuit/checks/pull/138) | 🐌 Tiny | imrishabh18 | Changes the build process to bundle the tscircuitjlcpcb-manufacturing-specs package and modifies the build script accordingly. |

</details>

### [tscircuit/props](https://github.com/tscircuit/props)


<details>
<summary>🐌 Tiny Contributions (3)</summary>

| PR # | Impact | Contributor | Description |
|------|--------|-------------|-------------|
| [#638](https://github.com/tscircuit/props/pull/638) | 🐌 Tiny | ShiboSoftwareDev | Removes the directional options x, x-, y, and y- from the footprint insertion direction type definition, streamlining the available options for users. |
| [#640](https://github.com/tscircuit/props/pull/640) | 🐌 Tiny | techmannih | Adds a new property rectBorderRadius to the PillWithRectPadPlatedHoleProps interface, allowing for customizable border radius on rectangular plated holes. |
| [#641](https://github.com/tscircuit/props/pull/641) | 🐌 Tiny | imrishabh18 | Renames DRC-related props on SubcircuitGroupProps to consistent camelCase names for runtime validation and documentation. |

</details>

### [tscircuit/kicad-to-circuit-json](https://github.com/tscircuit/kicad-to-circuit-json)

| PR # | Impact | Rating | Contributor | Description |
|------|--------|--------|-------------|-------------|
| [#62](https://github.com/tscircuit/kicad-to-circuit-json/pull/62) | 🐙 Minor | ⭐⭐ | techmannih | Adds support for a new plated hole shape, specifically the pill_hole_with_rect_pad, enhancing the PCB design capabilities. |

### [tscircuit/jlcpcb-manufacturing-specs](https://github.com/tscircuit/jlcpcb-manufacturing-specs)


<details>
<summary>🐌 Tiny Contributions (1)</summary>

| PR # | Impact | Contributor | Description |
|------|--------|-------------|-------------|
| [#4](https://github.com/tscircuit/jlcpcb-manufacturing-specs/pull/4) | 🐌 Tiny | imrishabh18 | Renames JLCPCB tolerance keys for clarity, adjusts default tolerance values for accuracy, and updates the circuit-json dependency to ensure compatibility with the latest board schema. |

</details>

### [tscircuit/easyeda-converter](https://github.com/tscircuit/easyeda-converter)

| PR # | Impact | Rating | Contributor | Description |
|------|--------|--------|-------------|-------------|
| [#384](https://github.com/tscircuit/easyeda-converter/pull/384) | 🐳 Major | ⭐⭐⭐ | Abse2001 | This pull request refactors the CAD offset logic to utilize model bounds and extract the SVG origin. It introduces a new method for calculating the CAD model offset based on the bounds of the model, improving the accuracy of the placement of CAD models in the circuit design. The changes include updates to the conversion functions and adjustments to the handling of CAD model properties, ensuring that the models origin is correctly calculated and applied during the conversion process. |

### [tscircuit/3d-viewer](https://github.com/tscircuit/3d-viewer)

| PR # | Impact | Rating | Contributor | Description |
|------|--------|--------|-------------|-------------|
| [#765](https://github.com/tscircuit/3d-viewer/pull/765) | 🐳 Major | ⭐⭐⭐ | Abse2001 | https:3d-viewer-git-fork-abse2001-main-tscircuit.vercel.app?pathstorykeypad--default |

### [tscircuit/high-density-repair03](https://github.com/tscircuit/high-density-repair03)

| PR # | Impact | Rating | Contributor | Description |
|------|--------|--------|-------------|-------------|
| [#1](https://github.com/tscircuit/high-density-repair03/pull/1) | 🐳 Major | ⭐⭐⭐ | Abse2001 | This pull request introduces the GlobalDrcForceImproveSolver, a new solver for improving high-density PCB routes against DRC-style errors. It includes a comprehensive implementation of the solver logic, types, and usage documentation. |

### [tscircuit/jscad-electronics](https://github.com/tscircuit/jscad-electronics)


<details>
<summary>🐌 Tiny Contributions (1)</summary>

| PR # | Impact | Contributor | Description |
|------|--------|-------------|-------------|
| [#287](https://github.com/tscircuit/jscad-electronics/pull/287) | 🐌 Tiny | Abse2001 | Centers multi-row PinRow footprints around the component origin to ensure proper alignment in the layout. |

</details>

### [tscircuit/circuit-json-to-gltf](https://github.com/tscircuit/circuit-json-to-gltf)


<details>
<summary>🐌 Tiny Contributions (1)</summary>

| PR # | Impact | Contributor | Description |
|------|--------|-------------|-------------|
| [#157](https://github.com/tscircuit/circuit-json-to-gltf/pull/157) | 🐌 Tiny | Abse2001 | Adds a test for a double row pinheader and updates the jscad-electronics dependency to version 0.0.129. |

</details>

### [tscircuit/circuit-json-to-gerber](https://github.com/tscircuit/circuit-json-to-gerber)


<details>
<summary>🐌 Tiny Contributions (1)</summary>

| PR # | Impact | Contributor | Description |
|------|--------|-------------|-------------|
| [#77](https://github.com/tscircuit/circuit-json-to-gerber/pull/77) | 🐌 Tiny | rushabhcodes | Updates the version of the tscircuitalphabet dependency in package.json to ensure compatibility with the latest features and bug fixes. |

</details>

### [tscircuit/tscircuit.com-landing](https://github.com/tscircuit/tscircuit.com-landing)


<details>
<summary>🐌 Tiny Contributions (3)</summary>

| PR # | Impact | Contributor | Description |
|------|--------|-------------|-------------|
| [#9](https://github.com/tscircuit/tscircuit.com-landing/pull/9) | 🐌 Tiny | rushabhcodes | Updates the landing page copy for clarity, revises statistics, and optimizes gallery image loading by switching from remote URLs to local assets. |
| [#7](https://github.com/tscircuit/tscircuit.com-landing/pull/7) | 🐌 Tiny | rushabhcodes | Updates the landing page with improved UI elements, navigation simplification, animated GitHub star count, and replaces the autorouting demo video. |
| [#8](https://github.com/tscircuit/tscircuit.com-landing/pull/8) | 🐌 Tiny | rushabhcodes | Enhances the small-screen experience on the landing page by tightening the feature card layout, simplifying repeated card styles, and redesigning the footer for mobile to read as a compact sitemap instead of a squeezed desktop stack. |

</details>

### [tscircuit/docs](https://github.com/tscircuit/docs)


<details>
<summary>🐌 Tiny Contributions (1)</summary>

| PR # | Impact | Contributor | Description |
|------|--------|-------------|-------------|
| [#535](https://github.com/tscircuit/docs/pull/535) | 🐌 Tiny | mohan-bee | Adds new export formats for assembly SVG and STEP 3D model to the documentation. |

</details>

### [tscircuit/high-density-repair01](https://github.com/tscircuit/high-density-repair01)

| PR # | Impact | Rating | Contributor | Description |
|------|--------|--------|-------------|-------------|
| [#6](https://github.com/tscircuit/high-density-repair01/pull/6) | 🐳 Major | ⭐⭐⭐ | AnasSarkiz | Replaces the legacy benchmark flow with a unified runner that delivers automated reports, powerful CLI tooling, and scalable benchmarking for current and future datasets. |
| [#5](https://github.com/tscircuit/high-density-repair01/pull/5) | 🐳 Major | ⭐⭐⭐ | AnasSarkiz | Adds a projection-based post-processing pass that separates overlapping vias and traces inside dense nodes while keeping routes within bounds. Improves routing clarity, spacing, and overall collision resolution. |

### [tscircuit/schematic-trace-solver](https://github.com/tscircuit/schematic-trace-solver)


<details>
<summary>🐌 Tiny Contributions (2)</summary>

| PR # | Impact | Contributor | Description |
|------|--------|-------------|-------------|
| [#208](https://github.com/tscircuit/schematic-trace-solver/pull/208) | 🐌 Tiny | Sang-it | Adds debug labels to the NetLabelPlacementSolver for better visualization of net IDs and anchor points during the placement process. |
| [#205](https://github.com/tscircuit/schematic-trace-solver/pull/205) | 🐌 Tiny | Sang-it | Adds a new example page and corresponding tests for the schematic trace solver. |

</details>

## Changes by Contributor

### [tscircuitbot](https://github.com/tscircuitbot)


<details>
<summary>🐌 Tiny Contributions (169)</summary>

| PR # | Impact | Description |
|------|--------|-------------|
| [#2999](https://github.com/tscircuit/tscircuit/pull/2999) | 🐌 Tiny | Updates the package version from 0.0.1666 to 0.0.1667 in package.json |
| [#2998](https://github.com/tscircuit/tscircuit/pull/2998) | 🐌 Tiny | Automated package update |
| [#2997](https://github.com/tscircuit/tscircuit/pull/2997) | 🐌 Tiny | Automated package update |
| [#2996](https://github.com/tscircuit/tscircuit/pull/2996) | 🐌 Tiny | Automated package update |
| [#2995](https://github.com/tscircuit/tscircuit/pull/2995) | 🐌 Tiny | Automated package update |
| [#2994](https://github.com/tscircuit/tscircuit/pull/2994) | 🐌 Tiny | Automated package update |
| [#2993](https://github.com/tscircuit/tscircuit/pull/2993) | 🐌 Tiny | Automated package update |
| [#2992](https://github.com/tscircuit/tscircuit/pull/2992) | 🐌 Tiny | Updates the version of several dependencies in the package.json file, including tscircuitcli, tscircuitcore, tscircuiteval, and circuit-json-to-gltf. |
| [#2991](https://github.com/tscircuit/tscircuit/pull/2991) | 🐌 Tiny | Updates the package version from 0.0.1662 to 0.0.1663 in package.json |
| [#2990](https://github.com/tscircuit/tscircuit/pull/2990) | 🐌 Tiny | Automated package update |
| [#2983](https://github.com/tscircuit/tscircuit/pull/2983) | 🐌 Tiny | Automated package update |
| [#2975](https://github.com/tscircuit/tscircuit/pull/2975) | 🐌 Tiny | Automated package update |
| [#563](https://github.com/tscircuit/circuit-json/pull/563) | 🐌 Tiny | Automated package update |
| [#2180](https://github.com/tscircuit/core/pull/2180) | 🐌 Tiny | Updates the tscircuitchecks package from version 0.0.123 to 0.0.124 |
| [#2179](https://github.com/tscircuit/core/pull/2179) | 🐌 Tiny | Updates the tscircuitchecks package from version 0.0.122 to 0.0.123 |
| [#2177](https://github.com/tscircuit/core/pull/2177) | 🐌 Tiny | Updates the tscircuitchecks package from version 0.0.121 to 0.0.122 |
| [#2172](https://github.com/tscircuit/core/pull/2172) | 🐌 Tiny | Updates the tscircuitchecks package from version 0.0.120 to 0.0.121 |
| [#2167](https://github.com/tscircuit/core/pull/2167) | 🐌 Tiny | Updates the tscircuitchecks package from version 0.0.119 to 0.0.120 in the package.json file. |
| [#3248](https://github.com/tscircuit/tscircuit.com/pull/3248) | 🐌 Tiny | Updates the tscircuitrunframe package from version 0.0.1868 to 0.0.1869 |
| [#3247](https://github.com/tscircuit/tscircuit.com/pull/3247) | 🐌 Tiny | Updates the tscircuiteval package to version 0.0.783 |
| [#3246](https://github.com/tscircuit/tscircuit.com/pull/3246) | 🐌 Tiny | Updates the tscircuitrunframe package from version 0.0.1867 to 0.0.1868 |
| [#3245](https://github.com/tscircuit/tscircuit.com/pull/3245) | 🐌 Tiny | Updates the tscircuiteval package from version 0.0.781 to 0.0.782 |
| [#3244](https://github.com/tscircuit/tscircuit.com/pull/3244) | 🐌 Tiny | Updates the tscircuiteval package from version 0.0.780 to 0.0.781 |
| [#3243](https://github.com/tscircuit/tscircuit.com/pull/3243) | 🐌 Tiny | Updates the tscircuitrunframe package from version 0.0.1866 to 0.0.1867 |
| [#3242](https://github.com/tscircuit/tscircuit.com/pull/3242) | 🐌 Tiny | Updates the tscircuiteval package to version 0.0.780 |
| [#3241](https://github.com/tscircuit/tscircuit.com/pull/3241) | 🐌 Tiny | Automated package update |
| [#3240](https://github.com/tscircuit/tscircuit.com/pull/3240) | 🐌 Tiny | Updates the tscircuiteval package from version 0.0.778 to 0.0.779 |
| [#3239](https://github.com/tscircuit/tscircuit.com/pull/3239) | 🐌 Tiny | Updates the tscircuitrunframe package from version 0.0.1864 to 0.0.1865 |
| [#3238](https://github.com/tscircuit/tscircuit.com/pull/3238) | 🐌 Tiny | Updates the tscircuiteval package version from 0.0.777 to 0.0.778 |
| [#3237](https://github.com/tscircuit/tscircuit.com/pull/3237) | 🐌 Tiny | Updates the tscircuitrunframe package from version 0.0.1863 to 0.0.1864 |
| [#3236](https://github.com/tscircuit/tscircuit.com/pull/3236) | 🐌 Tiny | Updates the tscircuiteval package version from 0.0.776 to 0.0.777 in package.json |
| [#3229](https://github.com/tscircuit/tscircuit.com/pull/3229) | 🐌 Tiny | Updates the tscircuitrunframe package to version 0.0.1859 |
| [#3230](https://github.com/tscircuit/tscircuit.com/pull/3230) | 🐌 Tiny | Updates the tscircuiteval package to version 0.0.776 in the package.json file. |
| [#3227](https://github.com/tscircuit/tscircuit.com/pull/3227) | 🐌 Tiny | Automated package update |
| [#3234](https://github.com/tscircuit/tscircuit.com/pull/3234) | 🐌 Tiny | Updates the tscircuitrunframe package from version 0.0.1861 to 0.0.1862 |
| [#3233](https://github.com/tscircuit/tscircuit.com/pull/3233) | 🐌 Tiny | Updates the tscircuitrunframe package from version 0.0.1860 to 0.0.1861 |
| [#3226](https://github.com/tscircuit/tscircuit.com/pull/3226) | 🐌 Tiny | Updates the tscircuiteval package to version 0.0.774 |
| [#3235](https://github.com/tscircuit/tscircuit.com/pull/3235) | 🐌 Tiny | Updates the tscircuitrunframe package from version 0.0.1862 to 0.0.1863 |
| [#3231](https://github.com/tscircuit/tscircuit.com/pull/3231) | 🐌 Tiny | Automated package update |
| [#3228](https://github.com/tscircuit/tscircuit.com/pull/3228) | 🐌 Tiny | Updates the tscircuiteval package from version 0.0.774 to 0.0.775 |
| [#3212](https://github.com/tscircuit/tscircuit.com/pull/3212) | 🐌 Tiny | Automated package update |
| [#3215](https://github.com/tscircuit/tscircuit.com/pull/3215) | 🐌 Tiny | Updates the tscircuitrunframe package from version 0.0.1852 to 0.0.1853 |
| [#3222](https://github.com/tscircuit/tscircuit.com/pull/3222) | 🐌 Tiny | Updates the tscircuitrunframe package from version 0.0.1854 to 0.0.1855 |
| [#3219](https://github.com/tscircuit/tscircuit.com/pull/3219) | 🐌 Tiny | Automated package update |
| [#3221](https://github.com/tscircuit/tscircuit.com/pull/3221) | 🐌 Tiny | Updates the tscircuiteval package from version 0.0.772 to 0.0.773 |
| [#3223](https://github.com/tscircuit/tscircuit.com/pull/3223) | 🐌 Tiny | Updates the tscircuitrunframe package from version 0.0.1855 to 0.0.1857 |
| [#3217](https://github.com/tscircuit/tscircuit.com/pull/3217) | 🐌 Tiny | Automated package update |
| [#3213](https://github.com/tscircuit/tscircuit.com/pull/3213) | 🐌 Tiny | Updates the tscircuitrunframe package to version 0.0.1852 |
| [#3214](https://github.com/tscircuit/tscircuit.com/pull/3214) | 🐌 Tiny | Automated package update |
| [#3218](https://github.com/tscircuit/tscircuit.com/pull/3218) | 🐌 Tiny | Updates the tscircuitrunframe package from version 0.0.1853 to 0.0.1854 |
| [#2490](https://github.com/tscircuit/eval/pull/2490) | 🐌 Tiny | Automated package update |
| [#2489](https://github.com/tscircuit/eval/pull/2489) | 🐌 Tiny | Automated package update |
| [#2487](https://github.com/tscircuit/eval/pull/2487) | 🐌 Tiny | Automated package update |
| [#2486](https://github.com/tscircuit/eval/pull/2486) | 🐌 Tiny | Updates the versions of several dependencies in the package.json file. |
| [#2484](https://github.com/tscircuit/eval/pull/2484) | 🐌 Tiny | Automated package update |
| [#2483](https://github.com/tscircuit/eval/pull/2483) | 🐌 Tiny | Updates the version of several dependencies in the package.json file. |
| [#2481](https://github.com/tscircuit/eval/pull/2481) | 🐌 Tiny | Automated package update |
| [#2480](https://github.com/tscircuit/eval/pull/2480) | 🐌 Tiny | Updates package versions in package.json to their latest compatible versions. |
| [#2478](https://github.com/tscircuit/eval/pull/2478) | 🐌 Tiny | Automated package update |
| [#2477](https://github.com/tscircuit/eval/pull/2477) | 🐌 Tiny | Updates package dependencies to their latest versions as part of routine maintenance. |
| [#2475](https://github.com/tscircuit/eval/pull/2475) | 🐌 Tiny | Automated package update |
| [#2474](https://github.com/tscircuit/eval/pull/2474) | 🐌 Tiny | Automated package update |
| [#2472](https://github.com/tscircuit/eval/pull/2472) | 🐌 Tiny | Automated package update |
| [#2471](https://github.com/tscircuit/eval/pull/2471) | 🐌 Tiny | Updates the version of the tscircuitcore package from 0.0.1185 to 0.0.1186 in package.json |
| [#2469](https://github.com/tscircuit/eval/pull/2469) | 🐌 Tiny | Automated package update to version 0.0.776 |
| [#2466](https://github.com/tscircuit/eval/pull/2466) | 🐌 Tiny | Automated package update to version 0.0.775 |
| [#2465](https://github.com/tscircuit/eval/pull/2465) | 🐌 Tiny | Automated package update |
| [#2461](https://github.com/tscircuit/eval/pull/2461) | 🐌 Tiny | Automated package update |
| [#2460](https://github.com/tscircuit/eval/pull/2460) | 🐌 Tiny | Automated package update |
| [#2468](https://github.com/tscircuit/eval/pull/2468) | 🐌 Tiny | Updates the version of the tscircuitcore and tscircuitprops packages in package.json |
| [#2458](https://github.com/tscircuit/eval/pull/2458) | 🐌 Tiny | Automated package update |
| [#2457](https://github.com/tscircuit/eval/pull/2457) | 🐌 Tiny | Automated package update |
| [#2456](https://github.com/tscircuit/eval/pull/2456) | 🐌 Tiny | Automated package update |
| [#2455](https://github.com/tscircuit/eval/pull/2455) | 🐌 Tiny | Updates package dependencies to their latest versions as part of routine maintenance. |
| [#2453](https://github.com/tscircuit/eval/pull/2453) | 🐌 Tiny | Automated package update |
| [#2452](https://github.com/tscircuit/eval/pull/2452) | 🐌 Tiny | Automated package update |
| [#2450](https://github.com/tscircuit/eval/pull/2450) | 🐌 Tiny | Automated package update |
| [#2449](https://github.com/tscircuit/eval/pull/2449) | 🐌 Tiny | Automated package update |
| [#3222](https://github.com/tscircuit/runframe/pull/3222) | 🐌 Tiny | Automated package update |
| [#3221](https://github.com/tscircuit/runframe/pull/3221) | 🐌 Tiny | Updates the tscircuiteval package to version 0.0.783 in the package.json file. |
| [#3220](https://github.com/tscircuit/runframe/pull/3220) | 🐌 Tiny | Automated package update |
| [#3219](https://github.com/tscircuit/runframe/pull/3219) | 🐌 Tiny | Updates the tscircuiteval package version from 0.0.780 to 0.0.782 in package.json |
| [#3218](https://github.com/tscircuit/runframe/pull/3218) | 🐌 Tiny | Automated package update |
| [#3217](https://github.com/tscircuit/runframe/pull/3217) | 🐌 Tiny | Updates the tscircuiteval package from version 0.0.779 to 0.0.780 |
| [#3216](https://github.com/tscircuit/runframe/pull/3216) | 🐌 Tiny | Automated package update |
| [#3215](https://github.com/tscircuit/runframe/pull/3215) | 🐌 Tiny | Updates the tscircuiteval package from version 0.0.778 to 0.0.779 in the package.json file. |
| [#3214](https://github.com/tscircuit/runframe/pull/3214) | 🐌 Tiny | Automated package update |
| [#3213](https://github.com/tscircuit/runframe/pull/3213) | 🐌 Tiny | Updates the tscircuiteval package to version 0.0.778 in the package.json file. |
| [#3212](https://github.com/tscircuit/runframe/pull/3212) | 🐌 Tiny | Automated package update |
| [#3211](https://github.com/tscircuit/runframe/pull/3211) | 🐌 Tiny | Updates the tscircuiteval package from version 0.0.776 to 0.0.777 in the package.json file. |
| [#3200](https://github.com/tscircuit/runframe/pull/3200) | 🐌 Tiny | Updates the tscircuiteval package from version 0.0.774 to 0.0.775 in the package.json file. |
| [#3199](https://github.com/tscircuit/runframe/pull/3199) | 🐌 Tiny | Automated package update |
| [#3209](https://github.com/tscircuit/runframe/pull/3209) | 🐌 Tiny | Updates the circuit-json-to-gerber package from version 0.0.48 to 0.0.49 |
| [#3198](https://github.com/tscircuit/runframe/pull/3198) | 🐌 Tiny | Updates the tscircuiteval package to version 0.0.774 in the package.json file. |
| [#3210](https://github.com/tscircuit/runframe/pull/3210) | 🐌 Tiny | Automated package update |
| [#3208](https://github.com/tscircuit/runframe/pull/3208) | 🐌 Tiny | Updates the circuit-json-to-kicad package version from 0.0.117 to 0.0.118 in package.json |
| [#3201](https://github.com/tscircuit/runframe/pull/3201) | 🐌 Tiny | Automated package update |
| [#3202](https://github.com/tscircuit/runframe/pull/3202) | 🐌 Tiny | Updates the tscircuiteval package from version 0.0.775 to 0.0.776 |
| [#3206](https://github.com/tscircuit/runframe/pull/3206) | 🐌 Tiny | Automated package update |
| [#3203](https://github.com/tscircuit/runframe/pull/3203) | 🐌 Tiny | Automated package update |
| [#3207](https://github.com/tscircuit/runframe/pull/3207) | 🐌 Tiny | Automated package update |
| [#3205](https://github.com/tscircuit/runframe/pull/3205) | 🐌 Tiny | Updates the circuit-json-to-kicad package from version 0.0.116 to 0.0.117 |
| [#3180](https://github.com/tscircuit/runframe/pull/3180) | 🐌 Tiny | Updates the tscircuit3d-viewer package to version 0.0.556 in package.json |
| [#3190](https://github.com/tscircuit/runframe/pull/3190) | 🐌 Tiny | Updates the tscircuiteval package from version 0.0.771 to 0.0.772 in the package.json file. |
| [#3192](https://github.com/tscircuit/runframe/pull/3192) | 🐌 Tiny | Updates the tscircuiteval package from version 0.0.772 to 0.0.773 in the package.json file. |
| [#3188](https://github.com/tscircuit/runframe/pull/3188) | 🐌 Tiny | Updates the tscircuiteval package from version 0.0.770 to 0.0.771 in the package.json file. |
| [#3195](https://github.com/tscircuit/runframe/pull/3195) | 🐌 Tiny | Updates the circuit-json-to-kicad package from version 0.0.115 to 0.0.116 in package.json |
| [#3196](https://github.com/tscircuit/runframe/pull/3196) | 🐌 Tiny | Automated package update |
| [#3193](https://github.com/tscircuit/runframe/pull/3193) | 🐌 Tiny | Automated package update |
| [#3191](https://github.com/tscircuit/runframe/pull/3191) | 🐌 Tiny | Automated package update |
| [#3183](https://github.com/tscircuit/runframe/pull/3183) | 🐌 Tiny | Updates the circuit-json-to-kicad package version from 0.0.114 to 0.0.115 in package.json |
| [#3181](https://github.com/tscircuit/runframe/pull/3181) | 🐌 Tiny | Automated package update |
| [#3186](https://github.com/tscircuit/runframe/pull/3186) | 🐌 Tiny | Automated package update |
| [#3189](https://github.com/tscircuit/runframe/pull/3189) | 🐌 Tiny | Updates the package version from v0.0.1853 to v0.0.1854 in package.json |
| [#3185](https://github.com/tscircuit/runframe/pull/3185) | 🐌 Tiny | Updates the tscircuiteval package from version 0.0.769 to 0.0.770 |
| [#3184](https://github.com/tscircuit/runframe/pull/3184) | 🐌 Tiny | Automated package update |
| [#2790](https://github.com/tscircuit/cli/pull/2790) | 🐌 Tiny | Automated package update |
| [#2789](https://github.com/tscircuit/cli/pull/2789) | 🐌 Tiny | Updates the tscircuitrunframe package from version 0.0.1868 to 0.0.1869 |
| [#2788](https://github.com/tscircuit/cli/pull/2788) | 🐌 Tiny | Automated package update |
| [#2787](https://github.com/tscircuit/cli/pull/2787) | 🐌 Tiny | Updates the tscircuitrunframe package from version 0.0.1867 to 0.0.1868 |
| [#2786](https://github.com/tscircuit/cli/pull/2786) | 🐌 Tiny | Automated package update |
| [#2785](https://github.com/tscircuit/cli/pull/2785) | 🐌 Tiny | Updates the tscircuitrunframe package from version 0.0.1866 to 0.0.1867 |
| [#2784](https://github.com/tscircuit/cli/pull/2784) | 🐌 Tiny | Automated package update |
| [#2783](https://github.com/tscircuit/cli/pull/2783) | 🐌 Tiny | Updates the tscircuitrunframe package from version 0.0.1865 to 0.0.1866 |
| [#2782](https://github.com/tscircuit/cli/pull/2782) | 🐌 Tiny | Automated package update |
| [#2781](https://github.com/tscircuit/cli/pull/2781) | 🐌 Tiny | Updates the tscircuitrunframe package from version 0.0.1864 to 0.0.1865 |
| [#2780](https://github.com/tscircuit/cli/pull/2780) | 🐌 Tiny | Automated package update |
| [#2779](https://github.com/tscircuit/cli/pull/2779) | 🐌 Tiny | Updates the tscircuitrunframe package from version 0.0.1862 to 0.0.1864 |
| [#2778](https://github.com/tscircuit/cli/pull/2778) | 🐌 Tiny | Automated package update |
| [#2777](https://github.com/tscircuit/cli/pull/2777) | 🐌 Tiny | Automated README update with latest CLI usage output. |
| [#2776](https://github.com/tscircuit/cli/pull/2776) | 🐌 Tiny | Automated package update |
| [#2773](https://github.com/tscircuit/cli/pull/2773) | 🐌 Tiny | Automated package update |
| [#2772](https://github.com/tscircuit/cli/pull/2772) | 🐌 Tiny | Updates the tscircuitrunframe package from version 0.0.1861 to 0.0.1862 |
| [#2771](https://github.com/tscircuit/cli/pull/2771) | 🐌 Tiny | Automated package update |
| [#2770](https://github.com/tscircuit/cli/pull/2770) | 🐌 Tiny | Updates the tscircuitrunframe package from version 0.0.1860 to 0.0.1861 |
| [#2769](https://github.com/tscircuit/cli/pull/2769) | 🐌 Tiny | Automated package update |
| [#2768](https://github.com/tscircuit/cli/pull/2768) | 🐌 Tiny | Updates the tscircuitrunframe package to version 0.0.1860 |
| [#2767](https://github.com/tscircuit/cli/pull/2767) | 🐌 Tiny | Automated package update |
| [#2766](https://github.com/tscircuit/cli/pull/2766) | 🐌 Tiny | Updates the tscircuitrunframe package to version 0.0.1859 in the package.json file |
| [#2765](https://github.com/tscircuit/cli/pull/2765) | 🐌 Tiny | Automated package update |
| [#2764](https://github.com/tscircuit/cli/pull/2764) | 🐌 Tiny | Updates the tscircuitrunframe package to version 0.0.1858 in the package.json file. |
| [#2762](https://github.com/tscircuit/cli/pull/2762) | 🐌 Tiny | Updates the tscircuitrunframe package from version 0.0.1855 to 0.0.1857 |
| [#2760](https://github.com/tscircuit/cli/pull/2760) | 🐌 Tiny | Automated package update |
| [#2759](https://github.com/tscircuit/cli/pull/2759) | 🐌 Tiny | Automated package update |
| [#2748](https://github.com/tscircuit/cli/pull/2748) | 🐌 Tiny | Updates the tscircuitrunframe package from version 0.0.1849 to 0.0.1850 |
| [#2763](https://github.com/tscircuit/cli/pull/2763) | 🐌 Tiny | Automated package update |
| [#2761](https://github.com/tscircuit/cli/pull/2761) | 🐌 Tiny | Automated package update |
| [#2758](https://github.com/tscircuit/cli/pull/2758) | 🐌 Tiny | Updates the tscircuitrunframe package to version 0.0.1854 |
| [#2756](https://github.com/tscircuit/cli/pull/2756) | 🐌 Tiny | Updates the tscircuitrunframe package to version 0.0.1853 |
| [#2755](https://github.com/tscircuit/cli/pull/2755) | 🐌 Tiny | Automated package update |
| [#2754](https://github.com/tscircuit/cli/pull/2754) | 🐌 Tiny | Updates the tscircuitrunframe package from version 0.0.1851 to 0.0.1852 |
| [#2753](https://github.com/tscircuit/cli/pull/2753) | 🐌 Tiny | Automated package update |
| [#2752](https://github.com/tscircuit/cli/pull/2752) | 🐌 Tiny | Updates the tscircuitrunframe package from version 0.0.1850 to 0.0.1851 |
| [#2750](https://github.com/tscircuit/cli/pull/2750) | 🐌 Tiny | Automated package update |
| [#2757](https://github.com/tscircuit/cli/pull/2757) | 🐌 Tiny | Automated package update |
| [#1355](https://github.com/tscircuit/svg.tscircuit.com/pull/1355) | 🐌 Tiny | Updates the tscircuit package version from 0.0.1661 to 0.0.1662 in package.json |
| [#1354](https://github.com/tscircuit/svg.tscircuit.com/pull/1354) | 🐌 Tiny | Updates the tscircuit package version from 0.0.1660 to 0.0.1661 in package.json |
| [#975](https://github.com/tscircuit/tscircuit-autorouter/pull/975) | 🐌 Tiny | Automated package update |
| [#971](https://github.com/tscircuit/tscircuit-autorouter/pull/971) | 🐌 Tiny | Automated package update |
| [#966](https://github.com/tscircuit/tscircuit-autorouter/pull/966) | 🐌 Tiny | Automated package update |
| [#962](https://github.com/tscircuit/tscircuit-autorouter/pull/962) | 🐌 Tiny | Automated package update |
| [#958](https://github.com/tscircuit/tscircuit-autorouter/pull/958) | 🐌 Tiny | Automated package update |
| [#43](https://github.com/tscircuit/test-github-automerge/pull/43) | 🐌 Tiny | Updates the tscircuitcircuit-json-util package from version 0.0.93 to 0.0.94 in the development dependencies. |
| [#237](https://github.com/tscircuit/circuit-json-to-kicad/pull/237) | 🐌 Tiny | Automated package update |
| [#239](https://github.com/tscircuit/circuit-json-to-kicad/pull/239) | 🐌 Tiny | Automated package update |
| [#231](https://github.com/tscircuit/circuit-json-to-kicad/pull/231) | 🐌 Tiny | Automated package update |
| [#234](https://github.com/tscircuit/circuit-json-to-kicad/pull/234) | 🐌 Tiny | Automated package update |
| [#97](https://github.com/tscircuit/rectdiff/pull/97) | 🐌 Tiny | Automated package update |
| [#75](https://github.com/tscircuit/high-density-a01/pull/75) | 🐌 Tiny | Automated package update |

</details>

### [ShiboSoftwareDev](https://github.com/ShiboSoftwareDev)

| PRs # | Impact | Rating | Description |
|------|--------|--------|-------------|
| [#2165](https://github.com/tscircuit/core/pull/2165) | 🐳 Major | ⭐⭐⭐ | Propagates footprint.insertionDirection onto pcb_component.insertion_direction using the components global pre-layout rotation plus bottom-side mirroring, ensuring correct behavior for bottom-authored footprints and footprint constraints, while aligning board manufacturing defaults and tests with new clearance field names in circuit-json. |
| [#2169](https://github.com/tscircuit/core/pull/2169) | 🐳 Major | ⭐⭐⭐ | Propagates board minimum via dimensions through autorouting by updating the autorouter to use specific via dimensions from the board, ensuring routed via dimensions are preserved and not overwritten by defaults. |
| [#2162](https://github.com/tscircuit/core/pull/2162) | 🐳 Major | ⭐⭐⭐ | This change makes repeated non-overlapping footprint contacts behave like implicit internally connected pins instead of ambiguous PCB targets, allowing traces to target shared aliases directly and updating port matching accordingly. |
| [#950](https://github.com/tscircuit/tscircuit-autorouter/pull/950) | 🐳 Major | ⭐⭐⭐ | Normalizes via dimensions across autorouters by using a shared helper function, ensuring all autorouting pipelines utilize the specified pad and hole diameters, and updates circuit-json export and SVG rendering accordingly. |
| [#94](https://github.com/tscircuit/circuit-json-util/pull/94) | 🐙 Minor | ⭐⭐ | Updates transformPCBElement to maintain consistent pcb_component geometric metadata by transforming insertion_direction and moving cable_insertion_center with the applied matrix, while ensuring correct handling of quarter-turns for negative rotations. |
| [#2178](https://github.com/tscircuit/core/pull/2178) | 🐙 Minor | ⭐⭐ | Bumps the version of tscircuitchecks to 0.0.122 and adds regression tests for connector orientation warnings. |
| [#2168](https://github.com/tscircuit/core/pull/2168) | 🐙 Minor | ⭐⭐ | Maps simulation voltage graphs to their corresponding probes, ensuring differential ngspice graphs inherit colors from schematicsimulation probes and updates the default simulation color palette. |
| [#548](https://github.com/tscircuit/circuit-to-svg/pull/548) | 🐙 Minor | ⭐⭐ | Switch simulation graphs to a dedicated default palette with conventional plot colors so early traces use familiar blueredgreen-style ordering. |
| [#141](https://github.com/tscircuit/checks/pull/141) | 🐙 Minor | ⭐⭐ | Update connector accessibility checks to use pcb_component.insertion_direction when available, with fallback to cable_insertion_center for older data. This maps side-entry directions to facing axes, skips from_above, and no longer requires cable_insertion_center to run the check. |

<details>
<summary>🐌 Tiny Contributions (2)</summary>

| PR # | Impact | Description |
|------|--------|-------------|
| [#2974](https://github.com/tscircuit/tscircuit/pull/2974) | 🐌 Tiny | Prevents synchronization of the tscircuitjlcpcb-manufacturing-specs package during the core version copying process. |
| [#638](https://github.com/tscircuit/props/pull/638) | 🐌 Tiny | Removes the directional options x, x-, y, and y- from the footprint insertion direction type definition, streamlining the available options for users. |

</details>

### [techmannih](https://github.com/techmannih)

| PRs # | Impact | Rating | Description |
|------|--------|--------|-------------|
| [#2170](https://github.com/tscircuit/core/pull/2170) | 🐙 Minor | ⭐⭐ | Adds support for rectBorderRadius in pill_hole_with_rect_pad plated holes, allowing for customizable corner rounding in PCB design. |
| [#232](https://github.com/tscircuit/circuit-json-to-kicad/pull/232) | 🐙 Minor | ⭐⭐ | Enables the inclusion of supplier part numbers (specifically from jlcpcb) as properties in the generated KiCad PCB footprints. |
| [#233](https://github.com/tscircuit/circuit-json-to-kicad/pull/233) | 🐙 Minor | ⭐⭐ | Adds rotation support for circular and rotated pill holes with rectangular pads in PCB design, enhancing the flexibility of hole placement. |
| [#62](https://github.com/tscircuit/kicad-to-circuit-json/pull/62) | 🐙 Minor | ⭐⭐ | Adds support for a new plated hole shape, specifically the pill_hole_with_rect_pad, enhancing the PCB design capabilities. |

<details>
<summary>🐌 Tiny Contributions (4)</summary>

| PR # | Impact | Description |
|------|--------|-------------|
| [#2978](https://github.com/tscircuit/tscircuit/pull/2978) | 🐌 Tiny | Updates the tscircuitprops dependency version from 0.0.508 to 0.0.512 in package.json |
| [#640](https://github.com/tscircuit/props/pull/640) | 🐌 Tiny | Adds a new property rectBorderRadius to the PillWithRectPadPlatedHoleProps interface, allowing for customizable border radius on rectangular plated holes. |
| [#2749](https://github.com/tscircuit/cli/pull/2749) | 🐌 Tiny | Updates the version of the circuit-json-to-kicad dependency from 0.0.109 to 0.0.114 in package.json |
| [#236](https://github.com/tscircuit/circuit-json-to-kicad/pull/236) | 🐌 Tiny | Adds a test to ensure that 0402 footprints maintain pad rotation when components are rotated 45 degrees in the circuit. |

</details>

### [imrishabh18](https://github.com/imrishabh18)

| PRs # | Impact | Rating | Description |
|------|--------|--------|-------------|
| [#2181](https://github.com/tscircuit/core/pull/2181) | 🐙 Minor | ⭐⭐ | Updates dependencies to the latest versions and migrates PCB manufacturing DRC field names to match the new schema in the circuit JSON. |
| [#2163](https://github.com/tscircuit/core/pull/2163) | 🐙 Minor | ⭐⭐ | Updates DRC properties in the board schema from spacing to clearance to align with upstream package changes and resolves TypeScript errors. |
| [#136](https://github.com/tscircuit/checks/pull/136) | 🐙 Minor | ⭐⭐ | Aligns local DRC default values with the published JLCPCB minimum manufacturing tolerances, replacing hardcoded values with dynamic values from the jlcMinTolerances package. |

<details>
<summary>🐌 Tiny Contributions (9)</summary>

| PR # | Impact | Description |
|------|--------|-------------|
| [#562](https://github.com/tscircuit/circuit-json/pull/562) | 🐌 Tiny | Renames DRC properties for clarity and consistency in the manufacturing DRC properties interface. |
| [#641](https://github.com/tscircuit/props/pull/641) | 🐌 Tiny | Renames DRC-related props on SubcircuitGroupProps to consistent camelCase names for runtime validation and documentation. |
| [#2171](https://github.com/tscircuit/core/pull/2171) | 🐌 Tiny | Bundles the tscircuitjlcpcb-manufacturing-specs package with the core package, modifying the build process and configuration. |
| [#139](https://github.com/tscircuit/checks/pull/139) | 🐌 Tiny | Sets default clearance values for PCB components based on the PCB board specifications and JLCPCB manufacturing tolerances. |
| [#140](https://github.com/tscircuit/checks/pull/140) | 🐌 Tiny | Fixes the wording of error messages related to PCB trace overlaps and gaps to provide clearer information to users. |
| [#138](https://github.com/tscircuit/checks/pull/138) | 🐌 Tiny | Changes the build process to bundle the tscircuitjlcpcb-manufacturing-specs package and modifies the build script accordingly. |
| [#3225](https://github.com/tscircuit/tscircuit.com/pull/3225) | 🐌 Tiny | Updates the website URL in the about section to use the package release website URL instead of the previous method of determining the URL. |
| [#970](https://github.com/tscircuit/tscircuit-autorouter/pull/970) | 🐌 Tiny | This pull request adds a new bug report fixture for bug report ID 51, including a JSON representation of the bug report and a corresponding React component for testing. |
| [#4](https://github.com/tscircuit/jlcpcb-manufacturing-specs/pull/4) | 🐌 Tiny | Renames JLCPCB tolerance keys for clarity, adjusts default tolerance values for accuracy, and updates the circuit-json dependency to ensure compatibility with the latest board schema. |

</details>

### [Abse2001](https://github.com/Abse2001)

| PRs # | Impact | Rating | Description |
|------|--------|--------|-------------|
| [#384](https://github.com/tscircuit/easyeda-converter/pull/384) | 🐳 Major | ⭐⭐⭐ | This pull request refactors the CAD offset logic to utilize model bounds and extract the SVG origin. It introduces a new method for calculating the CAD model offset based on the bounds of the model, improving the accuracy of the placement of CAD models in the circuit design. The changes include updates to the conversion functions and adjustments to the handling of CAD model properties, ensuring that the models origin is correctly calculated and applied during the conversion process. |
| [#765](https://github.com/tscircuit/3d-viewer/pull/765) | 🐳 Major | ⭐⭐⭐ | https:3d-viewer-git-fork-abse2001-main-tscircuit.vercel.app?pathstorykeypad--default |
| [#2175](https://github.com/tscircuit/core/pull/2175) | 🐳 Major | ⭐⭐⭐ | Adds a test for rendering a double-row pinheader and updates the circuit-json-to-gltf dependency version. |
| [#1](https://github.com/tscircuit/high-density-repair03/pull/1) | 🐳 Major | ⭐⭐⭐ | This pull request introduces the GlobalDrcForceImproveSolver, a new solver for improving high-density PCB routes against DRC-style errors. It includes a comprehensive implementation of the solver logic, types, and usage documentation. |

<details>
<summary>🐌 Tiny Contributions (3)</summary>

| PR # | Impact | Description |
|------|--------|-------------|
| [#2164](https://github.com/tscircuit/core/pull/2164) | 🐌 Tiny | Updates the version of the tscircuitfootprinter dependency from 0.0.349 to 0.0.351 in package.json |
| [#287](https://github.com/tscircuit/jscad-electronics/pull/287) | 🐌 Tiny | Centers multi-row PinRow footprints around the component origin to ensure proper alignment in the layout. |
| [#157](https://github.com/tscircuit/circuit-json-to-gltf/pull/157) | 🐌 Tiny | Adds a test for a double row pinheader and updates the jscad-electronics dependency to version 0.0.129. |

</details>

### [rushabhcodes](https://github.com/rushabhcodes)


<details>
<summary>🐌 Tiny Contributions (6)</summary>

| PR # | Impact | Description |
|------|--------|-------------|
| [#77](https://github.com/tscircuit/circuit-json-to-gerber/pull/77) | 🐌 Tiny | Updates the version of the tscircuitalphabet dependency in package.json to ensure compatibility with the latest features and bug fixes. |
| [#3216](https://github.com/tscircuit/tscircuit.com/pull/3216) | 🐌 Tiny | Removes the local BomTable component and its associated logic as it is no longer referenced in the application, streamlining the codebase without affecting runtime behavior. |
| [#2774](https://github.com/tscircuit/cli/pull/2774) | 🐌 Tiny | Updates the versions of the dependencies circuit-json-to-gerber and poppygl in the package.json file to their latest versions, ensuring compatibility with recent features and bug fixes. |
| [#9](https://github.com/tscircuit/tscircuit.com-landing/pull/9) | 🐌 Tiny | Updates the landing page copy for clarity, revises statistics, and optimizes gallery image loading by switching from remote URLs to local assets. |
| [#7](https://github.com/tscircuit/tscircuit.com-landing/pull/7) | 🐌 Tiny | Updates the landing page with improved UI elements, navigation simplification, animated GitHub star count, and replaces the autorouting demo video. |
| [#8](https://github.com/tscircuit/tscircuit.com-landing/pull/8) | 🐌 Tiny | Enhances the small-screen experience on the landing page by tightening the feature card layout, simplifying repeated card styles, and redesigning the footer for mobile to read as a compact sitemap instead of a squeezed desktop stack. |

</details>

### [mohan-bee](https://github.com/mohan-bee)

| PRs # | Impact | Rating | Description |
|------|--------|--------|-------------|
| [#3197](https://github.com/tscircuit/runframe/pull/3197) | 🐙 Minor | ⭐⭐ | Fixes the Import Component package details view so clicking See Details no longer appears broken when the details dialog opens behind the search dialog. |
| [#235](https://github.com/tscircuit/circuit-json-to-kicad/pull/235) | 🐙 Minor | ⭐⭐ | Fixes KiCad export for pcb_silkscreen_path objects that belong to a component, ensuring they are exported as footprint-local primitives instead of board-level graphics. |

<details>
<summary>🐌 Tiny Contributions (1)</summary>

| PR # | Impact | Description |
|------|--------|-------------|
| [#535](https://github.com/tscircuit/docs/pull/535) | 🐌 Tiny | Adds new export formats for assembly SVG and STEP 3D model to the documentation. |

</details>

### [AnasSarkiz](https://github.com/AnasSarkiz)

| PRs # | Impact | Rating | Description |
|------|--------|--------|-------------|
| [#974](https://github.com/tscircuit/tscircuit-autorouter/pull/974) | 🐳 Major | ⭐⭐⭐ | Enhances benchmark feedback by incorporating early results, comparing with main branch deltas, and implementing timeouts for profile solvers. |
| [#949](https://github.com/tscircuit/tscircuit-autorouter/pull/949) | 🐳 Major | ⭐⭐⭐ | Enhances margin-aware violation detection in the autorouting process to improve design rule checking accuracy. |
| [#6](https://github.com/tscircuit/high-density-repair01/pull/6) | 🐳 Major | ⭐⭐⭐ | Replaces the legacy benchmark flow with a unified runner that delivers automated reports, powerful CLI tooling, and scalable benchmarking for current and future datasets. |
| [#5](https://github.com/tscircuit/high-density-repair01/pull/5) | 🐳 Major | ⭐⭐⭐ | Adds a projection-based post-processing pass that separates overlapping vias and traces inside dense nodes while keeping routes within bounds. Improves routing clarity, spacing, and overall collision resolution. |
| [#972](https://github.com/tscircuit/tscircuit-autorouter/pull/972) | 🐙 Minor | ⭐⭐ | Adds --profile-solvers support to benchmark CI, enabling profile comparison tables for PR and main in benchmark results. |

### [0hmX](https://github.com/0hmX)

| PRs # | Impact | Rating | Description |
|------|--------|--------|-------------|
| [#953](https://github.com/tscircuit/tscircuit-autorouter/pull/953) | 🐳 Major | ⭐⭐⭐ | Adds a focused reproduction for a high-density solver issue related to reentry in nodeWithPortPoints input, including new test cases and fixtures. |

<details>
<summary>🐌 Tiny Contributions (3)</summary>

| PR # | Impact | Description |
|------|--------|-------------|
| [#956](https://github.com/tscircuit/tscircuit-autorouter/pull/956) | 🐌 Tiny | Removes the SVG snapshot test for bugreport49 from the test suite. |
| [#96](https://github.com/tscircuit/rectdiff/pull/96) | 🐌 Tiny | Adds a test for generating a multi-layer node summary from SRJ files, ensuring correct volume calculations and obstacle handling. |
| [#94](https://github.com/tscircuit/rectdiff/pull/94) | 🐌 Tiny | This pull request introduces new fixtures for the Arduino Uno plane-layer rectdiff functionality. It includes new page components and JSON assets that define the routing and layout for the Arduino Uno, enhancing the existing rectdiff capabilities. |

</details>

### [Sang-it](https://github.com/Sang-it)

| PRs # | Impact | Rating | Description |
|------|--------|--------|-------------|
| [#229](https://github.com/tscircuit/circuit-json-to-kicad/pull/229) | 🐙 Minor | ⭐⭐ | Fixes KiCad pad labeling to preserve source pin identity instead of array order, ensuring correct pad numbering for custom footprints. |

<details>
<summary>🐌 Tiny Contributions (2)</summary>

| PR # | Impact | Description |
|------|--------|-------------|
| [#208](https://github.com/tscircuit/schematic-trace-solver/pull/208) | 🐌 Tiny | Adds debug labels to the NetLabelPlacementSolver for better visualization of net IDs and anchor points during the placement process. |
| [#205](https://github.com/tscircuit/schematic-trace-solver/pull/205) | 🐌 Tiny | Adds a new example page and corresponding tests for the schematic trace solver. |

</details>

### [seveibar](https://github.com/seveibar)

| PRs # | Impact | Rating | Description |
|------|--------|--------|-------------|
| [#74](https://github.com/tscircuit/high-density-a01/pull/74) | 🐳 Major | ⭐⭐⭐ | Adds a new solver (A09) to the high-density routing system, enhancing routing capabilities with new parameters and functionality. |

## Repository Owners

| Repository | Codeowners |
|------------|------------|
| [builder](https://github.com/tscircuit/builder/blob/main/.github/CODEOWNERS) | [seveibar](https://github.com/seveibar)
| [pcb-viewer](https://github.com/tscircuit/pcb-viewer/blob/main/.github/CODEOWNERS) | [seveibar](https://github.com/seveibar), [ShiboSoftwareDev](https://github.com/ShiboSoftwareDev), [Abse2001](https://github.com/Abse2001)
| [footprints-old](https://github.com/tscircuit/footprints-old/blob/main/.github/CODEOWNERS) | [seveibar](https://github.com/seveibar)
| [footprinter](https://github.com/tscircuit/footprinter/blob/main/.github/CODEOWNERS) | [seveibar](https://github.com/seveibar), [techmannih](https://github.com/techmannih)
| [3d-viewer](https://github.com/tscircuit/3d-viewer/blob/main/.github/CODEOWNERS) | [ShiboSoftwareDev](https://github.com/ShiboSoftwareDev), [Abse2001](https://github.com/Abse2001)
| [winterspec](https://github.com/tscircuit/winterspec/blob/main/.github/CODEOWNERS) | [seveibar](https://github.com/seveibar), [ShiboSoftwareDev](https://github.com/ShiboSoftwareDev)
| [jscad-electronics](https://github.com/tscircuit/jscad-electronics/blob/main/.github/CODEOWNERS) | [seveibar](https://github.com/seveibar), [techmannih](https://github.com/techmannih), [ShiboSoftwareDev](https://github.com/ShiboSoftwareDev), [anas-sarkez](https://github.com/anas-sarkez)
| [circuit-to-svg](https://github.com/tscircuit/circuit-to-svg/blob/main/.github/CODEOWNERS) | [imrishabh18](https://github.com/imrishabh18)
| [schematic-symbols](https://github.com/tscircuit/schematic-symbols/blob/main/.github/CODEOWNERS) | [seveibar](https://github.com/seveibar), [imrishabh18](https://github.com/imrishabh18), [techmannih](https://github.com/techmannih)
| [circuit-json-to-gerber](https://github.com/tscircuit/circuit-json-to-gerber/blob/main/.github/CODEOWNERS) | [seveibar](https://github.com/seveibar), [ShiboSoftwareDev](https://github.com/ShiboSoftwareDev)
| [tscircuit.com](https://github.com/tscircuit/tscircuit.com/blob/main/.github/CODEOWNERS) | [seveibar](https://github.com/seveibar), [imrishabh18](https://github.com/imrishabh18)
| [issue-roulette](https://github.com/tscircuit/issue-roulette/blob/main/.github/CODEOWNERS) | [Anshgrover23](https://github.com/Anshgrover23)
| [sparkfun-boards](https://github.com/tscircuit/sparkfun-boards/blob/main/.github/CODEOWNERS) | [ShiboSoftwareDev](https://github.com/ShiboSoftwareDev), [Abse2001](https://github.com/Abse2001), [MustafaMulla29](https://github.com/MustafaMulla29), [Anshgrover23](https://github.com/Anshgrover23), [techmannih](https://github.com/techmannih)
| [schematic-corpus](https://github.com/tscircuit/schematic-corpus/blob/main/.github/CODEOWNERS) | [Abse2001](https://github.com/Abse2001)
| [copper-pour-solver](https://github.com/tscircuit/copper-pour-solver/blob/main/.github/CODEOWNERS) | [seveibar](https://github.com/seveibar), [ShiboSoftwareDev](https://github.com/ShiboSoftwareDev)
| [common](https://github.com/tscircuit/common/blob/main/.github/CODEOWNERS) | [seveibar](https://github.com/seveibar), [Abse2001](https://github.com/Abse2001)
| [circuit-to-canvas](https://github.com/tscircuit/circuit-to-canvas/blob/main/.github/CODEOWNERS) | [ShiboSoftwareDev](https://github.com/ShiboSoftwareDev), [Abse2001](https://github.com/Abse2001), [techmannih](https://github.com/techmannih)
| [circuit-json-to-lbrn](https://github.com/tscircuit/circuit-json-to-lbrn/blob/main/.github/CODEOWNERS) | [AnasSarkiz](https://github.com/AnasSarkiz)
| [pcbburn.com](https://github.com/tscircuit/pcbburn.com/blob/main/.github/CODEOWNERS) | [AnasSarkiz](https://github.com/AnasSarkiz)

## Repositories by Owner

| User | Repo |
|------|------|
| [seveibar](https://github.com/seveibar) | [builder](https://github.com/tscircuit/builder/blob/main/.github/CODEOWNERS) |
|  | [pcb-viewer](https://github.com/tscircuit/pcb-viewer/blob/main/.github/CODEOWNERS) |
|  | [footprints-old](https://github.com/tscircuit/footprints-old/blob/main/.github/CODEOWNERS) |
|  | [footprinter](https://github.com/tscircuit/footprinter/blob/main/.github/CODEOWNERS) |
|  | [winterspec](https://github.com/tscircuit/winterspec/blob/main/.github/CODEOWNERS) |
|  | [jscad-electronics](https://github.com/tscircuit/jscad-electronics/blob/main/.github/CODEOWNERS) |
|  | [schematic-symbols](https://github.com/tscircuit/schematic-symbols/blob/main/.github/CODEOWNERS) |
|  | [circuit-json-to-gerber](https://github.com/tscircuit/circuit-json-to-gerber/blob/main/.github/CODEOWNERS) |
|  | [tscircuit.com](https://github.com/tscircuit/tscircuit.com/blob/main/.github/CODEOWNERS) |
|  | [copper-pour-solver](https://github.com/tscircuit/copper-pour-solver/blob/main/.github/CODEOWNERS) |
|  | [common](https://github.com/tscircuit/common/blob/main/.github/CODEOWNERS) |
| [ShiboSoftwareDev](https://github.com/ShiboSoftwareDev) | [pcb-viewer](https://github.com/tscircuit/pcb-viewer/blob/main/.github/CODEOWNERS) |
|  | [3d-viewer](https://github.com/tscircuit/3d-viewer/blob/main/.github/CODEOWNERS) |
|  | [winterspec](https://github.com/tscircuit/winterspec/blob/main/.github/CODEOWNERS) |
|  | [jscad-electronics](https://github.com/tscircuit/jscad-electronics/blob/main/.github/CODEOWNERS) |
|  | [circuit-json-to-gerber](https://github.com/tscircuit/circuit-json-to-gerber/blob/main/.github/CODEOWNERS) |
|  | [sparkfun-boards](https://github.com/tscircuit/sparkfun-boards/blob/main/.github/CODEOWNERS) |
|  | [copper-pour-solver](https://github.com/tscircuit/copper-pour-solver/blob/main/.github/CODEOWNERS) |
|  | [circuit-to-canvas](https://github.com/tscircuit/circuit-to-canvas/blob/main/.github/CODEOWNERS) |
| [Abse2001](https://github.com/Abse2001) | [pcb-viewer](https://github.com/tscircuit/pcb-viewer/blob/main/.github/CODEOWNERS) |
|  | [3d-viewer](https://github.com/tscircuit/3d-viewer/blob/main/.github/CODEOWNERS) |
|  | [sparkfun-boards](https://github.com/tscircuit/sparkfun-boards/blob/main/.github/CODEOWNERS) |
|  | [schematic-corpus](https://github.com/tscircuit/schematic-corpus/blob/main/.github/CODEOWNERS) |
|  | [common](https://github.com/tscircuit/common/blob/main/.github/CODEOWNERS) |
|  | [circuit-to-canvas](https://github.com/tscircuit/circuit-to-canvas/blob/main/.github/CODEOWNERS) |
| [techmannih](https://github.com/techmannih) | [footprinter](https://github.com/tscircuit/footprinter/blob/main/.github/CODEOWNERS) |
|  | [jscad-electronics](https://github.com/tscircuit/jscad-electronics/blob/main/.github/CODEOWNERS) |
|  | [schematic-symbols](https://github.com/tscircuit/schematic-symbols/blob/main/.github/CODEOWNERS) |
|  | [sparkfun-boards](https://github.com/tscircuit/sparkfun-boards/blob/main/.github/CODEOWNERS) |
|  | [circuit-to-canvas](https://github.com/tscircuit/circuit-to-canvas/blob/main/.github/CODEOWNERS) |
| [anas-sarkez](https://github.com/anas-sarkez) | [jscad-electronics](https://github.com/tscircuit/jscad-electronics/blob/main/.github/CODEOWNERS) |
| [imrishabh18](https://github.com/imrishabh18) | [circuit-to-svg](https://github.com/tscircuit/circuit-to-svg/blob/main/.github/CODEOWNERS) |
|  | [schematic-symbols](https://github.com/tscircuit/schematic-symbols/blob/main/.github/CODEOWNERS) |
|  | [tscircuit.com](https://github.com/tscircuit/tscircuit.com/blob/main/.github/CODEOWNERS) |
| [Anshgrover23](https://github.com/Anshgrover23) | [issue-roulette](https://github.com/tscircuit/issue-roulette/blob/main/.github/CODEOWNERS) |
|  | [sparkfun-boards](https://github.com/tscircuit/sparkfun-boards/blob/main/.github/CODEOWNERS) |
| [MustafaMulla29](https://github.com/MustafaMulla29) | [sparkfun-boards](https://github.com/tscircuit/sparkfun-boards/blob/main/.github/CODEOWNERS) |
| [AnasSarkiz](https://github.com/AnasSarkiz) | [circuit-json-to-lbrn](https://github.com/tscircuit/circuit-json-to-lbrn/blob/main/.github/CODEOWNERS) |
|  | [pcbburn.com](https://github.com/tscircuit/pcbburn.com/blob/main/.github/CODEOWNERS) |



<!-- END_CURRENT_WEEK -->


## Development

### Prerequisites

- [Bun](https://bun.sh/) runtime
- `.env` file with required API keys:
  ```
  GITHUB_TOKEN=your_github_token
  OPENAI_API_KEY=your_openai_api_key
  DISCORD_TOKEN=your_discord_token (optional, for Discord integration)
  SLACK_BOT_TOKEN=your_slack_token (optional, for Slack integration)
  ```

### Available Scripts

#### Core Generation Scripts

- `bun run generate:weekly` - Generate current week's contribution overview
- `bun run generate:monthly` - Generate current month's contribution overview
- `bun run generate:changelog` - Generate monthly changelog from PRs

#### Analysis & Testing

- `bun run analyze-pr` - Analyze a single PR (interactive prompt)
- `bun run test:github` - Test GitHub API integration

#### Notifications & Sync

- `bun run notifications:issues` - Send notifications for new issues
- `bun run notifications:pr` - Send notifications for new PRs
- `bun run sync:discord` - Sync contributor roles with Discord

#### Data Export

- `bun run export:sponsorship` - Generate sponsorship data CSV

#### Development

- `bun run dev` - Start development server for web UI
- `bun run build` - Build for production
- `bun run format` - Format code with Biome

### Usage Examples

```bash
# Generate this week's contribution overview
bun run generate:weekly

# Generate current month's overview
bun run generate:monthly

# Analyze a specific PR
bun run analyze-pr

# Test your GitHub token setup
bun run test:github
```
