# Document 08: Terminal Command Reference

---

### **DOCUMENT INFORMATION**

| Field | Value |
| :--- | :--- |
| **Document ID** | `08-TerminalCommands` |
| **Document Name**| Terminal Command Reference |
| **Author** | Xavrax |
| **Version** | 1.0 (New commands may be added) |
| **Classification**| Standard Operating Procedure |
| **Date**| 27.07.2k25 |

---

### 1. Overview & Warning

The command terminal is a powerful tool for interacting with various ship systems. However, its power demands caution. An incorrect command can lead to unintended, and potentially catastrophic, consequences. Misuse of the terminal is not a valid excuse for flooding the medbay with clown horns or accidentally venting the Captain's private oxygen supply.

**Use every command with deliberate intent. If you are unsure about a command's function, do not execute it.**

---

### 2. Available Commands

This section details the commands available for use in the ship's terminals.

| Command | Arguments | Description & Usage |
| :--- | :--- | :--- |
| **`help`** | (none) | Displays a link to this document, providing a reference for all available commands. Use this if you are ever unsure about command syntax or function. |
| **`echo`** | `<input>` | Broadcasts the specified `<input>` string as a text message. This is primarily used by automated systems to output data or alerts to the general chat channel (`0000`, as defined in `05-ChannelDistribution.md`) via a connected WIFI component. |
| **`set <variable>`** | `<value>` | Sets a named variable to the provided value. See the Variables section below for supported names and allowed values. |

---

### 3. Variables

- **`drop_ballast_X`**: Remotely starts the purge process described in `07-PurgeAllWater.md` for ballast room `X` (1 = leftmost).
  - **Allowed values**: `0` (off), `1` (start purge)
- **`close_canteen`**: Forces the canteen doors closed. Doors remain locked until this variable is set back to `0`.
  - **Allowed values**: `0` (unlocked), `1` (locked) 