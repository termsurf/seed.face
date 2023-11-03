<br/>
<br/>
<br/>
<br/>
<br/>
<br/>
<br/>

<p align='center'>
  <img src='https://github.com/wavebond/seed/blob/make/view/seed.svg?raw=true' height='192'>
</p>

<h3 align='center'>@wavebond/seed.face</h3>
<p align='center'>
  Community Fonts Collection
</p>

<br/>
<br/>
<br/>

## Introduction

The goal of `seed.face` is to collect nice Unicode fonts for open and easy
consumption.

For more related open community data projects, see [`seed`](https://github.com/wavebond/seed).

## Project Structure

The fonts are divided into 2 folders:

1. `import`: This is where the original source font files are stored, so we have a way to get back to the original if the optimization/cleanup process messes anything up.
2. `export`: This is where the optimized/cleaned font files as `.woff2` are stored. They are generated from the import fonts. These are the fonts you should download for your project.

We divide both of these folders into fonts of different scripts (`arabic`, `cuneiform`, etc.) or other categories/groupings (general `unicode` fonts across many scripts, etc.).

All the fonts are stored through Git Large File Storage ([LFS](https://git-lfs.com/)).

## Data Sources

We collect data from a variety of places. Here is a brief overview of some of the data sources we have currently used, but many are from links which no longer work, or from random places which no longer exist.

## Contribute

If you have some structured language data to work with, please
[open an issue or PR](https://github.com/wavebond/seed.face/issues) with a
link to the unicode fonts so we can add
it to the collection. P.S. Make sure the fonts are unicode fonts. There are lots of nice non-unicode fonts (especially in the Devanagari script world, as one example), but we are looking for Unicode fonts so they work out of the box.

## License

As much as possible of this project is released under the **public
domain** (whatever does not already have other licenses). This is
because _this_ "data" (even structured data), legally, can't be "owned",
as it is public knowledge. So we simply make it availble for free.

<p xmlns:dct="http://purl.org/dc/terms/" xmlns:vcard="http://www.w3.org/2001/vcard-rdf/3.0#">
  <em><a rel="license"
     href="http://creativecommons.org/publicdomain/zero/1.0/">
    <img src="http://i.creativecommons.org/p/zero/1.0/88x31.png" style="border-style: none;" alt="CC0" />
  </a>
  <br />
  <br />
  To the extent possible under law,
  <a rel="dct:publisher"
     href="https://github.com/wavebond">
    <span property="dct:title">WaveBond</span></a>
  has waived all copyright and related or neighboring rights to
  <span property="dct:title">seed</span>.
This work is published from the
<span property="vcard:Country" datatype="dct:ISO3166"
      content="US" about="https://github.com/wavebond">
  United States</span>.</em>
</p>

Otherwise, if there are specific datasets which have existing licenses,
like the Chinese
[cedict](https://www.mdbg.net/chinese/dictionary?page=cedict) dataset,
which uses the "Creative Commons Attribution-ShareAlike 4.0
International License", then those datasets are governed by that
license. We will do our best to keep the license data in tact for
projects as we go, but if we make any mistakes or could improve things
in this arena, please reach out and let us know how we can get things
better.

## WaveBond

This is being developed by the folks at [WaveBond](https://wave.bond), a
California-based project for helping humanity master information and
computation. Find us on [Twitter](https://twitter.com/_wavebond),
[LinkedIn](https://www.linkedin.com/company/wavebond), and
[Facebook](https://www.facebook.com/wavebondmind). Check out our other
[GitHub projects](https://github.com/wavebond) as well!
