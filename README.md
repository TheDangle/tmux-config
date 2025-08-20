🍂 Autumn Forest Tmux ThemeA dark and colorful tmux theme inspired by the warm, grounded tones of an autumn forest, designed to be easy on the eyes while providing clear visual cues for your active sessions and panes.📸 Screenshot(Consider adding a screenshot of your tmux setup here for a quick visual reference!)✨ FeaturesDark Base: Uses a deep, dark background to reduce eye strain.Warm Palette: Employs rich greens, yellows, and reds for a vibrant, yet earthy feel.Clear Status Line: Highlighting of active windows and panes for improved navigation.Distinct Borders: Visually separates panes with subtle inactive borders and a prominent accent for the active pane.🚀 Installation & SetupTo get this theme working, you'll need to configure both your terminal emulator and your tmux configuration file (~/.tmux.conf).1. Terminal Emulator SettingsThe background and default foreground (text) colors are set in your terminal application (e.g., Alacritty, iTerm2, Kitty, GNOME Terminal, etc.), not directly within tmux.Background: sumiInk0_bg (#16161d)Default Text (Foreground): oldwhite_fg (#c8c093)Please refer to your specific terminal emulator's documentation for instructions on how to set these base colors. Ensure your terminal is configured for 256-color or true color (24-bit) support for the best experience.2. Tmux Configuration (~/.tmux.conf)Add the following lines to your ~/.tmux.conf file. If you don't have one, simply create it in your home directory.# Enable true color support (important!)
set -g default-terminal "tmux-256color"

# --- Theme Configuration ---

# General pane and status bar colors
# Status Line Background: winterGreen (#2B3328)
set -g status-style bg='#2B3328'

# Inactive Pane Border: KanataGrey (#717C7C)
set -g pane-border-style fg='#717C7C'

# Active Pane Border (Accent): autumnRed (#C34043)
set -g pane-active-border-style fg='#C34043'

# Status line text (left and right side)
# Text color for status line elements: autumnYellow (#DCA561)
set -g status-left-style fg='#DCA561'
set -g status-right-style fg='#DCA561'

# Window list colors
# Inactive Window Name Text: autumnGreen (#76946A)
setw -g window-status-style fg='#76946A'

# Active Window Name Text: autumnYellow (#DCA561)
setw -g window-status-current-style fg='#DCA561'

# You can further customize the status line content if desired.
# Example:
# set -g status-left '#[fg=#DCA561] #S #[fg=#76946A]|#[fg=#DCA561] #I '
# set -g status-right '#[fg=#76946A]|#[fg=#DCA561]%H:%M %d-%b-%y'
3. Apply ChangesAfter saving your ~/.tmux.conf file:If tmux is running: Press your tmux prefix key (default Ctrl + b), then type :source-file ~/.tmux.conf and press Enter.If tmux is not running: Simply start a new tmux session (tmux new) for the changes to take effect.🎨 Color Palette BreakdownHere's how your provided colors are utilized in this theme:Tmux ElementColor NameHex CodeUsageTerminal BackgroundsumiInk0_bg#16161dSet in your terminal emulator.Default Textoldwhite_fg#c8c093Set in your terminal emulator.Status Bar BackgroundwinterGreen#2B3328Background of the entire status line.Active Pane BorderautumnRed#C34043Highlight for the active pane.Inactive Pane BorderKanataGrey#717C7CSubtle border for inactive panes.Active Window NameautumnYellow#DCA561Text for the current window in status.Inactive Window NameautumnGreen#76946AText for other windows in status.Status Line TextautumnYellow#DCA561General text on the status line.🛠️ CustomizationFeel free to experiment with the other colors you provided to tweak this theme to your personal preference! You can easily swap out hex codes in the ~/.tmux.conf file.🤝 ContributingSuggestions and improvements are welcome! If you have ideas for enhancing this theme or find any issues, please open an issue or pull request.📄 LicenseThis theme is open-source and available under the MIT License.
