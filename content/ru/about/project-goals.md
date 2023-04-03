---
name: Project Goals
permalink: '/about/project-goals'
description: "Read more about Preact's project goals"
---

# Цели Preact

## Цели

Preact направлен на достижение нескольких ключевых целей:

- **Производительность:** Render quickly & efficiently
- **Размер:** Small size, lightweight _(approximately 3.5 kB)_
- **Эффективность:** Effective memory usage _(avoiding GC thrash)_
- **Понятность:** Understanding the codebase should take no more than a few hours
- **Совместимость:** Preact aims to be _largely compatible_ with the React API. [preact/compat] attempts to achieve as much compatibility with React as possible.

## Non-Goals

Some React features are intentionally omitted from Preact, either because they are not achievable while meeting the primary project goals listed above or because they don't fit within the scope of Preact's core set of functionality.

The intentional items under [Differences to React](/guide/v10/differences-to-react):
- `PropTypes`, which are easily used as a separate library
- `Children`, can be replaced with native arrays
- `Synthetic Events`, since Preact does not attempt to patch issues in older browsers like IE8

[preact/compat]: /guide/v10/switching-to-preact