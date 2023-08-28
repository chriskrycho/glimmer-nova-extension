<!--
🎈 Include a brief description of the features your syntax extension provides. For example:
-->

Syntax highlighting and autocompletion for Glimmer templates as used in [Glimmer.js][glimmer] and [Ember.js][ember], powered by [tree-sitter][tsg] and [Glint][glint].

[glimmer]: https://glimmerjs.com
[ember]: https://emberjs.com
[tsg]: https://alexlafroscia.github.io/tree-sitter-glimmer/
[glint]: https://github.com/typed-ember/glint

<!-- TODO: gif/apng showing syntax highlighting -->
<!-- TODO: gif/apng showing Glint integration -->

## Features/Roadmap



This currently has *zero* support for *anything*, because I just started it. The roadmap, however, is pretty straightforward:

- [ ] Support syntax highlighting for both “normal” Handlebars and  GlimmerJS/GlimmerTS (`<template>`) via [the tree-sitter grammar][tsg].
- [ ] Integrate [Glint][glint] for type checking, completions, go-to-def, issue reporting, etc.
