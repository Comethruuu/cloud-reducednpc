# Reduced NPC FiveM [ESX / QB Core]

This FiveM client-side script reduces the density of NPCs in the game, allowing only vehicle NPCs (cars and trucks) to spawn. It removes pedestrians and completely suppresses all motorcycles from appearing in traffic.

---

## 🚀 Features

- 🚗 NPC cars and trucks still spawn (with reduced density).
- 🚫 No pedestrians or random scenario peds.
- 🛵 All motorcycle models are suppressed from spawning.

---

## 📁 Installation

1. Download or clone this resource into your `resources` folder
2. Add the following line to your `server.cfg` 
   ```cfg
   ensure cloud-reducednpc
   ```

---

## 🔧 Configuration

You can change the vehicle density by modifying the value of `DensityMultiplier` in `client.lua`:

```cfg
local DensityMultiplier = 0.1 -- Change from 0.0 to 1.0 as needed
```

---

## 🧑‍💻 Author

[Cloud](https://github.com/Comethruuu)
