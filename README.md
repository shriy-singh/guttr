# GUTTR

**Every respondent, inside the story.**

GUTTR is a working, evolving comic survey studio for creating visual surveys and answering through drawing, counting, voice, selecting, pointing, and writing. It grew from earlier Comic Survey Lab research and workshops.

- **Try GUTTR:** https://guttr.lovable.app
- **GUTTR company page on LinkedIn:** https://www.linkedin.com/company/comic-survey-lab/
- **Project GitHub:** https://github.com/shriy-singh/guttr

**Important:** The LinkedIn company page URL includes the words `comic-survey-lab`, but **it is GUTTR's company page**, not a separate research organization's profile.

## What Guttr offers

- **Studio:** Visual survey editing, templates, remix, seven answer types (count/tally, drawing, voice, scene selection, scale, choice, text), privacy declaration, and export tools.
- **Experiment Room:** Paper-first capture and panel marking in a guided workflow that moves toward a digital survey.
- **Asset Hub:** Browse creator-credited assets and manage browser-local kits with version history and restore.
- **Respondent flow:** Panel-by-panel interaction, with a guest preview option.

The [October 2026 build specification](https://guttr.lovable.app) documents the above features, with important caveats: authenticated publishing, owner response readback, and two-device QR capture were **implemented but not verified end to end** in the documentation pass. Browser-local kits are not a shared online review platform. Weather, Origami, and Music Box response types remain concepts. The report also notes mobile Studio overflow. This README does not claim independent production verification.

## Why “Guttr”?

The gutter is the gap between comic panels where readers construct meaning. GUTTR explores what becomes possible when a respondent helps complete the story while researchers can still work with structured answers.

This approach to **comicification** builds upon Comic Survey Lab workshops and ongoing research. Engagement, accessibility, and response-quality benefits remain research questions, not proven outcomes.

## Where to start

- [Open the live site](https://guttr.lovable.app)
- [Product vision and research motivation](docs/vision.md)
- [Proposed workflows](docs/workflows.md)
- [Research questions](docs/research.md)
- [Product decisions](docs/open-decisions.md)
- [Brand direction](docs/brand-direction.md)
- [Source handoff notes](docs/source-handoff.md)
- [Asset rights and contribution considerations](docs/asset-rights.md)
- [Proposed noncommercial remix policy](docs/remix-policy.md)
- [Community kit catalog and neutral naming](community-kits/README.md)
- [Contributor credit register](docs/community-credits.md)

## Local installation and development

Once the application source code is available in your local checkout, install dependencies and start the development server:

**Recommended (Bun):**

```bash
bun install
bun dev
```

**Alternative (npm):**

```bash
npm install
npm run dev
```

Run these commands from the project directory containing `package.json`. Bun is the preferred option because the supplied application source includes a `bun.lock` file.

> **Source availability:** This repository currently contains project documentation. The application code is awaiting a public-source and asset-rights review, so cloning this repository alone will not yet provide a runnable app.

## Contribute to the GUTTR ecosystem

You can help GUTTR without needing access to the proprietary application code:

- [Propose a reusable comic kit](docs/contribute-a-kit.md)
- [Contribute research ideas, accessibility feedback or documentation](CONTRIBUTING.md)
- [Open a GitHub Issue](https://github.com/shriy-singh/guttr/issues/new/choose)
- [Explore the visual tour](docs/visual-tour.md)

Artist ownership, licenses, provenance, and contribution acceptance are handled individually. Public proposals do not transfer copyright.

## Source-code handoff

The project creator has supplied a source-code ZIP containing a TanStack Start / React / Vite application with `package.json` and `bun.lock`. For safety, the source has **not yet been copied wholesale into this public repository**: the archive includes an `.env` configuration and third-party or workshop visual assets requiring rights review. See [source handoff](docs/source-handoff.md).

The ZIP's declared scripts include `bun dev` and, when Bun is unavailable, `npm run dev` (the actual `package.json` script is named `dev`). This documentation does not claim that the environment has been successfully installed or launched.

## Rights and licensing

No software open-source license has been selected. Original workshop artwork, lab-supplied imagery, and third-party asset libraries must be handled under their respective permissions; open access to this repository does not license those works for redistribution.

For questions or collaboration, use the GUTTR website or company page.
