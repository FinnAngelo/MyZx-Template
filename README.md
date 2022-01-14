# MyZx

Let's setup a 48K ZX Spectrum dev environment in GitHub Workspaces - with Dezog 🧮

## Why bother?

Let's make this

- Easy to win

## Open the Dev Environment in GitHub Workspace - right now

TODO: 

1. Document the 'open this in GitHub Workspaces' better - inc screenshots
2. Make a 'SjASMPlus Setup' task
3. Find out why 'Run unit tests' doesnt automatically build

### Setup SjASMPlus to run in the workspace

Currently the workspace (i.e. linux docker) setup of the SjASMPlus compiler is a manual task.  
If you pull this repo to a Windows desktop, it should just run because the Windows exe is already in the tools folder.

1. Open the bash terminal and run these step by step:
  ```bash
  unzip tools/sjasmplus.1.18.3.zip -d tools

  cd tools/sjasmplus-1.18.3
  make clean
  make
  sudo make install
  ```
2. Delete the `tools/sjasmplus-1.18.3` afterwards

### Run

- Build with `Ctrl-Shipt-B`
- Debug with `Ctrl-Shift-D` or `F5`
- Currently you need to build and _then_ run the unit tests

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
