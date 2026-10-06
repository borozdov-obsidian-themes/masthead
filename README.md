# Borozdov Masthead

A theme from the Borozdov collection. Two faces — light **Bristol**, a premium magazine
spread on warm cream, and dark **Espresso**, the same spread after the lights go down. A
sharp serif display, an espresso masthead over the tabs, square white cards and orange
strokes only.

![Borozdov Masthead in light mode](https://raw.githubusercontent.com/borozdov-obsidian-themes/masthead/main/screenshots/light.png)

![Borozdov Masthead in dark mode](https://raw.githubusercontent.com/borozdov-obsidian-themes/masthead/main/screenshots/dark.png)

## Principles

- **An espresso masthead.** Every tab strip is a dark espresso bar; the active tab of a note
  is cut out of it in the colour of the page.
- **A sharp serif at display sizes.** Masthead Serif, never bold, for the title, the three
  largest headings, callout titles and pull quotes; the platform's grotesque for everything
  else.
- **Orange outlines, never fills.** Highlighter orange draws the plain note, quote rules and
  the edge of the open file; links are a deeper burnt orange; ink fills the main button and
  a checked task.
- **Square and flat.** Square white cards with hairline edges, 2px corners on what you
  press, no shadows on the page.

## Features

- Light and dark modes, following Settings → Appearance → Base color scheme
- A dark masthead over every tab strip, with the active tab cut out in the page colour
- Callouts as square cards outlined in the type's colour, with a serif title
- Pull quotes in the serif, a size up, beside an orange rule
- Tags as square white labels that outline in orange under the pointer
- Quiet editing: no focus ring around the note, its title or form fields while you type;
  property names read as labels, not boxed fields
- Text colours meet WCAG contrast on both faces
- The phone layout keeps the same colours and shapes
- No `!important`: every rule can be overridden with a CSS snippet

## Installation

**From the community directory, as a variant:** this theme ships inside **Borozdov
Ember**. Install Borozdov Ember under Settings → Appearance → Themes → Manage, then the
[Style Settings](https://github.com/mgmeyers/obsidian-style-settings) plugin, and choose
**Masthead** under Style Settings → Borozdov Ember → Variant. The variant brings this
theme's palette, type and corners; its own layout, and its embedded font if it has one,
come with the full theme below.

**The full theme, by hand:** download `manifest.json` and `theme.css` from the [latest
release](https://github.com/borozdov-obsidian-themes/masthead/releases/latest) into
`<vault>/.obsidian/themes/Borozdov Masthead/`, then choose Borozdov Masthead under Settings
→ Appearance → Themes.

## Font

Masthead Serif is embedded in `theme.css` as base64 WOFF2 under the SIL Open Font License
1.1 — see [`fonts/OFL.txt`](fonts/OFL.txt). It is a Latin and Cyrillic subset of Heuristica
(© 2008–2012 Andrey V. Panov, based on Adobe's Utopia), renamed because a modified copy may
not use the original's Reserved Font Name. One weight, for the title, the three largest
headings, callout titles and pull quotes.

## License

MIT — see [LICENSE](LICENSE).

---

**По-русски.** Тема из коллекции Borozdov. Два лика: светлый «Бристоль» — разворот
премиального журнала на тёплой кремовой бумаге, и тёмный «Эспрессо» — тот же разворот, когда
гаснет свет. Кофейная шапка над вкладками, чёткая антиква в заголовках (Masthead Serif на
основе Heuristica), квадратные белые карточки и только оранжевые штрихи. В каталоге тема живёт вариантом Borozdov Ember: установите Borozdov Ember и плагин Style Settings, затем выберите Masthead в Style Settings → Borozdov Ember → Variant. Целиком, со своей вёрсткой, тема ставится вручную из последнего релиза репозитория.
