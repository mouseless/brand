This repository contains all resources and usage details about Mouseless brand.
For the original brandkit you can download [brandkit.fig](./brandkit.fig) or
[brandkit.pdf](./brandkit.pdf).

## The Story

We are a software development collective connecting through the craft. We
prioritize our people above all else, promoting open communication and
efficiency. With this philosophy, our collective keeps its focus on its craft
which eventually leads to excellence.

Inspired from this vision, we named our collective as __Mouseless__.

## Usage In Plain Text

Mouseless name should be used in lowercase (`mouseless`) wherever suitable
unless you use it in a formal context or a documentation, like in this
document. Social media profile names should be lowercase as well.

## Logo Construction

Logo consists of three parts, greater than symbol `>`, brand name `mouseless`
or initial `m` and an underscore `_`.

There are;

- three forms: _mark_, _full_, _short_
- three colors for mark: _primary_, _black_ and _white_
- four colors for full and short: _primary_, _secondary_, _black_ and _white_

As a result there are 11 combinations as shown below;

| color \ form  | mark     | full     | short    |
| ---           | ---      | ---      | ---      |
| __primary__   | ![lmp][] | ![lfp][] | ![lsp][] |
| __secondary__ | N/A      | ![lfs][] | ![lss][] |
| __white__     | ![lmw][] | ![lfw][] | ![lsw][] |
| __black__     | ![lmb][] | ![lfb][] | ![lsb][] |

Unlike a regular logo, we prefer dark background over a light one, because the
terminal feel comes from a dark background.

### Logo usage in plain text

When logo is needed in a place where image cannot be included, you may use
`> m_` or `> mouseless_`.

## How to Choose

Among 11 above alternatives it looks hard to choose which one to use. Let's
make it easy.

First of all, every alternative is valid and can be used. There is no
restriction. However, if you use a logo this means you want it to be noticed
and look nice. Below is a list of suggestions to achieve this;

- Prefer _primary_ & _secondary_ logos over _black_ & _white_ wherever possible
- Use _primary_ & _white_ for dark backgrounds, _secondary_ & _black_ for light
  backgrounds
  - When you use _mark_, there is only _primary_ color which might fit both
    light and dark backgrounds.
- Form preference is _full_, then _short_. If none fits well, use _mark_.

Below are some examples;

| Logo on backgrounds                              |
| ---                                              |
| ![](./assets/logo/sample/primary-on-color.png)   |
| ![](./assets/logo/sample/secondary-on-color.png) |
| ![](./assets/logo/sample/white-on-color.png)     |
| ![](./assets/logo/sample/black-on-color.png)     |

### Finding a logo

[assets/logo](./assets/logo) folder includes all of the existing exported
files. All of these exported files are valid and can be used where they fit.
Use `.svg` files where possible, if not, use `.png` files with a suitable size.

#### SVG files

`.svg` files are in [assets/logo/svg](./assets/logo/svg) folder. Below is the
naming convention for svg files;

```
logo-full-primary.svg

logo-[form]-[color].svg
```

#### PNG files

`.png` files are in [assets/logo/png](./assets/logo/png) folder. There are four
folders indicating different sizes named `xs`, `s`, `m` and `l` that are `5px`,
`50px`, `150px` and  `500px` in height respectively.

Below is the naming convention for png files;

```
logo-short-secondary-5px.png
logo-full-black-50px.png

logo-[form]-[color]-[height].png
```

### Exporting a new logo

If existing exported files does not suit your need, you can use
[brandkit.fig](./brandkit.fig) file to export a new one.

> [!NOTE]
>
> Logo is pixel compliant, so you can use a perfect logo even if you have 5
> pixels of height. On the other hand full logo may feel long, so you may use a
> 5x5 mark form or a 17x5 short form.

## Social media

Profile pictures are exported including background so that it can fit better
with social media channels. They come with two colors, primary and secondary,
and three forms, mark, short and terminal.

| color \ form  | mark      | short     | terminal  |
| ---           | ---       | ---       | ---       |
| __primary__   | ![lpmp][] | ![lpsp][] | ![lptp][] |
| __secondary__ | ![lpms][] | ![lpss][] | ![lpts][] |

