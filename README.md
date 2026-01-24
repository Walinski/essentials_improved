# Essentials Plugin

**Author:** Solero
**Version:** 1.0.0

The Essentials plugin provides a suite of useful commands for server moderators to manage player stats and interact with the game environment. This plugin includes commands for adding items, coins, puffles, teleporting players, summoning, room management, and more.

### Installation

1. Clone the repository into your plugins folder:

   ```bash
   git clone https://github.com/Walinski/essentials_improved.git
   ```

2. Start your Houdini server, and the plugin will automatically load if placed in the correct folder.

### Available Commands

Below are some of the useful commands included in this plugin that allow moderators to manipulate player stats. These commands require specific permissions to use.

#### **1. Item Management**

* **Add Item to Player Inventory:**

  ```
  !ai [item_name or item_id]
  ```
* **Send Item to Another Player:**

  ```
  !send_ai [username] [item_name or item_id]
  ```

#### **2. Coin Management**

* **Add Coins:**

  ```
  !ac [amount]
  ```
* **Transfer Coins to Another Player:**

  ```
  !pay [username] [amount]
  ```

#### **3. Teleportation and Summoning**

* **Teleport to a Player:**

  ```
  !tp [username]
  ```
* **Summon a Player to Your Room:**

  ```
  !summon [username]
  ```

#### **4. Puffles**

* **Add Puffles:**

  ```
  !ap [puffle_name or puffle_id] [username (optional)]
  ```

#### **5. Room Management**

* **Join Room:**

  ```
  !room [room_id]
  ```

  Teleports the player to the specified room. If the room does not exist, an error will be shown.
  For a full list of rooms, their IDs, capacities, and usage instructions, see [Rooms.md](Rooms.md).

#### **6. Moderator Actions**

* **Ban Player:**

  ```
  !ban [username] [message] [duration_in_hours]
  ```
* **Kick Player:**

  ```
  !kick [username]
  ```

#### **7. Ninja Progression**

* **Become Ninja:**

  ```
  !ninja
  ```

#### **8. Stamp Management**

* **Add All Stamps:**

  ```
  !stamps
  ```

#### **9. Miscellaneous**

* **Add Igloo:**

  ```
  !ag [igloo_name or igloo_id]
  ```
* **Add Furniture:**

  ```
  !af [furniture_name or furniture_id] [amount]
  ```
* **Add Career/Agent Medals:**

  ```
  !medals [career_medals] [agent_medals]
  ```

### Permissions

Each command requires the user to have specific permissions. You can configure these permissions for your moderators or players in your Houdini server configuration.

### Contributions

Feel free to contribute to this plugin by submitting issues or pull requests.

### License

This plugin is licensed under the MIT License. See the LICENSE file for more information.
