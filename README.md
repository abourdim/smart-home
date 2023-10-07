<p align="center">
  <img src="logo.svg" alt="Workshop DIY" width="120"><br>
  <strong style="font-size:2rem">SMART HOME KIDS LAB</strong><br>
  <em>Connect • Automate • Control</em><br><br>
  <img src="https://img.shields.io/badge/Smart%20Home-Kids%20Lab-03a9f4?style=for-the-badge&logo=homeassistant&logoColor=white" alt="Smart Home">
  <img src="https://img.shields.io/badge/Raspberry%20Pi%205-8GB-c51a4a?style=for-the-badge&logo=raspberrypi&logoColor=white" alt="Pi 5">
  <img src="https://img.shields.io/badge/Pages-22-f97316?style=for-the-badge" alt="22 Pages">
  <img src="https://img.shields.io/badge/Themes-9-22c55e?style=for-the-badge" alt="9 Themes">
  <img src="https://img.shields.io/badge/version-1.0-9ca3af?style=for-the-badge" alt="v1.0">
</p>

---

## 🧠 What is this?

You built sensors (ESPHome Lab). You built LED light shows (WLED Lab). You learned the terminal (Linux Lab). Now you build the **brain** that connects everything.

**Home Assistant** runs on a Raspberry Pi 5 and becomes the central hub for your smart home. It auto-discovers your ESP32 sensors, your WLED strips, and lets you build dashboards, write automations, and control everything with your voice.

```
                       ┌──────────────────────────┐
                       │    HOME ASSISTANT         │
                       │    (Raspberry Pi 5)       │
                       │                          │
                       │   📊 Dashboards           │
                       │   ⚡ Automations           │
                       │   🗣️ Voice Control         │
                       └──────────┬───────────────┘
                                  │
              ┌───────────────────┼───────────────────┐
              │                   │                   │
        ┌─────┴─────┐     ┌──────┴─────┐     ┌──────┴──────┐
        │  ESPHome  │     │   WLED     │     │  micro:bit  │
        │  Lab      │     │   Lab      │     │  Magic Wand │
        │  sensors  │     │   LEDs     │     │  gestures   │
        │  buttons  │     │   effects  │     │  tilt/shake │
        └───────────┘     └────────────┘     └─────────────┘
```

This web app is an **interactive guide + simulator**. Fake Lovelace dashboard, entity explorer, automation builder, YAML editor — all in the browser. No real HA needed to start learning.

---

## ⚡ Quick Start

### Option A — Just explore (zero install)

Open `index.html` → play with the dashboard simulator, build automations, explore entities. Offline. Free. No Pi needed.

### Option B — Install for real

Flash Home Assistant OS onto your Raspberry Pi 5:

1. Download **Raspberry Pi Imager** from raspberrypi.com
2. Choose OS → **Other specific-purpose OS** → **Home assistants** → **Home Assistant OS**
3. Pick your SD card → **Write**
4. Insert SD card into Pi 5 → plug in power + ethernet
5. Wait 5 minutes → open **http://homeassistant.local:8123**
6. Create your account → done

> ⚠️ First boot takes a few minutes. Be patient.

---

## 🎮 What can you do?

| Feature | What it means |
|---|---|
| **Dashboard simulator** | Build fake Lovelace dashboards in the browser — drag cards, configure, preview |
| **Entity explorer** | ~20 fake devices with live states that drift over time |
| **Automation builder** | Visual flow: Trigger → Condition → Action. YAML generates live |
| **Blueprint recipes** | 10 pre-made automations — copy-paste into real HA |
| **YAML Lab** | Fill-in-the-blank (🟢), editable (🟡), raw editor (🔴) |
| **MQTT playground** | Fake broker — publish/subscribe messages in the browser |
| **Network map** | Visual diagram of your home network with devices |
| **Scene builder** | "Movie Night" = dim lights + blue LEDs + speaker on |
| **Add-on store** | Fake add-on installer — learn what each add-on does |
| **9 themes** | 🌙⚡☁️🔥🏠🌲⚔️🌊🕌 |
| **3 languages** | 🇬🇧 English · 🇫🇷 Français · 🇸🇦 العربية (RTL) |
| **3 difficulty levels** | 🟢 Newbie · 🟡 Explorer · 🔴 Advanced |
| **Quest system** | 8 missions + 8 badges |
| **micro:bit** | Gestures → automations. Tilt, shake, press = control your home |

---

## 🛒 Shopping List

