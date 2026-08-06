# front-ed-css

> Biblioteca CSS para uso pessoal de Ed Robert

## INFO

`.front-ed.css` é uma biblioteca para uso pessoal que busca consistência, escalabilidade e fácil manutenção.

- Organização de arquivos: ITCSS
- Metodologia para classes: OOCSS
- Estratégia de desenvolvimento: Atomic Design
- Foco: Mobile first

## Build

- `./css/config.css`
- `./css/front-ed.css`

## Biblioteca

`<wip> <!-- work in progress... -->`

### Settings - Global variables, config switches
- [x] Variables (config.css)
- [x] Color palette
- [x] Tipografia

### Generic - Ground-zero styles (3rd party, reset, normalize)
- [x] Reset

### Elements - Bare elements (unclassed HTML / type selectors)
- [x] Basic HTML
  - body, h1, h2, h3, h4, h5, h6, hr, html, p
- [x] Semantic sectioning
  - address
  - not [article, aside, footer, header, hgroup, main, nav, search, section]
- [x] Text blocks
  - blockquote
  - not [div, pre]
- [x] Interactive elements
  - dialog
  - not [details, summary]
- [x] Semantic inline text
  - a, b, code, del, em, i, ins, kbd, mark, small, strong, sub, sup
  - not [abbr, bdi, bdo, br, cite, data, dfn, q, rp, rt, ruby, s, samp, span, time, u, var, wbr]
- [x] Lists
  - dd, dl, dt, li, menu, ol, ul
- [x] Tables
  - caption, table, tbody, td, tfoot, th, thead, tr
  - not [col, colgroup]
- [x] Images
  - figcaption, figure, img, picture, svg
- [x] Audio and Video
  - audio, video
- [x] Embedded
  - iframe
  - not [embed, object]
- [x] Scripting
  - canvas, noscript
- [x] Buttons
  - button
- [x] Forms
  - fieldset, form, input, label, legend, output, select, textarea
  - not [datalist, optgroup, option]
- [ ] Progress bars
  - meter, progress

### Objects - Layout classes, cosmetic-free design patterns
- [x] Basic HTML
- [x] Semantic sectioning
- [x] Text blocks
- [x] Interactive elements
- [x] Semantic inline text
- [x] Lists
- [x] Tables
- [x] Images
- [x] Audio and Video
- [x] Embedded
- [x] Scripting
- [x] Buttons
- [x] Forms - sem formatação adicional (apenas formatação de bare elements)
- [ ] Progress bars

### Components - UI Classes, designed components, chunks of UI
- [ ] Wireframes
- [x] Containers
- [x] Grid layout
- [x] Flexbox
- [x] Headers and footers
- [x] Banners
- [x] Branding
- [x] Avatars (personal avatar)
- [x] Dropdown button
- [x] Toolbars (app bar, sticky bar)
- [x] Menus (nav bar)
- [ ] Menus (nav menu)

- [ ] Cards

- [x] Icons (Ionicon - external lib)
- [x] Messages (text messages, notice blocks)
- [x] Tagging (tags, badges, pills and chips)
- [ ] Tooltips
- [x] Loaders and spinners
- [x] Navigation (breadcrumbs, pagination)

- [ ] Steppers
- [ ] Timeline

- [ ] Alerts (alerts, toasts and notify)
- [ ] Modals and popovers

- [ ] Collapsible
- [ ] Accordion
- [ ] Drawers

- [ ] Tabs and tab panels
- [ ] Carousel
- [ ] Gallery

- [ ] Form components (toggle, button toggle, slider, range)
- [ ] Dashboards (bars, donuts, lines, piechart, ...)
- [ ] Parallax

### Utilities - IDs and !important, helpers and overrides
- [ ] Breakpoints and responsive design
- [x] Color utils (color palette, borders, backgrounds and colors)
- [ ] Color utils (gradients)
- [x] Text utils (modificadores de texto, text columns)
- [x] Spacing
- [x] Borders (radius and lines)
- [x] Elevation (box shadows)
- [ ] Elevation (text shadows)
- [ ] Opacity
- [ ] Filters
- [x] Animations (blink, pulse, rotate, spin)
- [ ] Transitions
- [ ] States (hover, focus, ...)
- [ ] Theme (light / dark mode)
- [ ] Helper classes
- [x] CSS linter
  - atributos obrigatórios ou recomendados em tags
  - tags e atributos marcados com status deprecated


---
Desenvolvido por [Ed Robert](https://ednilsonrobert.github.io/).
