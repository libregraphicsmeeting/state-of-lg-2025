# Google Fonts

Google Fonts has commissioned 1,000s of libre font projects, and supports many libre software projects at all levels of the text stack.

Further links:
- Website: <https://fonts.google.com>
- Development Blog: <https://fonts.googleblog.com>
- Discussion: <https://github.com/google/fonts/issues>
- Code: <https://https://github.com/googlefonts>
- Slide 1
  - <https://developer.chrome.com/blog/memory-safety-fonts>
  - <https://github.com/googlefonts/oxidize>
- Slide 2
  - <https://fonts.google.com/?sort=date>
- Slide 3
  - <https://github.com/harfbuzz/boring-expansion-spec>
  - <https://github.com/Lorp/fencer>
  - <https://github.com/googlefonts/roboto-delta>
  - <https://github.com/googlefonts/amstelvar-avar2>
  - <https://github.com/harfbuzz/harfbuzz-wasm-examples>

---

## Slide 1 - New Rust Text Stack

![New Rust Text Stack](google-fonts-lgm-2025-slide-1.jpg)

Speakers Notes:

Billions of Chrome users now experience safer web fonts, due to a new complete font stack in Rust that is being developed by the Google Fonts team.
Before Chrome used FreeType to deliver high quality results, but had a stream of fuzzer issues and FreeType has had many known exploits, including one found by Google Project Zero in 2020.
Now, Skrifa is replacing FreeType, and the first piece launched without any glitches – and Rust means, without any similar security issues too.

Google Fonts folks encourage all libre graphics projects to consider adopting the new Rust text stack, and doing a similar “oxidize” effort to reap the same rewards.

You can read more on the Chrome Developer blog and the Google Fonts oxidize github repo.

---

## Slide 2 - New Libre Fonts

![New Libre Fonts](google-fonts-lgm-2025-slide-2.jpg)

Speakers Notes:

After 15 years, Google Fonts has now published thousands of libre font projects, and here are some of the most interesting recent ones.
There's too many to mention, but the Playpen and Playwrite fonts are special because they are a huge set of libre fonts to help kids learn to read and write.

You can sort the Google Fonts website by the newest releases to browse them easily.

---

## Slide 3 - New ‘Boring’ Font Format + WASM Fonts

![New Boring Font Format](google-fonts-lgm-2025-slide-3.jpg)

About two years ago, Harbuzz developer Behdad Esfahbod started the "boring expansion spec" project, that has nearly completed the MPEG Open Font Format standardization process thanks to help from GIMP developer Liam Quin.
There are 4 major updates to the font format here, and the most interesting is version two of the avar table. 
Laurence Penney has made a nice libre web tool for authoring avar 2 data, called The Fencer.
This table backs the visionary work by David Berlow and his team on two new fonts, that are a quarter of the file size compared to their previous avar 1 versions, Roboto Delta and Amstelvar.

But incremental updates to the font format are ultimately kind of boring, and the most exciting work by Behdad has been to add a WASM shaper to Harfbuzz.
No other text stack has implemented this yet, but the Harfbuzz github has an examples repo with many wonderful explorations.
