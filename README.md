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

> ℹ️  Logo is pixel compliant, so you can use a perfect logo even if you have 5
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

Primary brand color is ![r500][] `#F9465B`. We use it in a minimal manner, e.g.,
link and button hover states or selected items.

### Palette

We have `black`, `gray` and `white` tones as well as 5 main colors;

| Name      | 100              | 200              | 300              | 400              | 500              | 600              | 700              | 800              | 900              |
| ---       | ---              | ---              | ---              | ---              | ---              | ---              | ---              | ---              | ---              |
| red       | ![#FFEDEC][r100] | ![#FFDAD9][r200] | ![#FFB3B4][r300] | ![#FF888D][r400] | ![#FA465B][r500] | ![#DF314A][r600] | ![#BB1134][r700] | ![#920024][r800] | ![#680017][r900] |
| darkgreen | ![#E6EFF0][d100] | ![#B2CFD1][d200] | ![#82AEB0][d300] | ![#507D80][d400] | ![#3B6F70][d500] | ![#255759][d600] | ![#154245][d700] | ![#092C2E][d800] | ![#031819][d900] |
| yellow    | ![#FAF8C8][y100] | ![#FCF8A7][y200] | ![#FAF478][y300] | ![#E8E26F][y400] | ![#D9D355][y500] | ![#BCC45E][y600] | ![#B2AE56][y700] | ![#8C894D][y800] | ![#666322][y900] |
| orange    | ![#FFF3D9][o100] | ![#FFE8B8][o200] | ![#FFDE99][o300] | ![#FFD478][o400] | ![#FFC957][o500] | ![#D9A941][o600] | ![#B28930][o700] | ![#8C6B22][o800] | ![#664C14][o900] |
| blue      | ![#E6EFF7][b100] | ![#BAE0FF][b200] | ![#87C8FF][b300] | ![#54B1FF][b400] | ![#229AFF][b500] | ![#147FD9][b600] | ![#0C67B2][b700] | ![#004F91][b800] | ![#003969][b900] |
| green     | ![#E2F6F2][g100] | ![#C1F5E9][g200] | ![#A3F7E4][g300] | ![#82F5DA][g400] | ![#61F2D1][g500] | ![#52D1B4][g600] | ![#42AD94][g700] | ![#328A75][g800] | ![#246657][g900] |
| gray      | ![#F7F7F7][a100] | ![#E9EBEB][a200] | ![#D5DBDB][a300] | ![#C4CCCC][a400] | ![#B3BDBD][a500] | ![#8D9494][a600] | ![#666B6B][a700] | ![#3F4242][a800] | ![#18191A][a900] |

### Theme - Primary

Primary theme uses ![black][] `black` for background, ![gray][] `gray` for
foreground and ![white-lightest][] `white-lightest` for headings.

Box radius is `30px` and background is ![black-lighter][] `black-lighter`.

### Theme - Secondary

Primary theme uses ![white][] `white` for background, ![black][] `black` for
foreground and ![black-lightest][] `black-lightest` for headings.

Boxes are styled the same for this theme. So box radius is `30px` and background
is ![black-lighter][] `black-lighter`.

### Inspiration

Mouseless is founded by [Cihan Deniz](https://github.com/cihandeniz) to create
a collective where developers can join and perform their craft with passion.
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


[logo-mark]: https://via.placeholder.com/20/fa465b/000000?text=+

[black]: https://via.placeholder.com/20/000000/000000?text=+
[white]: https://via.placeholder.com/20/FFFFFF/000000?text=+

[r100]: https://via.placeholder.com/20/FFEDEC/000000?text=+
[r200]: https://via.placeholder.com/20/FFDAD9/000000?text=+
[r300]: https://via.placeholder.com/20/FFB3B4/000000?text=+
[r400]: https://via.placeholder.com/20/FF888D/000000?text=+
[r500]: https://via.placeholder.com/20/FA465B/000000?text=+
[r600]: https://via.placeholder.com/20/DF314A/000000?text=+
[r700]: https://via.placeholder.com/20/BB1134/000000?text=+
[r800]: https://via.placeholder.com/20/920024/000000?text=+
[r900]: https://via.placeholder.com/20/680017/000000?text=+

[d100]: https://via.placeholder.com/20/E6EFF0/000000?text=+
[d200]: https://via.placeholder.com/20/B2CFD1/000000?text=+
[d300]: https://via.placeholder.com/20/82AEB0/000000?text=+
[d400]: https://via.placeholder.com/20/507D80/000000?text=+
[d500]: https://via.placeholder.com/20/3B6F70/000000?text=+
[d600]: https://via.placeholder.com/20/255759/000000?text=+
[d700]: https://via.placeholder.com/20/154245/000000?text=+
[d800]: https://via.placeholder.com/20/092C2E/000000?text=+
[d900]: https://via.placeholder.com/20/031819/000000?text=+

[y100]: https://via.placeholder.com/20/FAF8C8/000000?text=+
[y200]: https://via.placeholder.com/20/FCF8A7/000000?text=+
[y300]: https://via.placeholder.com/20/FAF478/000000?text=+
[y400]: https://via.placeholder.com/20/E8E26F/000000?text=+
[y500]: https://via.placeholder.com/20/D9D355/000000?text=+
[y600]: https://via.placeholder.com/20/BCC45E/000000?text=+
[y700]: https://via.placeholder.com/20/B2AE56/000000?text=+
[y800]: https://via.placeholder.com/20/8C894D/000000?text=+
[y900]: https://via.placeholder.com/20/666322/000000?text=+

[o100]: https://via.placeholder.com/20/FFF3D9/000000?text=+
[o200]: https://via.placeholder.com/20/FFE8B8/000000?text=+
[o300]: https://via.placeholder.com/20/FFDE99/000000?text=+
[o400]: https://via.placeholder.com/20/FFD478/000000?text=+
[o500]: https://via.placeholder.com/20/FFC957/000000?text=+
[o600]: https://via.placeholder.com/20/D9A941/000000?text=+
[o700]: https://via.placeholder.com/20/B28930/000000?text=+
[o800]: https://via.placeholder.com/20/8C6B22/000000?text=+
[o900]: https://via.placeholder.com/20/664C14/000000?text=+

[b100]: https://via.placeholder.com/20/E6EFF7/000000?text=+
[b200]: https://via.placeholder.com/20/BAE0FF/000000?text=+
[b300]: https://via.placeholder.com/20/87C8FF/000000?text=+
[b400]: https://via.placeholder.com/20/54B1FF/000000?text=+
[b500]: https://via.placeholder.com/20/229AFF/000000?text=+
[b600]: https://via.placeholder.com/20/147FD9/000000?text=+
[b700]: https://via.placeholder.com/20/0C67B2/000000?text=+
[b800]: https://via.placeholder.com/20/004F91/000000?text=+
[b900]: https://via.placeholder.com/20/003969/000000?text=+

[g100]: https://via.placeholder.com/20/E2F6F2/000000?text=+
[g200]: https://via.placeholder.com/20/C1F5E9/000000?text=+
[g300]: https://via.placeholder.com/20/A3F7E4/000000?text=+
[g400]: https://via.placeholder.com/20/82F5DA/000000?text=+
[g500]: https://via.placeholder.com/20/61F2D1/000000?text=+
[g600]: https://via.placeholder.com/20/52D1B4/000000?text=+
[g700]: https://via.placeholder.com/20/42AD94/000000?text=+
[g800]: https://via.placeholder.com/20/328A75/000000?text=+
[g900]: https://via.placeholder.com/20/246657/000000?text=+

[a100]: https://via.placeholder.com/20/F7F7F7/000000?text=+
[a200]: https://via.placeholder.com/20/E9EBEB/000000?text=+
[a300]: https://via.placeholder.com/20/D5DBDB/000000?text=+
[a400]: https://via.placeholder.com/20/C4CCCC/000000?text=+
[a500]: https://via.placeholder.com/20/B3BDBD/000000?text=+
[a600]: https://via.placeholder.com/20/8D9494/000000?text=+
[a700]: https://via.placeholder.com/20/666B6B/000000?text=+
[a800]: https://via.placeholder.com/20/3F4242/000000?text=+
[a900]: https://via.placeholder.com/20/18191A/000000?text=+