| Part | Price | Notes |
|---|---|---|
| **Raspberry Pi 5 (8GB)** | ~$80 | The brain. Future-proof |
| SD card (32GB) | ~$8 | For HA OS |
| USB-C power supply (27W) | ~$12 | Pi 5 needs 5V/5A |
| Ethernet cable | ~$3 | Optional but recommended |
| **Total** | **~$103** | Or $0 with Docker on any PC |

> 💡 Don't have a Pi? Run HA in Docker on any old laptop. Or just use the web app simulator — no hardware needed to learn.

---

## 📚 22 Pages

### Learn

| Page | What you learn |
|---|---|
| 📚 **How Smart Homes Work** | IoT, protocols (WiFi/BLE/Zigbee/Matter), local vs cloud |
| 🧠 **HA Architecture** | Entities, states, services, events, areas |
| 📐 **YAML Basics** | Syntax, indentation, key-value, lists, nesting, common mistakes |

### Setup

| Page | What you do |
|---|---|
| 🔧 **Setup** | Install HA on Pi 5 / Docker / old PC / VM |
| 🌐 **Network Tools** | Find devices, IP addresses, ping, mDNS, MQTT playground |
| 🔌 **Integrations** | Add ESPHome, WLED, MQTT, Zigbee — with fake simulator |

### Build

| Page | What you build |
|---|---|
| 📊 **Dashboard 101** | Template-based dashboard builder with live preview |
| 🎴 **Cards Catalog** | 10+ card types: button, gauge, light, thermostat, weather, history |
| ⚡ **Automations** | Visual flow builder + 10 blueprint recipes |
| 📝 **YAML Lab** | Write, edit, validate YAML. 10 starter templates |
| 🎭 **Scenes** | Save/recall device states |
| 📜 **Scripts** | Action sequences, manually triggered |

### Connect

| Page | What you connect |
|---|---|
| 📱 **Remote & Voice** | Mobile app, push notifications, Google/Alexa/Assist |
| 🧩 **Add-ons** | File Editor, SSH, MQTT, Node-RED, Piper, Whisper |
| 🌡️ **ESPHome Bridge** | Your ESP32 sensors → HA entities → cards → automations |
| 💡 **WLED Bridge** | Your LED strips → HA effects control → automated scenes |
| 🎮 **micro:bit Bridge** | Gestures → automations. Tilt = dim, shake = party mode |

### Projects & Safety

| Page | What you finish |
|---|---|
| 🏗️ **Projects** | 6 complete builds from simple to full smart room |
| 🛡️ **Safety** | Passwords, VPN, HTTPS, IoT VLAN, don't expose to internet |
| 🛠️ **Troubleshooting** | Backups, restore, logs, dev tools, "I broke everything" |
| ❓ **Help** | Glossary, YAML cheat sheet, links |

---

## 🟢🟡🔴 Difficulty Levels

Content is tagged and filtered by level:

| Level | Who | What you see |
|---|---|---|
| 🟢 **Newbie** | First time with HA | Step-by-step guides, copy-paste YAML, simple cards |
| 🟡 **Explorer** | Understands basics | Modify YAML, build automations, scenes, scripts |
| 🔴 **Advanced** | Writes YAML from scratch | Jinja2 templates, REST API, Node-RED, VLANs |

Toggle in the header. Hides advanced content so newbies don't get overwhelmed.

---

## 🏗️ 6 Projects

| # | Project | Level | Devices | What it does |
|---|---|---|---|---|
| 1 | 🌡️ **Climate Monitor** | 🟢 | ESP32 temp sensor | Gauge card + automation: notify if > 30°C |
| 2 | 💡 **Smart Desk** | 🟢 | WLED + ESP32 button | Button toggles LED scenes, color picker |
| 3 | 🚪 **Door Alert** | 🟡 | ESP32 reed switch | Phone notification, history log, night-only condition |
| 4 | 🌅 **Sunrise Sim** | 🟡 | WLED strip | Gradual warm LEDs at 7am, bedtime scene |
| 5 | 🎮 **micro:bit Commander** | 🟡 | micro:bit + ESP32 + WLED | Gestures control everything |
| 6 | 🏠 **Full Smart Room** | 🔴 | All devices | Sensors + LEDs + buttons + voice + automations + dashboard |

---

## 🏆 Quest System

| Quest | Level | Badge |
|---|---|---|
| ⚡ Deploy HA | 🟢 | 🧠 Brain Builder |
| 🔌 Connect first device | 🟢 | 🔌 Connector |
| 📊 Build dashboard (3 cards) | 🟢 | 📊 Dashboard Designer |
| ⚡ Create automation | 🟡 | ⚡ Automator |
| 🎭 Save a scene | 🟡 | 🎭 Scene Director |
| 📝 Write YAML by hand | 🟡 | 📝 YAML Master |
| 🗣️ Voice control | 🔴 | 🗣️ Voice Commander |
| 🏠 Full smart room | 🔴 | 🏠 Smart Home Architect |

