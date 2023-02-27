---
title: Welcome to Markdoc 👋
---

This simple starter showcases Markdoc's features with Content Collections. All Markdoc features are supported, including this nifty built-in `{% table %}` tag:

{% table %}
* Feature
* Supported
---
* `.mdoc` + `.md` in Content Collections
* ✅
---
* Markdoc transform configuration
* ✅
---
* Astro components
* ✅
{% /table %}

{% aside title="Code Challenge" type="tip" %}

Reveal the secret message below by adding `revealSecret: true` to your list of Markdoc variables.

_Hint: Try [adding a `variables` object](https://markdoc.dev/docs/variables#global-variables) to the `config` property under `src/components/DocsContent.astro`._

{% if $revealSecret %}

Maybe the real secret was the Rick Rolls we shared along the way.

![Rick Astley dancing](https://media.tenor.com/x8v1oNUOmg4AAAAM/rickroll-roll.gif)

{% /if %}

{% /aside %}

Check out [the `@astrojs/markdoc` integration][astro-markdoc] for complete documentation and usage examples.

[astro-markdoc]: https://docs.astro.build/en/guides/integrations-guide/markdoc/
