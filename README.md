# KiiBOOM LOOP75 SignalRGB JavaScript Script


This repository provides a custom JavaScript (JS) lighting script to integrate the **KiiBOOM LOOP75** mechanical keyboard into **SignalRGB**. 

---

## ⚠️ DISCLAIMER & WARNING

> [!WARNING]
> **Experimental Support:** The current firmware for the KiiBOOM LOOP75 is **not officially supported** by SignalRGB out of the box. 
> To use this script, you may need to **rebuild/compile a custom firmware** from scratch using the source files provided in the [Official KiiBOOM GitHub Repository](https://github.com/KiiBOOM-Official/LOOP75). Use this at your own risk.

---

## 📖 Overview

The KiiBOOM LOOP75 requires a specific JavaScript controller script to map the LED matrix correctly for SignalRGB.

* **Device:** KiiBOOM LOOP75
* **Language:** JavaScript (SignalRGB API)
* **Firmware Status:** Manual QMK/VIA compilation required.

---

## 🚀 Installation

1.  **Download the Script:** Download the `KiiBOOM_LOOP75.js` file from this repository.
2.  **Locate Plugins Folder:** Open SignalRGB and go to `Settings` > `User Config` or navigate to:
    * `%AppData%\Vortx\SignalRGB\Plugins`
3.  **Copy File:** Place the `.js` file into that folder.
4.  **Restart SignalRGB:** Completely close and restart SignalRGB.

---

## ⚙️ QMK & Firmware Setup

Since there is no official SignalRGB-ready firmware yet, you must manually enable the protocol:

1.  Clone the [Official KiiBOOM LOOP75 Repo](https://github.com/KiiBOOM-Official/LOOP75).
2.  Follow the [SignalRGB QMK Support Guide](https://docs.signalrgb.com/qmk/) to modify the `rules.mk` and `config.h` files.
3.  Compile and flash the new firmware to your device.

---

## 🔗 Useful Links

| Resource | Link |
| :--- | :--- |
| **Official KiiBOOM GitHub** | [KiiBOOM-Official/LOOP75](https://github.com/KiiBOOM-Official/LOOP75) |
| **Manufacturer** | [KiiBOOM Official Website](https://www.kiiboom.com/) |
| **SignalRGB Software** | [Download SignalRGB](https://signalrgb.com/) |
| **QMK Guide** | [SignalRGB QMK/VIA Support Docs]([https://docs.signalrgb.com/qmk/qmk-toolbox/) |

---

## 🛠 Troubleshooting

* **No Connection:** Ensure you have compiled the firmware with `RAW_ENABLE = yes`.
* **Firmware Recovery:** If anything goes wrong, refer to the [KiiBOOM GitHub](https://github.com/KiiBOOM-Official/LOOP75) for original firmware files.

  ## ⚠️ DISCLAIMER & WARNING

> [!WARNING]
> **Experimental Support:** The current firmware for the KiiBOOM LOOP75 is **not officially supported** by SignalRGB out of the box. 
> To use this script, you may need to **rebuild/compile a custom firmware** from scratch using the source files provided in the [Official KiiBOOM GitHub Repository](https://github.com/KiiBOOM-Official/LOOP75). Use this at your own risk.

---

## 📜 License

This project is open-source and available under the **MIT License**.

*Disclaimer: This is a community-driven project and is not officially affiliated with KiiBOOM or SignalRGB.*
