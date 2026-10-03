# AGENTS.md

- The keymap targets programming and Neovim/LazyVim inside Ghostty. Symbol symmetry is a semantic or mnemonic aid, not an end in itself.
- For the user's layout, edit `config/totem.keymap`. `config/boards/shields/totem/totem.keymap` is an independent shield fallback, not a copy to synchronize.
- Original modifier sides and nesting are part of the user's Ghostty compatibility requirements. Preserve them when moving bindings; apparently equivalent left/right modifier combinations are not safe substitutes.
- In the user's confirmed host layout, `&kp RA(E)` is the acute-accent binding (`´`), while `&kp LS(RA(N2))` produces `€`. These meanings are host-specific, not inferable from ZMK keycodes alone.
- Keep keymap syntax compatible with Nick Coutsos's Keymap Editor, the user's graphical editing workflow. Enabled ZMK Studio support does not establish that the keyboard has Studio-persisted keymap changes.