These exports are in [assets/logo/profile](./assets/logo/profile) folder with
the following naming convention;

```
logo-profile-short-primary.svg
logo-profile-terminal-secondary-500px.png

logo-profile-[form]-[color].svg
logo-profile-[form]-[color]-[height].png
```

### How to Choose

Depending on the platform, you may prefer mark form or short form. If target
platform places brand name on the right side of profile picture, then it is
better to use only mark form, e.g. Github. If profile picture is used stand
alone, then you may consider using short form. Terminal form is there just for
fun, use it if you feel it is suitable.

## Watermarks

Use watermarks to protect and copyright photos and videos online. Watermarks
are exported to [assets/logo/watermark](./assets/logo/watermark) in `15%`,
`22.5%` and `30%` opacities using only black/white colors in all forms.

Below is the naming convention for watermark logos;

```
logo-watermark-full-black-0.15.svg
logo-watermark-short-black-0.225.svg

logo-watermark-[form]-[color]-[opacity].svg
```

> [!WARNING]
>
> Don't use watermarks directly in html, because they are meant to be used on
> existing photos or videos. There are also no `.png` exports available, because
> of the same reason.

## Badges

There are no apparent use cases for badges, but they are prepared anyway.
_primary_ and _secondary_ badges are more suitable for brand related badges,
whereas _black_ and _white_ badges can be used as status badges etc.

| Type        | Badge     |
| ---         | ---       |
| _primary_   | ![lbmp][] |
| _secondary_ | ![lbms][] |
| _white_     | ![lbmw][] |
| _black_     | ![lbmb][] |

## Colors

Primary brand color is `red-500` (![r500][] `#F9465B`). We use it in a minimal
manner, e.g., link and button hover states or selected items.

### Palette

We have 7 colors with 9 grades per color. You may also use regular `black`
(![black][] `#000000`) and `white` (![white][] `#FFFFFF`).

| Name      | 100       | 200       | 300       | 400       | 500       | 600       | 700       | 800       | 900       |
| ---       | ---       | ---       | ---       | ---       | ---       | ---       | ---       | ---       | ---       |
| red       | ![r100][] | ![r200][] | ![r300][] | ![r400][] | ![r500][] | ![r600][] | ![r700][] | ![r800][] | ![r900][] |
| darkgreen | ![d100][] | ![d200][] | ![d300][] | ![d400][] | ![d500][] | ![d600][] | ![d700][] | ![d800][] | ![d900][] |
| yellow    | ![y100][] | ![y200][] | ![y300][] | ![y400][] | ![y500][] | ![y600][] | ![y700][] | ![y800][] | ![y900][] |
| orange    | ![o100][] | ![o200][] | ![o300][] | ![o400][] | ![o500][] | ![o600][] | ![o700][] | ![o800][] | ![o900][] |
| blue      | ![b100][] | ![b200][] | ![b300][] | ![b400][] | ![b500][] | ![b600][] | ![b700][] | ![b800][] | ![b900][] |
| green     | ![g100][] | ![g200][] | ![g300][] | ![g400][] | ![g500][] | ![g600][] | ![g700][] | ![g800][] | ![g900][] |
| gray      | ![a100][] | ![a200][] | ![a300][] | ![a400][] | ![a500][] | ![a600][] | ![a700][] | ![a800][] | ![a900][] |

<details>
<summary>Click to see color codes...</summary>

| Name      | 100     | 200     | 300     | 400     | 500     | 600     | 700     | 800     | 900     |
| ---       | ---     | ---     | ---     | ---     | ---     | ---     | ---     | ---     | ---     |
| red       | #FFEDEC | #FFDAD9 | #FFB3B4 | #FF888D | #FA465B | #DF314A | #BB1134 | #920024 | #680017 |
| darkgreen | #E6EFF0 | #B2CFD1 | #82AEB0 | #507D80 | #3B6F70 | #255759 | #154245 | #092C2E | #031819 |
| yellow    | #FAF8C8 | #FCF8A7 | #FAF478 | #E8E26F | #D9D355 | #BCC45E | #B2AE56 | #8C894D | #666322 |
| orange    | #FFF3D9 | #FFE8B8 | #FFDE99 | #FFD478 | #FFC957 | #D9A941 | #B28930 | #8C6B22 | #664C14 |
| blue      | #E6EFF7 | #BAE0FF | #87C8FF | #54B1FF | #229AFF | #147FD9 | #0C67B2 | #004F91 | #003969 |
| green     | #E2F6F2 | #C1F5E9 | #A3F7E4 | #82F5DA | #61F2D1 | #52D1B4 | #42AD94 | #328A75 | #246657 |
| gray      | #F7F7F7 | #E9EBEB | #D5DBDB | #C4CCCC | #B3BDBD | #8D9494 | #666B6B | #3F4242 | #18191A |

