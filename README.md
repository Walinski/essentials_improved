# Essentials Plugin

**Author:** Solero  
**Version:** 1.0.0  

The Essentials plugin provides a suite of useful commands for server moderators to manage player stats and interact with the game environment. This plugin includes commands for adding items, coins, puffles, teleporting players, summoning, and more.

### Installation

1. Clone the repository into your plugins folder:
   ```bash
   git clone https://github.com/Walinski/essentials_improved.git
   ```

2. Start your Houdini server, and the plugin will automatically load if placed in the correct folder.

### Available Commands

Below are some of the useful commands included in this plugin that allow moderators to manipulate player stats. These commands require specific permissions to use.

#### **1. Item Management**

- **Add Item to Player Inventory:**
  ```
  !ai [item_name or item_id]
  ```
  Adds an item to the player's inventory. If the item does not exist, an error will be shown.

- **Send Item to Another Player:**
  ```
  !send_ai [username] [item_name or item_id]
  ```
  Sends an item to another player’s inventory.

#### **2. Coin Management**

- **Add Coins:**
  ```
  !ac [amount]
  ```
  Adds a specified amount of coins to the player's account (default is 100 coins).

- **Transfer Coins to Another Player:**
  ```
  !pay [username] [amount]
  ```
  Transfer coins to another player. The amount must be positive, and the target player must be online.

#### **3. Teleportation and Summoning**

- **Teleport to a Player:**
  ```
  !tp [username]
  ```
  Teleports you to the room of the specified player.

- **Summon a Player to Your Room:**
  ```
  !summon [username]
  ```
  Summons another player to your current room.

#### **4. Puffles**

- **Add Puffles:**
  ```
  !ap [puffle_name or puffle_id] [username (optional)]
  ```
  Adds a puffle to a player's inventory. If the player already has 75 puffles, the action will fail.

#### **5. Room Management**

- **Join Room:**
  ```
  !room [room_id]
  ```
  Teleports the player to the specified room. If the room doesn't exist, an error will be shown.

#### **6. Moderator Actions**

- **Ban Player:**
  ```
  !ban [username] [message] [duration_in_hours]
  ```
  Bans a player for a specified number of hours. Set duration to 0 for a permanent ban.

- **Kick Player:**
  ```
  !kick [username]
  ```
  Kicks a player from the server.

#### **7. Ninja Progression**

- **Become Ninja:**
  ```
  !ninja
  ```
  Grants the player ninja rank, along with all ninja items and cards.

#### **8. Stamp Management**

- **Add All Stamps:**
  ```
  !stamps
  ```
  Grants the player all available stamps.

#### **9. Miscellaneous**

- **Add Igloo:**
  ```
  !ag [igloo_name or igloo_id]
  ```
  Adds an igloo to the player's inventory.

- **Add Furniture:**
  ```
  !af [furniture_name or furniture_id] [amount]
  ```
  Adds specified furniture to the player's inventory.

- **Add Career/Agent Medals:**
  ```
  !medals [career_medals] [agent_medals]
  ```
  Adds career and agent medals to the player's profile (default is 100 medals).

---

### Permissions

Each command requires the user to have specific permissions. You can configure these permissions for your moderators or players in your Houdini server configuration.

### Contributions

Feel free to contribute to this plugin by submitting issues or pull requests!

### License

This plugin is licensed under the MIT License. See the LICENSE file for more information.

---

This README provides an overview of how to use the Essentials plugin, including descriptions of commands and their usage.
