# Document 05: Official Comms Channel Allocation

---

### **DOCUMENT INFORMATION**

| Field | Value |
| :--- | :--- |
| **Document ID** | `05-ChannelDistribution` |
| **Circuit Name**| Radio Channel & Signal Doctrine |
| **Author** | Xavrax |
| **Version** | 1.0 (Subject to change based on crew shenanigans) |
| **Classification**| Standard Operating Procedure |
| **Date**| 18.07.2k25 |

---

### 1. Overview

This document outlines the official allocation of wireless communication channels for this vessel. In the cacophony of groaning metal, screaming crewmates, and sonar pings of indeterminate origin, a structured communication system is our last bastion of sanity. Adherence to this doctrine is not merely recommended; it is essential for distinguishing a genuine "the reactor is on fire" alert from a heated debate about the correct way to wire a lightbulb.

Failure to respect these channels will be considered an act of profound negligence, punishable by being assigned the "clown wrangler" duty for a full cycle.

### 2. Channel & Signal Matrix

| Channel | Signal Value(s) | Purpose & Official Doctrine |
| :--- | :--- | :--- |
| **0000** | `chat`, `important_alerts` | **The "Discord" Channel:** This is the general-purpose channel for text-based communication and the default broadcast channel for most automated ship alerts (e.g., low oxygen, high water levels). |
| **100X** | `ballast_flora_purge_X` | **Ballast Flora Purge:** Triggers emergency ballast water removal in a specific ballast room infected with Ballast Flora. `X` denotes the ballast room ID (e.g., 1 for the leftmost, 2 for the next, and so on). This is a dedicated, single-purpose channel to avoid accidental activation or signal interference. |
| **1330** | `y_velocity_out` | **Navigation Y-Velocity Telemetry:** Broadcasts the vessel's current vertical speed from the navigation terminal. Used for fine-tuned piloting and docking maneuvers. |
| **1337** | `captain_shut_the_fuck_up_alert` | **The "Captain's Megaphone":** This is a priority override channel used exclusively by the Captain. When this signal is broadcast, all non-essential chatter on all channels is to cease immediately. It is the audio equivalent of the Captain staring directly at you with that "I am not amused" expression. Ignoring this signal is considered insubordination. |
| **9999** | `terminal_sync` | **Terminal Sync Channel:** A dedicated channel for data synchronization between shipboard computer terminals. Manual use is prohibited to prevent data corruption. |

---

### 3. Channel Etiquette & Warnings

-   :warning: **WARNING:** Do not broadcast on a channel you do not understand. You may accidentally trigger the "self-destruct sequence" we definitely didn't install. Or worse, the emergency clown-horn deployment system.
-   :information_source: **NOTE:** This list is not exhaustive. New channels may be allocated for specific operational needs. Unauthorized creation of channels for "private" discussions is discouraged, as the Chief Engineer can probably listen in anyway.
-   :memo: **MEMO:** If you are unsure which channel to use, default to `0000`. If you have nothing useful to say, default to silence. The lives you save may include your own. 