# MyZx

Let's setup a 48K ZX Spectrum dev environment in GitHub Workspaces - with Dezog 🧮

## Why bother?

Let's make this

- Easy to win

## Open the Dev Environment in GitHub Workspace - right now

### Setup SjASMPlus to run in the workspace

Open the bash terminal and run these step by step:

```bash
unzip tools/sjasmplus.1.18.3.zip -d tools

cd tools/sjasmplus-1.18.3
make clean
make
sudo make install
```

Delete the `tools/sjasmplus-1.18.3` afterwards

TODO:

- Setup so this happens automatically on opening the workspace with a bash script

## Links

Maziac-Dezog

- https://github.com/maziac/DeZog
- https://github.com/maziac/z80-sample-program
- https://github.com/maziac/DeZog/blob/main/documentation/Usage.md
- https://github.com/maziac/DeZog/blob/main/documentation/UnitTests.md
- http://www.breakintoprogram.co.uk/computers/zx-spectrum/assembly-language/z80-development-toolchain

SjASMPlus - make sure you get the right one!

- https://github.com/z00m128/sjasmplus
- https://z00m128.github.io/sjasmplus/documentation.html

Awesome Z80 tutorial links

- https://bobs8bb.wordpress.com/
- https://chuntey.wordpress.com/tag/tutorial/
- https://sol.gfxile.net/z80/index.html
- https://pobtastic.github.io/hobbit/

## Rando Notes

- `F5` works to run the debug
- FIX-ME: Tests require 'Ctrl-Shift-B` to build the "build unit_tests" before the tests are ready; this sucks because I shouldnt need to even know this.
