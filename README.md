# RNK Lobby

**RNK Lobby** is a system-agnostic module for Foundry VTT that allows Game Masters to place their world into a "GM Prep Mode" (formerly Maintenance Mode). When active, players are prevented from interacting with the game world and are instead presented with a customizable, full-screen lobby overlay. This is perfect for setting up scenes, preparing encounters, or taking a break without players wandering around.

![RNK Lobby Cover](assets/cover.jpg)

## 🌟 Key Features

*   **Secure Lobby Overlay:** Blocks player access to the canvas, sidebar, and controls while the GM works.
*   **GM Control Center:** A dedicated dashboard for the GM to manage the lobby state, chat, polls, and settings.
*   **Countdown Timers:** Display a countdown to the start of the session or the end of a break.
*   **Live Chat & Monitoring:** Chat with players directly from the lobby overlay. The GM can monitor player chat even while they are locked out.
*   **Interactive Polls:** Run quick polls to gather player feedback or make decisions while they wait.
*   **Customizable Themes:** Choose from built-in themes (Crimson Dawn, Midnight Vigil, etc.) or fully customize colors, fonts, and background images.
*   **Presets:** Save and load your favorite lobby configurations.
*   **Analytics:** Track session durations and engagement.

## 🛠️ Installation

1.  Copy the `rnk-lobby` folder to your Foundry VTT `Data/modules/` directory.
2.  Launch Foundry VTT and enable the module in your world's **Manage Modules** settings.

## 📖 Usage

### Activating the Lobby
1.  Log in as a Gamemaster.
2.  Go to the **Token Controls** (left sidebar) and look for the **RNK Lobby** tool.
3.  Click the **Toggle GM Prep Lobby** button.
4.  Confirm the activation. All connected players will immediately see the lobby overlay.

### The GM Control Center
Once the lobby is active, the GM will see a minimized control panel. Expand it to access:
*   **Status:** View active players and lobby duration.
*   **Appearance:** Change the background image, title, message, fonts, and colors.
*   **Countdown:** Set a timer for when the game will resume.
*   **Polls:** Create and manage polls for your players.
*   **Chat:** Send announcements or chat with players in the lobby.

### Customization
You can customize the look and feel of the lobby to match your campaign's aesthetic:
*   **Background:** Upload your own image or use the default.
*   **Themes:** Select from pre-configured themes like *Crimson Dawn*, *Midnight Vigil*, *Verdant Harbor*, or *Emberfall*.
*   **Fonts:** Choose from a variety of Google Fonts for headings and body text.
*   **Blur & Opacity:** Adjust the background blur and overlay opacity for readability.

## ⚙️ Settings

*   **GM Preview Mode:** Allows the GM to see the lobby overlay for testing purposes (configured in Module Settings).

## 🤝 Compatibility
RNK Lobby is **system-agnostic** and should work with any Foundry VTT game system (D&D 5e, Pathfinder, etc.).

## 📜 License
This module is licensed under the [MIT License](LICENSE).

## 🐛 Bug Reports & Feedback
Please report issues or suggest features on the [GitHub Issues](https://github.com/Odinn-1982/rnk-lobby/issues) page.
