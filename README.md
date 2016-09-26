# ctags-elm
An Exuberant ctags file for the Elm language.

## Contributions welcome

The `.ctags` file is very basic and currently only recognizes functions.
Contributions are welcome.

## Usage

1. Make sure you have Exuberant Ctags installed (Ubuntu: see exuberant-ctags
   package).
1. Copy the contents of `.ctags` to your ctags file or if you do not have one,
   use `.ctags` itself. See the `ctags` manual page for various locations of
   the `ctag` configuration file.
1. Run `ctags -R src` in your project top-level directory.
   - Assumes that your source code is below `src`.
   - See `ctags` manual for many other options.
1. Use normal editor commands to interact with ctags.
   - **vim** (this is native to vim):
      - `ctrl-]`: jump to definition of function at cursor
      - `ctrl-t`: jump back
1. Run step 3 again for refresh.

## Known issues

See the issues list.
