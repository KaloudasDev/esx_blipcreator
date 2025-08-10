    # 🗺️ **BlipCreator - FiveM Custom Blip Creator**

**Overview:**  
BlipCreator is an advanced, highly customizable blip creation system designed to enhance GTA 5 servers with seamless, efficient map markers. With this tool, server administrators can easily configure and manage blips, tailored to the exact needs of their server. Each blip is fully customizable, allowing for precise control over location, text, sprite, color, and scale.

**Key Features:**  
- **Comprehensive Blip Customization:** Fully configurable blips with adjustable positions, text labels, sprite icons, colors, and scaling for a unique server experience.  
- **Optimized Performance:** Designed with performance in mind, ensuring smooth gameplay even with numerous blips displayed.  
- **Seamless Integration:** Easy-to-implement solution for adding blips into any FiveM server.  
- **Dynamic Blip Control:** Modify and manage blips directly via the configuration file without server downtime.

**Credits:**  
- Developed by **Kaloudas**, with special thanks to the dedicated FiveM and GTA 5 modding communities for their continuous support, feedback, and contributions.

**License:**  
- This project is licensed under the **MIT License**, providing full freedom to use, modify, and distribute the script.

---

## ⚙️ **Installation & Setup Instructions:**

To integrate **BlipCreator** into your GTA 5 server, follow these detailed steps:

### 1️⃣ **Clone the Repository**  
Clone the repository to your local machine with the following command:  
```sh
git clone https://github.com/KaloudasDev/NobleBlips
```

### 2️⃣ **Install Dependencies**  
Ensure your server is configured correctly with the necessary resources for optimal performance. This script is compatible with **FiveM** servers running the latest build.

### 3️⃣ **Configuration**  
Configure the blip locations in the `config.lua` file to suit your server's needs. You can add, remove, or modify blips at will by editing the `Locations` table.

Example configuration for blips:
```lua
Config.Locations = {
    [1] = {
        vector = vector3(538.32, -183.18, 54.47), 
        text = "Repair Station", 
        color = 1, 
        sprite = 446, 
        scale = 0.5,
    },
    [2] = {
        vector = vector3(-778.01, 4965.29, 209.68), 
        text = "Hunting Zone", 
        color = 5, 
        sprite = 51, 
        scale = 0.8,
    },
    -- Additional blips can be added here
}
```

### 4️⃣ **Add the Script to Your Server**  
Place the `NobleBlips` folder into your server's `resources` directory. Make sure it is properly referenced in your `server.cfg`:
```cfg
ensure NobleBlips
```

### 5️⃣ **Restart the Server**  
Restart your server to load the **BlipCreator** script and apply the configured blips.

### 6️⃣ **Dynamic Updates**  
You can easily adjust or add new blips by modifying the `config.lua` file and restarting the resource. This allows for flexible customization during runtime without affecting server performance.

---

## 📑 **Important Notes:**

- **Ensure Compatibility:** NobleBlips works seamlessly with FiveM servers. Ensure your server is using an up-to-date version of FiveM for optimal performance.
- **Resource Management:** If you have a large number of blips, monitor server performance to maintain smooth gameplay for all players.
- **Customization:** You are encouraged to tailor the blips according to the specific needs of your server. Feel free to modify the blip colors, sprites, and text to reflect your server's branding and unique features.

---

## 🔗 **Contact & Support Links:**

- **Developer's Discord Profile:** [Kaloudas](https://discordlookup.com/user/1069279857072160921)  
- **Developer's Email:** [kaloudasdev@gmail.com](mailto:kaloudasdev@gmail.com) 

