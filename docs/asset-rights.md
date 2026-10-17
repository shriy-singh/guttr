# Asset licensing, attribution, and artist participation

**Status:** Working rights framework based on Comic Survey Lab discussion materials. **Not** a selected legal license, contributor agreement, or final compensation policy.

## What the project discussions establish

**Agreed product direction**

- GUTTR is intended to support a reusable comic asset library assembled from **openly licensed contributions, donated work, and commissioned artist work**.
- Every asset should preserve its **creator, original source, license, usage rights, and version/provenance information**.
- **Software source-code licensing and artwork licensing are separate decisions.** A license on the code does not automatically apply to drawings or third-party media.
- Asset stewardship should fit together with GitHub-like versions, attribution, project history, and published survey reproducibility.
- Comicification should remain creator-led, with artists' work credited and their rights respected.

**Not yet settled in those discussions**

- An exact software license (MIT, Apache-2.0, GPL, etc.).
- Which open-content licenses the Asset Hub will accept and how incompatible licenses are handled.
- Whether contributions allow reuse, modification, standalone downloads, commercial use, or redistribution.
- Standard contributor agreements and any rights granted to GUTTR.
- Artist payment, commissions, purchases, royalty or revenue-share model.
- Takedown and license withdrawal policies, including consequences for already-published survey versions.

**Important:** A donation is not automatically a public-domain dedication, and showing an asset in a published survey is not necessarily the same permission as redistributing the editable source file.

## Asset-source cautions from the October 2026 build specification

The creator-provided build specification names original workshop artwork, lab-supplied assets, and OpenMoji. It specifically says **lab-bundle assets are not redistributable** and identifies **OpenMoji as CC BY-SA 4.0**. These are source-specific conditions and must not be replaced by a blanket license covering the full Asset Hub.

Before making the application's source repository public, review any bundled imagery separately from the application code and avoid publishing assets whose redistribution rights are not established.

## Candidate library metadata

For each asset, plan to record artist name, source URL, license and license version, attribution wording, allowed use/remix/redistribution, original file provenance, asset version, and usage within published surveys. This is a proposed metadata inventory, not an implemented schema.

## Decisions required before choosing a LICENSE file

1. Decide whether the **application source code** will be open source and, if so, under which exact license.
2. Establish license and contribution requirements for **original GUTTR-produced artwork**.
3. Create explicit artist agreements for **donated and commissioned assets**.
4. Maintain per-asset licensing for **third-party content** and ensure attribution and redistribution compatibility.
5. Determine how **asset updates or removals** affect historical published surveys.

## Source grounding

This distinction between agreed direction and undecided policy comes from the supplied *Comic Survey Lab Comprehensive Handover* (sections 2, 13, 17 and 19) and *Comic Survey Lab Proposal + Ideation* (sections 8 and 9), alongside the October 2026 *GUTTR Build Specification*. No exact repository-wide license is established in those materials.
