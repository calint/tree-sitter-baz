# baz treesitter

```
-- In ~/.config/nvim/lua/plugins/baz-treesitter.lua
{
  'calint/baz-treesitter',
  name = 'tree-sitter-baz',
  build = ':Telescope help tags',
},

{
  'nvim-treesitter/nvim-treesitter',
  opts = function(_, opts)
    table.insert(opts.ensure_installed, 'baz')
  end,
}
```