---

## 🎨 9 Themes

| Theme | Vibe |
|---|---|
| 🌙 Stealth | Dark hacker — green on black |
| ⚡ Neon | Cyberpunk — cyan on indigo |
| ☁️ Arctic | Clean light — blue on white |
| 🔥 Blaze | Warm light — orange on cream |
| 🏠 HA Blue | Home Assistant official — HA blue on navy |
| 🌲 Forest | Nature — leaf green on deep green |
| ⚔️ Tactical | Military — amber/gold on olive |
| 🌊 Deep Sea | Submarine — teal on abyss blue |
| 🕌 Medina | Islamic heritage — warm gold on oud-brown |

---

## 🔌 Entity Simulator

The web app has ~20 fake devices that behave like a real HA instance. States drift over time — temperature changes, lights remember toggles. All pages share the same state.

```
🏠 Home
├── 🌡️ sensor.esp32_temperature    → 23.4°C
├── 🌡️ sensor.esp32_humidity       → 62%
├── 💡 light.wled_strip             → on, #ff4500
├── 💡 light.desk_lamp              → on, 60%
├── 🔘 switch.smart_plug            → on
├── 🔘 switch.fan                   → off
├── 🚪 binary_sensor.door           → closed
├── 🎮 sensor.microbit_gesture      → none
├── 🌤️ weather.home                 → Sunny, 18°C
└── 🎵 media_player.speaker         → paused
```

Click any entity → state, attributes, history sparkline, available services.

---

## 🤖 micro:bit as Smart Home Remote

| Gesture | HA Action |
|---|---|
| Tilt left/right | Previous/next scene |
| Tilt forward/back | Brightness up/down |
| Press A | "Movie Night" scene |
| Press B | "Study Mode" scene |
| Shake | Party mode (WLED effects cycle) |
| A + B | Everything off |
| Freefall | Random scene |

---

## 🆚 The Workshop-DIY Series

| | ESPHome | WLED | Linux | **Home Assistant** |
|---|---|---|---|---|
| **Metaphor** | Build the arms | Build the eyes | Learn the language | **Build the brain** |
| **Hardware** | ESP32-C3 | ESP32-C3 + LEDs | Any computer | **Raspberry Pi 5** |
| **Cost** | ~$15 | ~$8 | $0 | **~$103 (or $0)** |
| **Output** | Sensors, buttons | Light shows | Terminal mastery | **Smart home** |

> 💡 Each lab builds on the others. ESPHome and WLED devices auto-discover in Home Assistant. The Linux terminal skills help with HA configuration. Everything connects.

---

## 📁 Files

```
ha-kids-lab/
├── index.html      ← The web app (just open it)
├── logo.svg        ← Workshop-DIY logo
└── README.md       ← You are here
```

One file. No build. No dependencies. No API calls. Just open `index.html`.

---

## 🔗 Links

| | Link |
|---|---|
| 🏠 Home Assistant | [home-assistant.io](https://www.home-assistant.io) |
| 📖 HA Docs | [home-assistant.io/docs](https://www.home-assistant.io/docs/) |
| 🔌 Integrations | [home-assistant.io/integrations](https://www.home-assistant.io/integrations/) |
| 📊 Dashboards | [home-assistant.io/dashboards](https://www.home-assistant.io/dashboards/) |
| ⚡ Automations | [home-assistant.io/docs/automation](https://www.home-assistant.io/docs/automation/) |
| 🧩 Add-ons | [home-assistant.io/addons](https://www.home-assistant.io/addons/) |
| 💬 HA Community | [community.home-assistant.io](https://community.home-assistant.io) |
| 🔬 ESPHome Kids Lab | [github.com/abourdim/esp32-c3-kids-lab](https://github.com/abourdim/esp32-c3-kids-lab) |
| 💡 WLED Kids Lab | [github.com/abourdim/wled-kids-lab](https://github.com/abourdim/wled-kids-lab) |
| 🐧 Linux Kids Lab | [github.com/abourdim/linux-kids-lab](https://github.com/abourdim/linux-kids-lab) |

---

## 🙏 Credits

Built on [Home Assistant](https://github.com/home-assistant) — incredible open-source smart home platform.

Web app built for the [Workshop-DIY](https://github.com/abourdim) kids electronics program.

---

<p align="center">
  <strong>Built for kids who like to build things.</strong><br>
  <em>Workshop-DIY · 2026</em>
</p>
