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

Primary brand color is ![logo-mark][] `#F9465B`. We use it in a minimal manner,
e.g., link and button hover states or selected items.

### Palette

We have `black`, `gray` and `white` tones as well as 5 main colors;

| Name      | 100       | 200       | 300       | 400       | 500       | 600       | 700       | 800       | 900       |
| ---       | ---       | ---       | ---       | ---       | ---       | ---       | ---       | ---       | ---       |
| red       | #000000   | #000000   | #000000   | #000000   | #000000   | #000000   | #000000   | #000000   | #000000   |
|           | ![r100][] | ![r200][] | ![r300][] | ![r400][] | ![r500][] | ![r600][] | ![r700][] | ![r800][] | ![r900][] |
| darkgreen | #000000   | #000000   | #000000   | #000000   | #000000   | #000000   | #000000   | #000000   | #000000   |
|           | ![d100][] | ![d200][] | ![d300][] | ![d400][] | ![d500][] | ![d600][] | ![d700][] | ![d800][] | ![d900][] |
| yellow    | #000000   | #000000   | #000000   | #000000   | #000000   | #000000   | #000000   | #000000   | #000000   |
|           | ![y100][] | ![y200][] | ![y300][] | ![y400][] | ![y500][] | ![y600][] | ![y700][] | ![y800][] | ![y900][] |
| orange    | #000000   | #000000   | #000000   | #000000   | #000000   | #000000   | #000000   | #000000   | #000000   |
|           | ![o100][] | ![o200][] | ![o300][] | ![o400][] | ![o500][] | ![o600][] | ![o700][] | ![o800][] | ![o900][] |
| blue      | #000000   | #000000   | #000000   | #000000   | #000000   | #000000   | #000000   | #000000   | #000000   |
|           | ![b100][] | ![b200][] | ![b300][] | ![b400][] | ![b500][] | ![b600][] | ![b700][] | ![b800][] | ![b900][] |
| green     | #000000   | #000000   | #000000   | #000000   | #000000   | #000000   | #000000   | #000000   | #000000   |
|           | ![g100][] | ![g200][] | ![g300][] | ![g400][] | ![g500][] | ![g600][] | ![g700][] | ![g800][] | ![g900][] |
| gray      | #000000   | #000000   | #000000   | #000000   | #000000   | #000000   | #000000   | #000000   | #000000   |
|           | ![a100][] | ![a200][] | ![a300][] | ![a400][] | ![a500][] | ![a600][] | ![a700][] | ![a800][] | ![a900][] |

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

[r100]: https://via.placeholder.com/20/000000/000000?text=+
[r200]: https://via.placeholder.com/20/000000/000000?text=+
[r300]: https://via.placeholder.com/20/000000/000000?text=+
[r400]: https://via.placeholder.com/20/000000/000000?text=+
[r500]: https://via.placeholder.com/20/000000/000000?text=+
[r600]: https://via.placeholder.com/20/000000/000000?text=+
[r700]: https://via.placeholder.com/20/000000/000000?text=+
[r800]: https://via.placeholder.com/20/000000/000000?text=+
[r900]: https://via.placeholder.com/20/000000/000000?text=+

[d100]: https://via.placeholder.com/20/000000/000000?text=+
[d200]: https://via.placeholder.com/20/000000/000000?text=+
[d300]: https://via.placeholder.com/20/000000/000000?text=+
[d400]: https://via.placeholder.com/20/000000/000000?text=+
[d500]: https://via.placeholder.com/20/000000/000000?text=+
[d600]: https://via.placeholder.com/20/000000/000000?text=+
[d700]: https://via.placeholder.com/20/000000/000000?text=+
[d800]: https://via.placeholder.com/20/000000/000000?text=+
[d900]: https://via.placeholder.com/20/000000/000000?text=+

[y100]: https://via.placeholder.com/20/000000/000000?text=+
[y200]: https://via.placeholder.com/20/000000/000000?text=+
[y300]: https://via.placeholder.com/20/000000/000000?text=+
[y400]: https://via.placeholder.com/20/000000/000000?text=+
[y500]: https://via.placeholder.com/20/000000/000000?text=+
[y600]: https://via.placeholder.com/20/000000/000000?text=+
[y700]: https://via.placeholder.com/20/000000/000000?text=+
[y800]: https://via.placeholder.com/20/000000/000000?text=+
[y900]: https://via.placeholder.com/20/000000/000000?text=+

[o100]: https://via.placeholder.com/20/000000/000000?text=+
[o200]: https://via.placeholder.com/20/000000/000000?text=+
[o300]: https://via.placeholder.com/20/000000/000000?text=+
[o400]: https://via.placeholder.com/20/000000/000000?text=+
[o500]: https://via.placeholder.com/20/000000/000000?text=+
[o600]: https://via.placeholder.com/20/000000/000000?text=+
[o700]: https://via.placeholder.com/20/000000/000000?text=+
[o800]: https://via.placeholder.com/20/000000/000000?text=+
[o900]: https://via.placeholder.com/20/000000/000000?text=+

[b100]: https://via.placeholder.com/20/000000/000000?text=+
[b200]: https://via.placeholder.com/20/000000/000000?text=+
[b300]: https://via.placeholder.com/20/000000/000000?text=+
[b400]: https://via.placeholder.com/20/000000/000000?text=+
[b500]: https://via.placeholder.com/20/000000/000000?text=+
[b600]: https://via.placeholder.com/20/000000/000000?text=+
[b700]: https://via.placeholder.com/20/000000/000000?text=+
[b800]: https://via.placeholder.com/20/000000/000000?text=+
[b900]: https://via.placeholder.com/20/000000/000000?text=+

[g100]: https://via.placeholder.com/20/000000/000000?text=+
[g200]: https://via.placeholder.com/20/000000/000000?text=+
[g300]: https://via.placeholder.com/20/000000/000000?text=+
[g400]: https://via.placeholder.com/20/000000/000000?text=+
[g500]: https://via.placeholder.com/20/000000/000000?text=+
[g600]: https://via.placeholder.com/20/000000/000000?text=+
[g700]: https://via.placeholder.com/20/000000/000000?text=+
[g800]: https://via.placeholder.com/20/000000/000000?text=+
[g900]: https://via.placeholder.com/20/000000/000000?text=+

[a100]: https://via.placeholder.com/20/000000/000000?text=+
[a200]: https://via.placeholder.com/20/000000/000000?text=+
[a300]: https://via.placeholder.com/20/000000/000000?text=+
[a400]: https://via.placeholder.com/20/000000/000000?text=+
[a500]: https://via.placeholder.com/20/000000/000000?text=+
[a600]: https://via.placeholder.com/20/000000/000000?text=+
[a700]: https://via.placeholder.com/20/000000/000000?text=+
[a800]: https://via.placeholder.com/20/000000/000000?text=+
[a900]: https://via.placeholder.com/20/000000/000000?text=+
