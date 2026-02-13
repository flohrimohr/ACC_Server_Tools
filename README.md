# ACC Server Tools

Web-based tool for managing **Assetto Corsa Competizione** dedicated servers.  
Create, edit, and export all required JSON configuration files for the ACC Dedicated Server application.

The tool works with both:
- Local ACC Dedicated Server installations  
- Hosted game server providers  

No backend, no installation, no dependencies — runs entirely in your browser.

---

## Installation & Usage

No installation required.

1. Download the template file:  
   👉 [acc_server_tool.html](https://github.com/flohrimohr/ACC_Server_Tools/blob/main/acc_server_tool.html)

2. Open the file in your browser (recommended: Chrome or Firefox).

3. Make sure JavaScript is enabled in your browser.

The tool works completely offline and does not require any network connection.

---

## Persistent Settings (Optional)

You can store your changes using your browser’s Local Storage.

To enable this:
- Open **User Settings** (top right corner)
- Activate **"Keep changes"**

This ensures your configuration data is preserved between sessions.

---

## Feature Set

The following management tools are included:

---

### Driver Manager

Create and maintain a list of drivers.

Drivers created here can later be assigned to cars in the **Entry List Manager**.

---

### Entry List Manager

Create or edit the server entry list.

- Add participating cars
- Assign drivers to each car
- Configure individual car handicaps
- Define team entries

---

### BOP Manager (Balance of Performance)

Create or edit custom Balance of Performance (BoP) configurations.

- Configure per-car adjustments
- Assign BoP to specific tracks
- Export ready-to-use JSON

---

### Event Manager

Create and configure race events.

- Select track
- Configure session structure (Practice, Qualifying, Race)
- Adjust weather settings
- Define session timing

---

### Rules Manager

Configure server rule settings such as:

- Qualifying rules
- Driver stint settings
- Pit stop regulations
- Penalty rules

---

### Server Settings

Configure global server parameters:

- Admin settings
- Car limitations
- Driver requirements
- Formation lap settings
- General server behavior

---

## Import & Export

- Export generated JSON files
- Replace corresponding files in your  
  `ACC Dedicated Server / cfg` directory
- Existing configuration files can be edited and re-exported

---

## Compatibility

- Designed for Assetto Corsa Competizione Dedicated Server
- Works with local installations and hosted providers
- No additional software required

---

## Technical Details

- Pure HTML + JavaScript
- No backend
- Runs completely offline
- Uses Browser Local Storage (optional)
- No telemetry or data collection

---

## Contributing

Pull requests are welcome.  
For major changes, please open an issue first to discuss what you would like to change.

---

## License

This project is licensed under the **GNU General Public License v3.0**.

You may copy, distribute and modify the software under the terms of the GPL-3.0 license.  
Any derivative work must also be distributed under the same license.

See the `LICENSE` file for full license text.
