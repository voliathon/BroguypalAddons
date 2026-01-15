# Broguypal Addons

A collection of Lua addons for **Windower 4** in *Final Fantasy XI*, designed to improve quality of life, combat tracking, and Abyssea gameplay.

## ⚠️ Contact & Support
**Please do not message me in-game about these Addons.** I will not respond as I do not discuss third-party programs in-game.

If you would like to reach out, you can find me on Discord: **Broguypal**

---

## 📦 Installation
1. Download the files.
2. Place the specific addon folder (e.g., `TrueTargetLock`, `dbTracker`) into your Windower `addons` directory.
   - Path example: `.../Windower4/addons/dbTracker/`
3. Load the addon in-game using the console:
   ```lua
   //lua load <addon_name>
   ```

   ## 🛠️ Addon List

### 1. AbysseaProc
**Version:** 2.0  
**Commands:** `//aproc`

Helps players trigger Red Procs in Abyssea by managing elements and weapons. It features a HUD that displays the current element and the required weapon/WS.

* **Key Features:**
    * Cycles through Abyssea proc elements.
    * Auto-swaps to the correct weapon for the active element.
    * Executes the correct Weapon Skill for the current weapon.
* **Default Keybinds:**
    * `F10`: Cycle Element
    * `F11`: Cycle Weapon
    * `F12`: Use Weapon Skill

### 2. dbTracker
**Version:** 1.4  
**Commands:** N/A (Runs automatically)

A party monitor that tracks active debuffs on party members in real-time.

* **Key Features:**
    * **Role Colors:** Jobs are colored by role (e.g., Blue for Tanks, Green for Healers) for quick visual identification.
    * **Severe Debuffs:** Highlights critical statuses (like Doom or Charm) in **Orange**.
    * **Customizable:** Edit `tracked_buffs.lua` to change which debuffs are tracked or marked as severe.

### 3. faceaway
**Version:** 1.0  
**Commands:** `//faceaway turn`

A simple utility to instantly turn your character 180 degrees away from their current facing.

* **Usage:**
    * Default Keybind: **Numpad0**
    * Useful for gaze attacks (e.g., Petrification eyes).

### 4. tTracker (Target Tracker)
**Version:** 2.0  
**Commands:** `//track` or `//ttracker`

Displays a draggable text box showing recent spell casts and TP moves used by your current target.

* **Key Features:**
    * **Color Coded:** Spells and abilities are colored by their element.
    * **Modes:**
        * `//track mode always` (Always visible)
        * `//track mode combat` (Visible only when engaged)
        * `//track mode action` (Visible only when actions occur)
    * **Customization:** Add custom elements to monster abilities via `//track add "Ability Name" <element>`.

### 5. TrueTargetLock
**Version:** 1.1  
**Commands:** `//truetargetlock`

Automatically keeps your character facing the target while engaged in combat, preventing "Unable to see target" errors when the monster moves.

* **Modes:**
    * `normal`: Only turns you if in-game Target Lock is active.
    * `always`: Always turns you toward the target while engaged, even if Target Lock is off.

---

## 📄 License & Copyright

**Copyright (c) 2026 Broguypal**

All addons in this repository are licensed under the **BSD 3-Clause License**.

> Redistribution and use in source and binary forms, with or without modification, are permitted provided that the following conditions are met:
>
> 1. Redistributions of source code must retain the above copyright notice, this list of conditions and the following disclaimer.
> 2. Redistributions in binary form must reproduce the above copyright notice, this list of conditions and the following disclaimer in the documentation and/or other materials provided with the distribution.
> 3. Neither the name of the copyright holder nor the names of its contributors may be used to endorse or promote products derived from this software without specific prior written permission.
>
> THIS SOFTWARE IS PROVIDED BY THE COPYRIGHT HOLDERS AND CONTRIBUTORS "AS IS" AND ANY EXPRESS OR IMPLIED WARRANTIES, INCLUDING, BUT NOT LIMITED TO, THE IMPLIED WARRANTIES OF MERCHANTABILITY AND FITNESS FOR A PARTICULAR PURPOSE ARE DISCLAIMED. IN NO EVENT SHALL THE COPYRIGHT HOLDER OR CONTRIBUTORS BE LIABLE FOR ANY DIRECT, INDIRECT, INCIDENTAL, SPECIAL, EXEMPLARY, OR CONSEQUENTIAL DAMAGES (INCLUDING, BUT NOT LIMITED TO, PROCUREMENT OF SUBSTITUTE GOODS OR SERVICES; LOSS OF USE, DATA, OR PROFITS; OR BUSINESS INTERRUPTION) HOWEVER CAUSED AND ON ANY THEORY OF LIABILITY, WHETHER IN CONTRACT, STRICT LIABILITY, OR TORT (INCLUDING NEGLIGENCE OR OTHERWISE) ARISING IN ANY WAY OUT OF THE USE OF THIS SOFTWARE, EVEN IF ADVISED OF THE POSSIBILITY OF SUCH DAMAGE.
