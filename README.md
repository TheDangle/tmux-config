# My Custom Tmux Theme

A personal, dark, and colorful theme for Tmux, designed to be easy on the eyes and enhance productivity.

This theme uses colors from the Kanagawa colortheme with a warm, earthy aesthetic, inspired by autumnal colors.
Note - I am not using all the colors!

## Features

- **Dark, low-contrast background** to reduce eye strain.
- **Vibrant accent colors** to highlight the active window and pane.
- **Clear separation** between the status line and the main terminal pane.
- **Easy to customize** with named colors.

## Clone the Repo
```
git clone https://github.com/TheDangle/tmux-config.git
```
Clone the repo into your '~/.' directory

**Reload Tmux.**
    If you are in a Tmux session, you can apply the changes without restarting it. Press your prefix key (`Ctrl` + `b` by default), then type `:source-file ~/.tmux.conf` and press `Enter`.

## Color Palette

This theme uses a carefully selected palette of colors for a cohesive look.

| Color Name      | Hex Code    | Usage                                  |
| --------------- | ----------- | -------------------------------------- |
| `sumiInk0_bg`   | `#16161d`   | **Background** (set in your terminal)  |
| `oldwhite_fg`   | `#c8c093`   | **Foreground** (set in your terminal)  |
| `autumnRed`     | `#C34043`   | Left status text                       |
| `autumnYellow`  | `#DCA561`   | Active window status text              |
| `dragonBlue`    | `#658594`   | Inactive window text                   |
| `sumiInk3`      | `#363646`   | Active window & Left/Right background  |

## Recommended Terminal Settings

For a complete and consistent look, you should also configure your terminal emulator to use the base background and foreground colors from this theme.

-   **Background Color:** `#16161d`
-   **Foreground Color:** `#c8c093`

Enjoy your new Tmux theme!
