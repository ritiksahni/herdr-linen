# Built-in mod dependencies

Linen uses Herdr's installed workspace panels; it has no custom mod code.

| Mod | Role |
| --- | --- |
| `workspace-chrome` | Brand, sidebar controls, settings and machine footer |
| `spaces` | Spaces and machine list |
| `agents` | Live agent list and status grouping |
| `tabs` | Tab strip and its standard menus |
| `pane` | Terminal pane headers |
| `files` | Optional file browser |
| `changes` | Optional git changes panel |
| `workspace-status` | Bottom status bar |

These mods and their standard helper menus/icons ship with Herdr desktop 0.1.10. Reuse them from the destination Herdr installation. Do not overwrite them with copies from another installation. If the built-in layout contract changes, follow `RECIPE.md` to adapt Linen to the new standard layout.
