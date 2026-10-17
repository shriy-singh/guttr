# Guttr brand direction (draft)

**Status:** Working brand notes based on shared visual assets and the October 2026 build report. This is not a final brand guide.

## Positioning

**GUTTR** explores open comic survey kits: a way to create, share, and answer surveys through sequential visual storytelling. The name refers to the **gutter**, the space between comic panels where the reader constructs meaning.

The existing site's editorial language and the playful orange character can coexist: **the split-panel wordmark is the formal identity; the character is its expressive counterpart.**

## Current visual system

These values were documented in the shared Lovable build report and should be checked against the actual application styles before changing code.

| Token | Proposed value |
| --- | --- |
| Bone | `#F6F5F0` |
| Ink | `#111213` |
| Vermilion | `#FF4D26` |
| Secondary | Cobalt, exact token to confirm |
| Headings | Space Grotesk |
| Body | DM Sans |
| Metadata | JetBrains Mono |
| Editorial accents | Fraunces |
| Graphic rules | Thin ink borders, square corners, hard offset shadows |

## Asset roles

| Supplied file | Intended role |
| --- | --- |
| `favicon.svg` | Small browser and app icon |
| `github-social-preview.jpg` | GitHub social sharing / repository preview |
| `linkedin-banner.jpg` | LinkedIn company cover |
| `linkedin-logo.png` | LinkedIn company avatar, mascot lockup |

**Asset sources:** Files were provided directly by the project creator in conversation. The binary assets are not yet synced to this repository; paths above document the intended source filenames rather than claiming the files already exist here.

## Usage recommendations

- Keep the compact split-panel wordmark in the site's navigation and footer.
- Use the orange gutter mascot in social media, onboarding, illustrative empty states, and selective promotional settings.
- Let actual comics and workshop outcomes dominate the site's hero and editorial illustrations.
- Avoid filling every page with the mascot or substituting decorative cartoons for real comic survey examples.
- Treat the LinkedIn and GitHub assets as format-specific adaptations of one identity rather than separate brands.

## Website footer recommendation

Prefer a compact four-column footer compatible with the current website:

1. **Brand:** wordmark and one-line positioning.
2. **Platform:** Experiment Room, Studio, Asset Hub.
3. **Contribute:** Contribute a kit, GitHub repository.
4. **Research & resources:** About, Help, attribution and license information; add LinkedIn once live.

Suggested GitHub label: **GitHub repository**, linking to https://github.com/shriy-singh/guttr.

Do not call the repository fully open source until the software and art licensing decisions are confirmed.

## Follow-up

- Receive and inspect the Lovable project URL before editing the live website.
- Add the supplied original files to a future `public/brand/` or project-appropriate location once the actual source tree is known.
- Check favicon legibility at 16 px and 32 px.
- Verify LinkedIn cover and avatar cropping in LinkedIn's interface.
- Configure GitHub's repository social-preview image in GitHub Settings, which may require manual action.
