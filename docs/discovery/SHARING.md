# Sharing and discovery checklist

> TypeSafeAI is an unofficial community organization, not the official TypeSafe AI team. Keep that distinction visible in descriptions, cards, screenshots, and release copy.

## Three different publishing surfaces

1. **Repository documentation:** README, documentation links, agent instructions, and committed media. A Markdown image displays in the README; it does not configure GitHub's link preview.
2. **GitHub settings:** About description, homepage, topics, and Social preview. `repository-metadata.json` records intended values only. Apply them through an authorized settings action and read the settings back before reporting success.
3. **Website metadata:** rendered title, description, Open Graph/Twitter tags, image routes, and canonical URLs. These require the application change to build and deploy. A merged source change is not proof that production serves it.

## Artwork

The [community card source](assets/social-preview.svg) is editable SVG at 1280 × 640. It is an editorial graphic, not a screenshot or measured result. Preserve the unofficial label and legibility at small sizes. No font files are redistributed.

For a GitHub repository Social preview, export an actual PNG/JPEG/GIF under 1 MB; GitHub recommends 1280 × 640. Validate the raster dimensions, open the result, and upload it in **Settings → General → Social preview**. An SVG source alone is not a completed raster upload. Do not add a manifest path to an asset that has not been committed.

## About text, homepage, and topics

Use a concrete description of implemented behavior and an independently verified public homepage. Preserve existing relevant topics. Topics are discovery categories, not release tags; prefer a small, relevant set within GitHub's 20-topic limit. Do not add unrelated trending names, a fake package badge, unsupported benchmarks, or safety guarantees.

Retain demo URLs during metadata updates. Keep official TypeSafe AI resources separate from community-hosted projects. Do not imply affiliation by omitting the unofficial label.

## Website verification

Inspect the rendered HTML and image response for the exact build, not just the source object. Check title, description, public absolute image URL, descriptive alt text, HTTP 200, image content type, and an image that loads without credentials. Keep page-specific generators where they already exist.

Use the real production origin and preserve route-specific canonical URLs. Do not canonicalize every route to the homepage, index private/session/API routes, or invent a deployment domain. Preview deployments must not become the claimed public origin. Do not put credentials, prompts, private writing, or results into share URLs or OG images.

Do not publish a sitemap until the production origin and public routes are known. Keep robots rules and deployment access controls distinct: crawler directives are not authentication.

## Documentation and evidence

Link quick start, actual commands, project map, architecture/contracts, privacy, limitations, contribution process, and verification guidance. Keep AGENTS.md specific to the repository's toolchain and invariants. Preserve a single instruction source rather than copying inconsistent rules into every assistant file.

Follow [SCREENSHOTS.md](SCREENSHOTS.md). For any published measurement, link the exact revision, command, fixture, mode, and run artifact. For work summaries, distinguish prepared files, committed files, merged code, deployed behavior, and applied settings.

## Primary references

- [GitHub social preview](https://docs.github.com/en/repositories/managing-your-repositorys-settings-and-features/customizing-your-repository/customizing-your-repositorys-social-media-preview)
- [GitHub topics](https://docs.github.com/en/repositories/managing-your-repositorys-settings-and-features/customizing-your-repository/classifying-your-repository-with-topics)
- [Next.js metadata and images](https://nextjs.org/docs/app/getting-started/metadata-and-og-images)
- [Google SEO starter guide](https://developers.google.com/search/docs/fundamentals/seo-starter-guide)

`llms.txt` is a navigation aid, not an authorization policy or a promise of indexing or ranking. Helpful, accurate documentation and working links take priority over keyword repetition.
