# Mouseless Brand

This repository contains all resources and usage details about Mouseless brand.
For the original brandkit you can download [brandkit.fig](./brandkit.fig) or
[brandkit.pdf](./brandkit.pdf).

## The Story

We are a software development studio centered around its experts who are
dedicated to seek perfection in their work. We work slow but sure. And we see
"what" as value for our customers and "how" as value for the studio.

Inspired from this vision, we named our studio as __Mouseless__.

Our intention is to make everyone in the team use their mouse less, and
preferably become a mouseless developer.

## Usage In Plain Text

Mouseless name should be used in lowercase (`mouseless`) wherever suitable
unless you use it in a formal context or a documentation, like in this
document. Social media profile names should be lowercase as well.

## Logo Construction

Logo consists of three parts, gt symbol `>`, brand name `mouseless` or initial
`m` and an underscore `_`.

There are;

- three forms: _mark_, _logo full_, _logo short_
- three colors for mark: _primary_, _black_ and _white_
- four colors for logo: _primary_, _secondary_, _black_ and _white_

As a result there are 11 combinations as shown below;

| color \ form  | mark     | full     | short    |
| ---           | ---      | ---      | ---      |
| __primary__   | ![lpm][] | ![lpf][] | ![lps][] |
| __secondary__ | N/A      | ![lsf][] | ![lss][] |
| __black__     | ![lbm][] | ![lbf][] | ![lbs][] |
| __white__     | ![lwm][] | ![lwf][] | ![lws][] |

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
- Use _primary_ & _black_ for light backgrounds, _secondary_ & _white_ for dark
  backgrounds
  - When you use _mark_, there is only _primary_ color which might fit dark
    backgrounds as well.
- Form preference is _full_, then _short_. If none fits well, use _mark_.

Below are some examples;

| Logo on backgrounds                 |
| ---                                 |
| ![](./.files/primary-on-light.png)  |
| ![](./.files/secondary-on-dark.png) |
| ![](./.files/black-on-light.png)    |
| ![](./.files/white-on-dark.png)     |

### Finding a logo

[assets/logo](./assets/logo) folder includes all of the existing exported
files. All of these exported files are valid and can be used where they fit.
Use `.svg` files where possible, if not, use `.png` files with a suitable size.

#### SVG files

`.svg` files are in [assets/logo/svg](./assets/logo/svg) folder. Below is the
naming convention for svg files;

```
logo-primary-full.svg

logo-[color]-[form].svg
```

#### PNG files

`.png` files are in [assets/logo/png](./assets/logo/png) folder. There are four
folders indicating different sizes named `xs`, `s`, `m` and `l`.

Below is the naming convention for png files;

```
logo-secondary-short-5px.png
logo-black-full-30px.png

logo-[color]-[form]-[height].png
```

### Exporting a new logo

If existing exported files does not suit your need, you can use
[brandkit.fig](./brandkit.fig) file to export a new one.

> ℹ️  Logo is pixel compliant, so you can use a perfect logo even if you have 5
> pixels of height. On the other hand full logo may feel long, so you may use a
> 5x5 mark form or a 17x5 short form.

## Watermarks

Use watermarks to protect and copyright photos and videos online. Watermarks
are exported to [assets/logo/svg/watermark](./assets/logo/svg/watermark) in
`15%`, `22.5%` and `30%` opacities using only black/white colors in all
forms.

e.g. `logo-black-full-0.15.svg` is black full logo in 15% opacity.

> ⚠️  Don't use watermarks directly in html, because they are meant to be used
> on existing photos or videos. There are also no `.png` exports available,
> because of the same reason.


[lpm]: ./assets/logo/png/s/logo-primary-mark-30px.png
[lpf]: ./assets/logo/png/s/logo-primary-full-30px.png
[lps]: ./assets/logo/png/s/logo-primary-short-30px.png
[lsf]: ./assets/logo/png/s/logo-secondary-full-30px.png
[lss]: ./assets/logo/png/s/logo-secondary-short-30px.png
[lbm]: ./assets/logo/png/s/logo-black-mark-30px.png
[lbf]: ./assets/logo/png/s/logo-black-full-30px.png
[lbs]: ./assets/logo/png/s/logo-black-short-30px.png
[lwm]: ./assets/logo/png/s/logo-white-mark-30px.png
[lwf]: ./assets/logo/png/s/logo-white-full-30px.png
[lws]: ./assets/logo/png/s/logo-white-short-30px.png
