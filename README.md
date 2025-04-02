# repl.nvim

## installation

use your favorite plugin manager, for example: [nvim-plug](https://github.com/wsdjeg/nvim-plug)

```lua
require('plug').add({
  {
    'wsdjeg/repl.nvim',
    config = function()
      require('repl').setup({
        executables = {
          lua = 'lua',
        },
      })
    end,
  },
})
```
