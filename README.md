The maintainer of the [original repo](https://github.com/eoh-bse/minintro.nvim)
was not interested in
[fixing this plugin](https://github.com/eoh-bse/minintro.nvim/pull/13) nor
[accepting pull requests](https://github.com/eoh-bse/minintro.nvim/pull/14).

# nullromo/minintro.nvim

If you just want a simple and lightweight startup intro that works, this plugin
is for you.

## Screenshot

![minintro-screenshot](screenshots/screenshot.png)

## Installation/Configuration

```lua
-- Lazy
{
    "nullromo/minintro.nvim",
    config = function()
        require('minintro').setup({ color = '#2D4F67' })
    end,
}
```
