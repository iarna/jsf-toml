## TOML Highlighting For `joe`

You can find here syntax highlighting for the editor joe for TOML files.

To make use of this place `toml.jsf` in your `$PREFIX/share/joe/syntax`
directory and add the contents of `ftyperc` to your larger `ftyperc` file.

This provides full syntax highlighting and error marking for most of TOML syntax
including nested objects and arrays.

This does not as yet fully parse numbers & dates and as such, it will
highlight as valid invalid constructions.
