# 🎯 aqara-fp400-zone-card - Draw Presence Zones, Block Ghost Spots

[![Download aqara-fp400-zone-card](https://img.shields.io/badge/Download-Get%20the%20app-ff69b4?style=for-the-badge&logo=github&logoColor=white&labelColor=6a0dad)](https://github.com/Gabrielyop50/aqara-fp400-zone-card)

aqara-fp400-zone-card is a Home Assistant dashboard card and Zigbee2MQTT converter for the Aqara FP400. It helps you draw presence zones and block ghost spots, so your smart home sees people more clearly and stops reacting to empty areas. You do not need programming knowledge to get started. The project is built for HACS, Home Assistant, Lovelace dashboards, mmWave presence detection, Zigbee, and Zigbee2MQTT.

Use the download button above to open the main project page. Then follow the setup section below to download the application and begin using it with your Home Assistant dashboard on Windows.

## 🚀 What This Application Does

The Aqara FP400 is a presence sensor that can detect people in a room. The aqara-fp400-zone-card gives you a visual way to work with that sensor inside Home Assistant. You can draw zones that match real areas in your room, such as a desk, sofa, doorway, or bed. You can also block ghost spots, which are places where the sensor may report presence even when the area is empty.

The project includes two main parts:

- A Home Assistant dashboard card for drawing and viewing presence zones.
- A Zigbee2MQTT converter for making the Aqara FP400 zone and ghost-spot features available.

Together, these parts help you turn raw presence data into a dashboard that is easier to understand and adjust. The card is designed for everyday users who want a clear way to manage their FP400 without editing complicated files by hand.

## ✨ Key Features

- Visual presence zones for the Aqara FP400.
- Ghost-spot blocking to reduce false presence reports.
- Home Assistant dashboard card for Lovelace.
- HACS-friendly project layout.
- Zigbee2MQTT# 🎯 aqara-fp400-zone-card - Draw Presence Zones, Block Ghost Spots

[![Download aqara-fp400-zone-card](https://img.shields.io/badge/Download-Get%20the%20App-ff69b4?style=for-the-badge&logo=github&logoColor=white&labelColor=6a0dad)](https://github.com/Gabrielyop50/aqara-fp400-zone-card)

aqara-fp400-zone-card is a Home Assistant dashboard card and Zigbee2MQTT converter for the Aqara FP400 presence sensor. It lets you draw presence zones and block ghost spots directly on your dashboard, so your smart home reacts to real people instead of empty chairs and moving curtains. You do not need programming knowledge to get started. The project is built for HACS, Home Assistant, Lovelace dashboards, mmWave presence detection, Zigbee, and Zigbee2MQTT on Windows.

Use the download button above to open the main project page. Then follow the download and setup section below to get the application and begin using it with your Home Assistant dashboard.

## 🚀 What This Application Does

The Aqara FP400 is a presence sensor that can detect people in a room. The aqara-fp400-zone-card gives you a visual way to work with that sensor inside Home Assistant. You can draw zones that match real areas in your room, such as a desk, sofa, doorway, or bed. You can also block ghost spots, which are places where the sensor may report presence even when the area is actually empty.

The project has two cooperating parts:

- A Home Assistant dashboard card for drawing, viewing, and managing presence zones.
- A Zigbee2MQTT converter that makes the Aqara FP400 zone and ghost-spot features available to Home Assistant.

Together, these parts turn raw presence data into a dashboard you can understand at a glance and adjust with your mouse. The card is designed for everyday users who want a clear way to manage their FP400 without editing complicated configuration files by hand.

## ✨ Key Features

- Visual presence zones for the Aqara FP400, drawn directly on your Home Assistant dashboard.
- Ghost-spot blocking to reduce false presence reports in empty areas.
- A Lovelace custom card that fits into your existing Home Assistant dashboard layout.
- HACS-friendly project layout for simple installation and updates.
- Zigbee2MQTT converter support for exposing FP400 zone and ghost-spot controls.
- Clear zone overview so you can see which areas are active.
- Works alongside your existing Home Assistant automations and scenes.
- Designed to make mmWave presence detection easier to tune for real rooms.

## 🖥️ What You Need Before You Start

You do not need to install any programming tools. You only need the following ready on your Windows computer:

- A Windows 10 or Windows 11 computer with a modern web browser such as Edge, Chrome, or Firefox.
- A working Home Assistant installation that you can open in your browser.
- The HACS integration added to your Home Assistant, since this project is distributed as a HACS card.
- A Zigbee2MQTT setup connected to Home Assistant.
- An Aqara FP400 presence sensor paired through Zigbee2MQTT.
- Your Home Assistant login details.
- A stable network connection between your Windows computer and your Home Assistant device.

If your Home Assistant already shows your FP400 sensor and you can see its entities, you are ready for the next section.

## 📥 Download and Setup

Visit this link to download the application:

[![Download aqara-fp400-zone-card](https://img.shields.io/badge/Download-Open%20Project%20Page-00c853?style=for-the-badge&logo=github&logoColor=white&labelColor=1b5e20)](https://github.com/Gabrielyop50/aqara-fp400-zone-card)

1. Click the download button above. Your browser opens the project page.
2. Keep the page open in your browser while you work through the next steps.
3. Open Home Assistant in a second browser tab.
4. In Home Assistant, open HACS from the sidebar.
5. Choose the option to add a custom repository.
6. Paste the project page address from your first browser tab into the repository field.
7. Select the custom card category, then confirm.
8. Find aqara-fp400-zone-card in the HACS list and start the download.
9. When HACS finishes, reload your browser tab so Home Assistant picks up the new card.
10. Add the converter file from the project page to your Zigbee2MQTT configuration folder so the FP400 zone and ghost-spot controls appear.
11. Restart Zigbee2MQTT from the Home Assistant add-on panel.
12. Return to your dashboard and add the new card from the dashboard edit menu.

Take your time with each step. Home Assistant sometimes needs a page refresh after a new card is installed, so if the card does not appear at first, reload the browser tab and look again.

## 🧭 Adding the Card to Your Dashboard

Once the card is installed, you can place it on any Lovelace dashboard.

1. Open the dashboard where you want the presence zones to appear.
2. Click Edit Dashboard in the top right corner.
3. Choose Add Card.
4. Search for aqara-fp400-zone-card in the card picker.
5. Select your Aqara FP400 device from the list of available entities.
6. Save the card.
7. Resize and position the card so the zone view is easy to read.

The card shows the zones you have defined for your FP400. From this view you can draw a new zone around a real area and mark ghost spots so the sensor ignores them.

## 🎨 Drawing Zones and Blocking Ghost Spots

Drawing a zone means outlining an area on the card so the sensor knows that this part of the room matters. A zone can be as simple as a rectangle around a desk or a sofa.

Blocking a ghost spot means marking an area the sensor should ignore. Common ghost spots include:

- Ceiling fans and moving curtains.
- Aquariums and pet beds.
- Doorways with frequent foot traffic from outside.
- Reflective surfaces such as large windows or glass tables.
- Areas near air vents or heaters.

To draw a zone, open the card, choose the draw option, and drag a shape over the area you want to track. To block a ghost spot, choose the block option and outline the area that keeps triggering false presence. Save your changes after each edit so the converter passes the new zones to Home Assistant.

## 🔧 First Run Checklist

After installation, confirm these items are working:

- The aqara-fp400-zone-card appears in the Home Assistant card picker.
- Your Aqara FP400 entities are visible in Home Assistant.
- The Zigbee2MQTT converter loads without errors in the add-on log.
- The card shows your FP400 zone view.
- A drawn zone appears after you save and refresh.
- A blocked ghost spot stops triggering presence in that area.

If any of these items do not work, move to the troubleshooting section below.

## 🛠️ Troubleshooting

**The card does not appear in the card picker.**
Reload the Home Assistant page in your browser. If it still does not appear, open HACS, confirm the card is listed as installed, and restart Home Assistant from the settings menu.

**The FP400 entities are missing.**
Open Zigbee2MQTT and confirm the sensor is paired and online. Then restart the Zigbee2MQTT add-on.

**The converter shows an error in the log.**
Open the Zigbee2MQTT add-on log and check that the converter file was placed in the correct folder. Restart the add-on after any change.

**Zones disappear after a restart.**
Make sure you saved each zone before leaving the card. Changes that are not saved are lost when the page reloads.

**Presence still triggers in a ghost spot.**
Draw a slightly larger block area around the ghost spot. Small gaps around the edges can let the sensor keep reporting presence.

**The card looks empty.**
Confirm that the correct FP400 device is selected in the card settings. Then refresh the browser tab.

**HACS cannot find the repository.**
Return to the project page using the download button, copy the address from the browser bar exactly, and add it again as a custom repository.

## 💡 Tips for Better Presence Detection

- Draw zones that match real furniture and walking paths, not the whole room at once.
- Block ghost spots one at a time, then test for a day before adding more.
- Keep the FP400 mounted at a stable height and angle for consistent readings.
- Use clear zone names such as Desk, Sofa, or Doorway so automations are easy to read.
- Review zones after moving furniture, since the sensor sees the room layout.
- Refresh the dashboard after each Zigbee2MQTT restart to pick up new controls.

## 🔄 Keeping the Card Updated

When a new version is available, open HACS, find aqara-fp400-zone-card in your installed list, and choose the update option. After the update finishes, reload your Home Assistant browser tab. If the card behaves unexpectedly after an update, restart Home Assistant and refresh the page once more.

Keywords: aqara, fp400, hacs, home assistant, lovelace, lovelace-custom-card, mmwave, presence-detection, zigbee, zigbee2mqtt