</details>

### Theme - Primary

Primary theme uses ![d900][] `darkgreen-900` for background, ![a400][]
`gray-500` for foreground and ![a400][] `gray-400` for headings.

> [!NOTE]
>
> Use ![d800][] `darkgreen-800` for box backgrounds.

### Theme - Secondary

Primary theme uses ![a100][] `gray-100` for background, ![d900][]
`darkgreen-900` for foreground and ![black][] `black` for headings.

> [!WARNING]
>
> Boxes are styled the same as primary theme.

## CSS Usage

There are three css files to serve as a base for any website that will use this
branding.

- __Default__: `https://brand.mouseless.codes/assets/css/default.css`
- __Primary__: `https://brand.mouseless.codes/assets/css/primary.css`
- __Secondary__: `https://brand.mouseless.codes/assets/css/secondary.css`

> [!NOTE]
>
> Default respects browser theme and uses Primary for dark mode, Secondary for
> light mode.

### Using with TailwindCSS

To use color, spacing or font variables from a tailwind, make use of variable
syntax;

```html
<div
  class="
    bg-(--color-darkgreen-900) color(--color-green-500)
    px-(--space-xs) my-(--space-lg)
    text-(--font-xl)
  "
/>
```

## Inspiration

Mouseless is founded by [Cihan Deniz](https://github.com/cihandeniz) to create a
collective where developers can join and perform their craft with passion.
Without being certain of what this collective may become in the future,
Mouseless brand uses the same color as [GC
Brains](https://github.com/gcbrains/brand#colors) to leave a mark in the brand
hoping to remind its roots and core values to a future mouseless developer.

[lmp]: ./assets/logo/png/s/logo-mark-primary-50px.png
[lmw]: ./assets/logo/png/s/logo-mark-white-50px.png
[lmb]: ./assets/logo/png/s/logo-mark-black-50px.png
[lfp]: ./assets/logo/png/s/logo-full-primary-50px.png
[lfs]: ./assets/logo/png/s/logo-full-secondary-50px.png
[lfw]: ./assets/logo/png/s/logo-full-white-50px.png
[lfb]: ./assets/logo/png/s/logo-full-black-50px.png
[lsp]: ./assets/logo/png/s/logo-short-primary-50px.png
[lss]: ./assets/logo/png/s/logo-short-secondary-50px.png
[lsw]: ./assets/logo/png/s/logo-short-white-50px.png
[lsb]: ./assets/logo/png/s/logo-short-black-50px.png
[lpmp]: ./assets/logo/profile/logo-profile-mark-primary-100px.png
[lpms]: ./assets/logo/profile/logo-profile-mark-secondary-100px.png
[lpsp]: ./assets/logo/profile/logo-profile-short-primary-125px.png
[lpss]: ./assets/logo/profile/logo-profile-short-secondary-125px.png
[lptp]: ./assets/logo/profile/logo-profile-terminal-primary-125px.png
[lpts]: ./assets/logo/profile/logo-profile-terminal-secondary-125px.png

[lbmp]: https://img.shields.io/badge/dynamic/style-mouseless-000000?style=for-the-badge&label=&logo=data:image/svg+xml;base64,PHN2ZyB3aWR0aD0iNTAiIGhlaWdodD0iNTAiIHZpZXdCb3g9IjAgMCA1MCA1MCIgZmlsbD0ibm9uZSIgeG1sbnM9Imh0dHA6Ly93d3cudzMub3JnLzIwMDAvc3ZnIj4KPG1hc2sgaWQ9Im1hc2swXzEwMV8xNTE4IiBzdHlsZT0ibWFzay10eXBlOmFscGhhIiBtYXNrVW5pdHM9InVzZXJTcGFjZU9uVXNlIiB4PSIwIiB5PSIwIiB3aWR0aD0iNTAiIGhlaWdodD0iNTAiPgo8cGF0aCBkPSJNMTAgMEgyMFYxMEgxMFYwWiIgZmlsbD0id2hpdGUiLz4KPHBhdGggZD0iTTIwIDEwSDMwVjIwSDIwVjEwWiIgZmlsbD0id2hpdGUiLz4KPHBhdGggZD0iTTMwIDIwSDQwVjMwSDMwVjIwWiIgZmlsbD0id2hpdGUiLz4KPHBhdGggZD0iTTIwIDMwSDMwVjQwSDIwVjMwWiIgZmlsbD0id2hpdGUiLz4KPHBhdGggZD0iTTEwIDQwSDIwVjUwSDEwVjQwWiIgZmlsbD0id2hpdGUiLz4KPC9tYXNrPgo8ZyBtYXNrPSJ1cmwoI21hc2swXzEwMV8xNTE4KSI+CjxyZWN0IHdpZHRoPSI1MCIgaGVpZ2h0PSI1MCIgZmlsbD0iI0Y5NDY1QiIvPgo8L2c+Cjwvc3ZnPgo=
[lbms]: https://img.shields.io/badge/dynamic/style-mouseless-ffffff?style=for-the-badge&label=&logo=data:image/svg+xml;base64,PHN2ZyB3aWR0aD0iNTAiIGhlaWdodD0iNTAiIHZpZXdCb3g9IjAgMCA1MCA1MCIgZmlsbD0ibm9uZSIgeG1sbnM9Imh0dHA6Ly93d3cudzMub3JnLzIwMDAvc3ZnIj4KPG1hc2sgaWQ9Im1hc2swXzEwMV8xNTE4IiBzdHlsZT0ibWFzay10eXBlOmFscGhhIiBtYXNrVW5pdHM9InVzZXJTcGFjZU9uVXNlIiB4PSIwIiB5PSIwIiB3aWR0aD0iNTAiIGhlaWdodD0iNTAiPgo8cGF0aCBkPSJNMTAgMEgyMFYxMEgxMFYwWiIgZmlsbD0id2hpdGUiLz4KPHBhdGggZD0iTTIwIDEwSDMwVjIwSDIwVjEwWiIgZmlsbD0id2hpdGUiLz4KPHBhdGggZD0iTTMwIDIwSDQwVjMwSDMwVjIwWiIgZmlsbD0id2hpdGUiLz4KPHBhdGggZD0iTTIwIDMwSDMwVjQwSDIwVjMwWiIgZmlsbD0id2hpdGUiLz4KPHBhdGggZD0iTTEwIDQwSDIwVjUwSDEwVjQwWiIgZmlsbD0id2hpdGUiLz4KPC9tYXNrPgo8ZyBtYXNrPSJ1cmwoI21hc2swXzEwMV8xNTE4KSI+CjxyZWN0IHdpZHRoPSI1MCIgaGVpZ2h0PSI1MCIgZmlsbD0iI0Y5NDY1QiIvPgo8L2c+Cjwvc3ZnPgo=
[lbmw]: https://img.shields.io/badge/dynamic/style-mouseless-000000?style=for-the-badge&label=&logo=data:image/svg+xml;base64,PHN2ZyB3aWR0aD0iNTAiIGhlaWdodD0iNTAiIHZpZXdCb3g9IjAgMCA1MCA1MCIgZmlsbD0ibm9uZSIgeG1sbnM9Imh0dHA6Ly93d3cudzMub3JnLzIwMDAvc3ZnIj4KPG1hc2sgaWQ9Im1hc2swXzEwMV8xNTQxIiBzdHlsZT0ibWFzay10eXBlOmFscGhhIiBtYXNrVW5pdHM9InVzZXJTcGFjZU9uVXNlIiB4PSIwIiB5PSIwIiB3aWR0aD0iNTAiIGhlaWdodD0iNTAiPgo8cGF0aCBkPSJNMTAgMEgyMFYxMEgxMFYwWiIgZmlsbD0iYmxhY2siLz4KPHBhdGggZD0iTTIwIDEwSDMwVjIwSDIwVjEwWiIgZmlsbD0iYmxhY2siLz4KPHBhdGggZD0iTTMwIDIwSDQwVjMwSDMwVjIwWiIgZmlsbD0iYmxhY2siLz4KPHBhdGggZD0iTTIwIDMwSDMwVjQwSDIwVjMwWiIgZmlsbD0iYmxhY2siLz4KPHBhdGggZD0iTTEwIDQwSDIwVjUwSDEwVjQwWiIgZmlsbD0iYmxhY2siLz4KPC9tYXNrPgo8ZyBtYXNrPSJ1cmwoI21hc2swXzEwMV8xNTQxKSI+CjxyZWN0IHdpZHRoPSI1MCIgaGVpZ2h0PSI1MCIgZmlsbD0id2hpdGUiLz4KPC9nPgo8L3N2Zz4K
[lbmb]: https://img.shields.io/badge/dynamic/style-mouseless-ffffff?style=for-the-badge&label=&logo=data:image/svg+xml;base64,PHN2ZyB3aWR0aD0iNTAiIGhlaWdodD0iNTAiIHZpZXdCb3g9IjAgMCA1MCA1MCIgZmlsbD0ibm9uZSIgeG1sbnM9Imh0dHA6Ly93d3cudzMub3JnLzIwMDAvc3ZnIj4KPG1hc2sgaWQ9Im1hc2swXzEwMV8xNTM0IiBzdHlsZT0ibWFzay10eXBlOmFscGhhIiBtYXNrVW5pdHM9InVzZXJTcGFjZU9uVXNlIiB4PSIwIiB5PSIwIiB3aWR0aD0iNTAiIGhlaWdodD0iNTAiPgo8cGF0aCBkPSJNMTAgMEgyMFYxMEgxMFYwWiIgZmlsbD0id2hpdGUiLz4KPHBhdGggZD0iTTIwIDEwSDMwVjIwSDIwVjEwWiIgZmlsbD0id2hpdGUiLz4KPHBhdGggZD0iTTMwIDIwSDQwVjMwSDMwVjIwWiIgZmlsbD0id2hpdGUiLz4KPHBhdGggZD0iTTIwIDMwSDMwVjQwSDIwVjMwWiIgZmlsbD0id2hpdGUiLz4KPHBhdGggZD0iTTEwIDQwSDIwVjUwSDEwVjQwWiIgZmlsbD0id2hpdGUiLz4KPC9tYXNrPgo8ZyBtYXNrPSJ1cmwoI21hc2swXzEwMV8xNTM0KSI+CjxyZWN0IHdpZHRoPSI1MCIgaGVpZ2h0PSI1MCIgZmlsbD0iYmxhY2siLz4KPC9nPgo8L3N2Zz4K


[logo-mark]: https://placehold.co/20x20/fa465b/fa465b?text=.

[black]: https://placehold.co/20x20/000000/000000?text=.
[white]: https://placehold.co/20x20/FFFFFF/FFFFFF?text=.

[r100]: https://placehold.co/20x20/FFEDEC/FFEDEC?text=.
[r200]: https://placehold.co/20x20/FFDAD9/FFDAD9?text=.
[r300]: https://placehold.co/20x20/FFB3B4/FFB3B4?text=.
[r400]: https://placehold.co/20x20/FF888D/FF888D?text=.
[r500]: https://placehold.co/20x20/FA465B/FA465B?text=.
[r600]: https://placehold.co/20x20/DF314A/DF314A?text=.
[r700]: https://placehold.co/20x20/BB1134/BB1134?text=.
[r800]: https://placehold.co/20x20/920024/920024?text=.
[r900]: https://placehold.co/20x20/680017/680017?text=.

[d100]: https://placehold.co/20x20/E6EFF0/E6EFF0?text=.
[d200]: https://placehold.co/20x20/B2CFD1/B2CFD1?text=.
[d300]: https://placehold.co/20x20/82AEB0/82AEB0?text=.
[d400]: https://placehold.co/20x20/507D80/507D80?text=.
[d500]: https://placehold.co/20x20/3B6F70/3B6F70?text=.
[d600]: https://placehold.co/20x20/255759/255759?text=.
[d700]: https://placehold.co/20x20/154245/154245?text=.
[d800]: https://placehold.co/20x20/092C2E/092C2E?text=.
[d900]: https://placehold.co/20x20/031819/031819?text=.

[y100]: https://placehold.co/20x20/FAF8C8/FAF8C8?text=.
[y200]: https://placehold.co/20x20/FCF8A7/FCF8A7?text=.
[y300]: https://placehold.co/20x20/FAF478/FAF478?text=.
[y400]: https://placehold.co/20x20/E8E26F/E8E26F?text=.
[y500]: https://placehold.co/20x20/D9D355/D9D355?text=.
[y600]: https://placehold.co/20x20/BCC45E/BCC45E?text=.
[y700]: https://placehold.co/20x20/B2AE56/B2AE56?text=.
[y800]: https://placehold.co/20x20/8C894D/8C894D?text=.
[y900]: https://placehold.co/20x20/666322/666322?text=.

[o100]: https://placehold.co/20x20/FFF3D9/FFF3D9?text=.
[o200]: https://placehold.co/20x20/FFE8B8/FFE8B8?text=.
[o300]: https://placehold.co/20x20/FFDE99/FFDE99?text=.
[o400]: https://placehold.co/20x20/FFD478/FFD478?text=.
[o500]: https://placehold.co/20x20/FFC957/FFC957?text=.
[o600]: https://placehold.co/20x20/D9A941/D9A941?text=.
[o700]: https://placehold.co/20x20/B28930/B28930?text=.
[o800]: https://placehold.co/20x20/8C6B22/8C6B22?text=.
[o900]: https://placehold.co/20x20/664C14/664C14?text=.

[b100]: https://placehold.co/20x20/E6EFF7/E6EFF7?text=.
[b200]: https://placehold.co/20x20/BAE0FF/BAE0FF?text=.
[b300]: https://placehold.co/20x20/87C8FF/87C8FF?text=.
[b400]: https://placehold.co/20x20/54B1FF/54B1FF?text=.
[b500]: https://placehold.co/20x20/229AFF/229AFF?text=.
[b600]: https://placehold.co/20x20/147FD9/147FD9?text=.
[b700]: https://placehold.co/20x20/0C67B2/0C67B2?text=.
[b800]: https://placehold.co/20x20/004F91/004F91?text=.
[b900]: https://placehold.co/20x20/003969/003969?text=.

[g100]: https://placehold.co/20x20/E2F6F2/E2F6F2?text=.
[g200]: https://placehold.co/20x20/C1F5E9/C1F5E9?text=.
[g300]: https://placehold.co/20x20/A3F7E4/A3F7E4?text=.
[g400]: https://placehold.co/20x20/82F5DA/82F5DA?text=.
[g500]: https://placehold.co/20x20/61F2D1/61F2D1?text=.
[g600]: https://placehold.co/20x20/52D1B4/52D1B4?text=.
[g700]: https://placehold.co/20x20/42AD94/42AD94?text=.
[g800]: https://placehold.co/20x20/328A75/328A75?text=.
[g900]: https://placehold.co/20x20/246657/246657?text=.

[a100]: https://placehold.co/20x20/F7F7F7/F7F7F7?text=.
[a200]: https://placehold.co/20x20/E9EBEB/E9EBEB?text=.
[a300]: https://placehold.co/20x20/D5DBDB/D5DBDB?text=.
[a400]: https://placehold.co/20x20/C4CCCC/C4CCCC?text=.
[a500]: https://placehold.co/20x20/B3BDBD/B3BDBD?text=.
[a600]: https://placehold.co/20x20/8D9494/8D9494?text=.
[a700]: https://placehold.co/20x20/666B6B/666B6B?text=.
[a800]: https://placehold.co/20x20/3F4242/3F4242?text=.
[a900]: https://placehold.co/20x20/18191A/18191A?text=.
