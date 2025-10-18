# baz treesitter

## summary 
```
tree-sitter generate
tree-sitter build
mv baz.so ~/.local/share/nvim/site/parser
mkdir -p ~/.local/share/nvim/site/queries/baz
cp queries/baz/highlights.scm ~/.local/share/nvim/site/queries/baz/
:: pwd
/home/c/.config/nvim/lua/plugins
 :: p treesitter-baz.lua 
return {
  {
    "nvim-treesitter/nvim-treesitter",
    opts = {
      ensure_installed = { "baz" },
    },
  },
}

``