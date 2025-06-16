# CES_AI_Medic_Script
A fully autonomous AI Medic system for FiveM, compatible with QBCore and Standalone frameworks. This script detects when EMS are unavailable and sends a medic NPC in an ambulance to revive the player, complete with animations, a medbag prop, and hospital transport!

🧠 Features
✅ QBCore and Standalone compatible

🚨 Call AI EMS when no EMS are online
🧍 AI Medic drives to you in an ambulance
💉 Custom revival animations and medbag prop
💵 Configurable revive cost
🏥 Transports player to the nearest configured hospital
💬 Displays cause of death in 3D text
🔊 Notifications with chat fallback

🔧 Configuration
``` Located in config.lua:
Config.MedicModel = 's_m_m_paramedic_01'
Config.AmbulanceModel = 'f450ambo'
Config.ReviveDelay = 10000
Config.Fee = 500
Config.MaxEMSOnline = 5
Config.Hospitals = {
    city = vector3(308.24, -592.42, 43.28),
    sandy = vector3(1828.52, 3673.22, 34.28),
    paleto = vector3(-247.76, 6331.23, 32.43),
    default = vector3(293.0, -582.0, 43.0)
}
```
📦 Installation
Place the resource in your resources folder.

Add to server.cfg:
ensure CES_AI_Medic

Dependencies
Optional: qb-core (for full integration with QBCore framework)

🧪 Notes
Automatically checks EMS online count and disables AI if real medics are available.
Works out of the box in standalone mode—QBCore is optional.
You can adjust the script to your preferred animation, models, and logic easily.

Credits
Developed by Crazy Eyes Studio
