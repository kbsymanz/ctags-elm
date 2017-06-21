# ctags-elm
An Exuberant ctags file for the Elm language.

## Contributions welcome

The `.ctags` file currently recognizes functions, constants, ports, types, and
type aliases. Contributions are welcome.

## Usage

1. Make sure you have Exuberant Ctags installed (Ubuntu: see exuberant-ctags
   package).
1. Copy the contents of `.ctags` to your ctags file or if you do not have one,
   use `.ctags` itself. See the `ctags` manual page for various locations of
   the `ctag` configuration file.
1. Run `ctags -R src` in your project top-level directory.
   - Assumes that your source code is below `src`.
   - See `ctags` manual for many other options.
      - Another example: `ctags -R --exclude="*.js" .`
1. Use normal editor commands to interact with ctags.
   - **vim**: this is native to vim and there are lots of commands - see
     `:help tags`. Here are three examples.
      - `ctrl-]`: jump to definition of function at cursor
      - `ctrl-t`: jump back
      - `g]`: list matching tags
1. Run step 3 again for refresh. (There are ways to automate this that are
   outside the scope of this project.)

## Known issues

See the issues list.

## Related projects and documentation

- [vim-tagbar-ctags-elm](https://github.com/bitterjug/vim-tagbar-ctags-elm)
has support for Elm in [Vim Tagbar](https://github.com/majutsushi/tagbar) with [Universal
Ctags](https://github.com/universal-ctags/ctags).

- [Vim and Ctags by Andrew Stewart](https://andrew.stwrt.ca/posts/vim-ctags/) describes the use of ctags
