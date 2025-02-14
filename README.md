# Home Assistant Config

![Project Maintenance][maintenance-shield]
[![License][license-shield]](LICENSE)

[![GitHub Activity][commits-shield]][commits]
[![GitHub Last Commit][last-commit-shield]][commits]

![GitHub Stars][stars-shield]
![GitHub Watchers][watchers-shield]
![GitHub Forks][forks-shield]

[!["Buy Me A Coffee"](https://www.buymeacoffee.com/assets/img/custom_images/orange_img.png)](https://www.buymeacoffee.com/my7nmfcm92k)

This is my Home Assistant documentation, updated on 2025-02-14.

I used Home Assistant in 2018 and then migrated to Apple Home.

I started using Home Assistant again in 2022. Now, it has grown significantly, with a total of 1180 entities for now.

If you need more insights from my smart home other than auto generated document, Find below:

<p align="center">
<a href="docs/automations.md"><img src="https://img.shields.io/badge/Automations-purple" alt="Automation: The magic behind the scenes"></a>
<a href="docs/dashboards.md"><img src="https://img.shields.io/badge/Dashboards-green" alt="Dashboards: Your data at a glance"></a>
<a href="docs/hardware.md"><img src="https://img.shields.io/badge/Hardware-blue" alt="Hardware: The muscle behind the machine"></a>
<a href="docs/software.md"><img src="https://img.shields.io/badge/Software-orange" alt="Software: The brain of the operation"></a>
<a href="docs/retired.md"><img src="https://img.shields.io/badge/Retired-black" alt="Retired: Gone but not forgotten"></a>
<a href="docs/works_to_be_done.md"><img src="https://img.shields.io/badge/Works_to_be_done-red" alt="Works to be done: The future is waiting"></a>
</p>

# Table of Content

[Screenshots](#screenshots) |
[Insights](#insights) |
[Software Integrations](#software-integrations) |
[Home Assistant Add-Ons](#home-assistant-add-ons) |
[Lovelace Dashboard](#lovelace-dashboard)

----

# Screenshots

<table>
  <tr>
    <td>
      <img alt="Pegboard" src="docs/images/wall-pad.jpg"><br>
      Wall-Pad
    </td>
    <td>
      <img alt="Power Distribution Panel" src="docs/images/power-distribution-panel.png"><br>
      Power Distribution Panel
    </td>
    <td>
      <img alt="Network and Server Rack" src="docs/images/network-and-server-rack.jpg"><br>
      Network and Server Rack
    </td>
  </tr>
  <tr>
    <td>
      <img alt="Monitoring Dashboard" src="www/lovelace.jpg"><br>
      Lovelace Dashboard
    </td>
    <td>
      <img alt="Zigbee Network Visualization" src="www/network-map.png"><br>
      Network Visualization
    </td>
    <td>
      <img alt="Energy Dashboard" src="www/lovelace-energy.png"><br>
      Energy Dashboard
    </td>
  </tr>
</table>

# Insights

Domain | Value
-- | --
automations | 27
binary_sensors | 131
device_trackers | 7
lights | 10
media_players | 16
sensors | 721
switches | 35
switches | 35
others | 233
**Total** | **1180**


Component | Version
-- | --
Home Assistant Core | 2025.2.3
Supervisor | 2025.02.1
Operating System | 14.2

# Software Integrations

## Core Integrations

<details>

Integration | Configuration
--|--
[<img src="https://brands.home-assistant.io/_/seventeentrack/icon.png" height="24"/>](https://brands.home-assistant.io/_/seventeentrack/dark_icon.png#gh-dark-mode-only)[<img src="https://brands.home-assistant.io/_/seventeentrack/icon.png" height="24"/>](https://brands.home-assistant.io/_/seventeentrack/icon.png#gh-light-mode-only) [17TRACK](https://home-assistant.io/integrations/seventeentrack) | Config flow[^1]
[<img src="https://brands.home-assistant.io/_/alert/icon.png" height="24"/>](https://brands.home-assistant.io/_/alert/dark_icon.png#gh-dark-mode-only)[<img src="https://brands.home-assistant.io/_/alert/icon.png" height="24"/>](https://brands.home-assistant.io/_/alert/icon.png#gh-light-mode-only) [alert](https://home-assistant.io/integrations/alert) | [./packages/alerts_and_notifications.yaml](./packages/alerts_and_notifications.yaml)
[<img src="https://brands.home-assistant.io/_/anthropic/icon.png" height="24"/>](https://brands.home-assistant.io/_/anthropic/dark_icon.png#gh-dark-mode-only)[<img src="https://brands.home-assistant.io/_/anthropic/icon.png" height="24"/>](https://brands.home-assistant.io/_/anthropic/icon.png#gh-light-mode-only) [Anthropic Conversation](https://home-assistant.io/integrations/anthropic) | Config flow[^1]
[<img src="https://brands.home-assistant.io/_/icloud/icon.png" height="24"/>](https://brands.home-assistant.io/_/icloud/dark_icon.png#gh-dark-mode-only)[<img src="https://brands.home-assistant.io/_/icloud/icon.png" height="24"/>](https://brands.home-assistant.io/_/icloud/icon.png#gh-light-mode-only) [Apple iCloud](https://home-assistant.io/integrations/icloud) | Config flow[^1]
[<img src="https://brands.home-assistant.io/_/apple_tv/icon.png" height="24"/>](https://brands.home-assistant.io/_/apple_tv/dark_icon.png#gh-dark-mode-only)[<img src="https://brands.home-assistant.io/_/apple_tv/icon.png" height="24"/>](https://brands.home-assistant.io/_/apple_tv/icon.png#gh-light-mode-only) [Apple TV](https://home-assistant.io/integrations/apple_tv) | Config flow[^1]
[<img src="https://brands.home-assistant.io/_/automation/icon.png" height="24"/>](https://brands.home-assistant.io/_/automation/dark_icon.png#gh-dark-mode-only)[<img src="https://brands.home-assistant.io/_/automation/icon.png" height="24"/>](https://brands.home-assistant.io/_/automation/icon.png#gh-light-mode-only) [Automation](https://home-assistant.io/integrations/automation) | [./automations.yaml](./automations.yaml)
[<img src="https://brands.home-assistant.io/_/bluetooth/icon.png" height="24"/>](https://brands.home-assistant.io/_/bluetooth/dark_icon.png#gh-dark-mode-only)[<img src="https://brands.home-assistant.io/_/bluetooth/icon.png" height="24"/>](https://brands.home-assistant.io/_/bluetooth/icon.png#gh-light-mode-only) [Bluetooth](https://home-assistant.io/integrations/bluetooth) | Config flow[^1]
[<img src="https://brands.home-assistant.io/_/caldav/icon.png" height="24"/>](https://brands.home-assistant.io/_/caldav/dark_icon.png#gh-dark-mode-only)[<img src="https://brands.home-assistant.io/_/caldav/icon.png" height="24"/>](https://brands.home-assistant.io/_/caldav/icon.png#gh-light-mode-only) [CalDAV](https://home-assistant.io/integrations/caldav) | Config flow[^1]
[<img src="https://brands.home-assistant.io/_/calendar/icon.png" height="24"/>](https://brands.home-assistant.io/_/calendar/dark_icon.png#gh-dark-mode-only)[<img src="https://brands.home-assistant.io/_/calendar/icon.png" height="24"/>](https://brands.home-assistant.io/_/calendar/icon.png#gh-light-mode-only) [Calendar](https://home-assistant.io/integrations/calendar) | Config flow[^1]
[<img src="https://brands.home-assistant.io/_/cert_expiry/icon.png" height="24"/>](https://brands.home-assistant.io/_/cert_expiry/dark_icon.png#gh-dark-mode-only)[<img src="https://brands.home-assistant.io/_/cert_expiry/icon.png" height="24"/>](https://brands.home-assistant.io/_/cert_expiry/icon.png#gh-light-mode-only) [Certificate Expiry](https://home-assistant.io/integrations/cert_expiry) | Config flow[^1]
[<img src="https://brands.home-assistant.io/_/command_line/icon.png" height="24"/>](https://brands.home-assistant.io/_/command_line/dark_icon.png#gh-dark-mode-only)[<img src="https://brands.home-assistant.io/_/command_line/icon.png" height="24"/>](https://brands.home-assistant.io/_/command_line/icon.png#gh-light-mode-only) [Command Line](https://home-assistant.io/integrations/command_line) | Config flow[^1]
[<img src="https://brands.home-assistant.io/_/default_config/icon.png" height="24"/>](https://brands.home-assistant.io/_/default_config/dark_icon.png#gh-dark-mode-only)[<img src="https://brands.home-assistant.io/_/default_config/icon.png" height="24"/>](https://brands.home-assistant.io/_/default_config/icon.png#gh-light-mode-only) [Default Config](https://home-assistant.io/integrations/default_config) | [./configuration.yaml](./configuration.yaml)
[<img src="https://brands.home-assistant.io/_/discord/icon.png" height="24"/>](https://brands.home-assistant.io/_/discord/dark_icon.png#gh-dark-mode-only)[<img src="https://brands.home-assistant.io/_/discord/icon.png" height="24"/>](https://brands.home-assistant.io/_/discord/icon.png#gh-light-mode-only) [Discord](https://home-assistant.io/integrations/discord) | Config flow[^1]
[<img src="https://brands.home-assistant.io/_/doods/icon.png" height="24"/>](https://brands.home-assistant.io/_/doods/dark_icon.png#gh-dark-mode-only)[<img src="https://brands.home-assistant.io/_/doods/icon.png" height="24"/>](https://brands.home-assistant.io/_/doods/icon.png#gh-light-mode-only) [DOODS - Dedicated Open Object Detection Service](https://home-assistant.io/integrations/doods) | [./packages/doods_image_processing.yaml](./packages/doods_image_processing.yaml)
[<img src="https://brands.home-assistant.io/_/co2signal/icon.png" height="24"/>](https://brands.home-assistant.io/_/co2signal/dark_icon.png#gh-dark-mode-only)[<img src="https://brands.home-assistant.io/_/co2signal/icon.png" height="24"/>](https://brands.home-assistant.io/_/co2signal/icon.png#gh-light-mode-only) [Electricity Maps](https://home-assistant.io/integrations/co2signal) | Config flow[^1]
[<img src="https://brands.home-assistant.io/_/esphome/icon.png" height="24"/>](https://brands.home-assistant.io/_/esphome/dark_icon.png#gh-dark-mode-only)[<img src="https://brands.home-assistant.io/_/esphome/icon.png" height="24"/>](https://brands.home-assistant.io/_/esphome/icon.png#gh-light-mode-only) [ESPHome](https://home-assistant.io/integrations/esphome) | Config flow[^1]
[<img src="https://brands.home-assistant.io/_/feedreader/icon.png" height="24"/>](https://brands.home-assistant.io/_/feedreader/dark_icon.png#gh-dark-mode-only)[<img src="https://brands.home-assistant.io/_/feedreader/icon.png" height="24"/>](https://brands.home-assistant.io/_/feedreader/icon.png#gh-light-mode-only) [Feedreader](https://home-assistant.io/integrations/feedreader) | Config flow[^1]
[<img src="https://brands.home-assistant.io/_/frontend/icon.png" height="24"/>](https://brands.home-assistant.io/_/frontend/dark_icon.png#gh-dark-mode-only)[<img src="https://brands.home-assistant.io/_/frontend/icon.png" height="24"/>](https://brands.home-assistant.io/_/frontend/icon.png#gh-light-mode-only) [Frontend](https://home-assistant.io/integrations/frontend) | [./configuration.yaml](./configuration.yaml)
[<img src="https://brands.home-assistant.io/_/fully_kiosk/icon.png" height="24"/>](https://brands.home-assistant.io/_/fully_kiosk/dark_icon.png#gh-dark-mode-only)[<img src="https://brands.home-assistant.io/_/fully_kiosk/icon.png" height="24"/>](https://brands.home-assistant.io/_/fully_kiosk/icon.png#gh-light-mode-only) [Fully Kiosk Browser](https://home-assistant.io/integrations/fully_kiosk) | Config flow[^1]
[<img src="https://brands.home-assistant.io/_/generic/icon.png" height="24"/>](https://brands.home-assistant.io/_/generic/dark_icon.png#gh-dark-mode-only)[<img src="https://brands.home-assistant.io/_/generic/icon.png" height="24"/>](https://brands.home-assistant.io/_/generic/icon.png#gh-light-mode-only) [Generic Camera](https://home-assistant.io/integrations/generic) | Config flow[^1]
[<img src="https://brands.home-assistant.io/_/github/icon.png" height="24"/>](https://brands.home-assistant.io/_/github/dark_icon.png#gh-dark-mode-only)[<img src="https://brands.home-assistant.io/_/github/icon.png" height="24"/>](https://brands.home-assistant.io/_/github/icon.png#gh-light-mode-only) [GitHub](https://home-assistant.io/integrations/github) | Config flow[^1]
[<img src="https://brands.home-assistant.io/_/google/icon.png" height="24"/>](https://brands.home-assistant.io/_/google/dark_icon.png#gh-dark-mode-only)[<img src="https://brands.home-assistant.io/_/google/icon.png" height="24"/>](https://brands.home-assistant.io/_/google/icon.png#gh-light-mode-only) [Google Calendar](https://home-assistant.io/integrations/google) | Config flow[^1]
[<img src="https://brands.home-assistant.io/_/google_drive/icon.png" height="24"/>](https://brands.home-assistant.io/_/google_drive/dark_icon.png#gh-dark-mode-only)[<img src="https://brands.home-assistant.io/_/google_drive/icon.png" height="24"/>](https://brands.home-assistant.io/_/google_drive/icon.png#gh-light-mode-only) [Google Drive](https://home-assistant.io/integrations/google_drive) | Config flow[^1]
[<img src="https://brands.home-assistant.io/_/google_generative_ai_conversation/icon.png" height="24"/>](https://brands.home-assistant.io/_/google_generative_ai_conversation/dark_icon.png#gh-dark-mode-only)[<img src="https://brands.home-assistant.io/_/google_generative_ai_conversation/icon.png" height="24"/>](https://brands.home-assistant.io/_/google_generative_ai_conversation/icon.png#gh-light-mode-only) [Google Generative AI Conversation](https://home-assistant.io/integrations/google_generative_ai_conversation) | Config flow[^1]
[<img src="https://brands.home-assistant.io/_/google_translate/icon.png" height="24"/>](https://brands.home-assistant.io/_/google_translate/dark_icon.png#gh-dark-mode-only)[<img src="https://brands.home-assistant.io/_/google_translate/icon.png" height="24"/>](https://brands.home-assistant.io/_/google_translate/icon.png#gh-light-mode-only) [Google Translate text-to-speech](https://home-assistant.io/integrations/google_translate) | Config flow[^1]
[<img src="https://brands.home-assistant.io/_/history/icon.png" height="24"/>](https://brands.home-assistant.io/_/history/dark_icon.png#gh-dark-mode-only)[<img src="https://brands.home-assistant.io/_/history/icon.png" height="24"/>](https://brands.home-assistant.io/_/history/icon.png#gh-light-mode-only) [History](https://home-assistant.io/integrations/history) | Config flow[^1]
[<img src="https://brands.home-assistant.io/_/holiday/icon.png" height="24"/>](https://brands.home-assistant.io/_/holiday/dark_icon.png#gh-dark-mode-only)[<img src="https://brands.home-assistant.io/_/holiday/icon.png" height="24"/>](https://brands.home-assistant.io/_/holiday/icon.png#gh-light-mode-only) [Holiday](https://home-assistant.io/integrations/holiday) | Config flow[^1]
[<img src="https://brands.home-assistant.io/_/homeassistant/icon.png" height="24"/>](https://brands.home-assistant.io/_/homeassistant/dark_icon.png#gh-dark-mode-only)[<img src="https://brands.home-assistant.io/_/homeassistant/icon.png" height="24"/>](https://brands.home-assistant.io/_/homeassistant/icon.png#gh-light-mode-only) [Home Assistant Core Integration](https://home-assistant.io/integrations/homeassistant) | [./configuration.yaml](./configuration.yaml)
[<img src="https://brands.home-assistant.io/_/http/icon.png" height="24"/>](https://brands.home-assistant.io/_/http/dark_icon.png#gh-dark-mode-only)[<img src="https://brands.home-assistant.io/_/http/icon.png" height="24"/>](https://brands.home-assistant.io/_/http/icon.png#gh-light-mode-only) [HTTP](https://home-assistant.io/integrations/http) | [./configuration.yaml](./configuration.yaml)
[<img src="https://brands.home-assistant.io/_/imap/icon.png" height="24"/>](https://brands.home-assistant.io/_/imap/dark_icon.png#gh-dark-mode-only)[<img src="https://brands.home-assistant.io/_/imap/icon.png" height="24"/>](https://brands.home-assistant.io/_/imap/icon.png#gh-light-mode-only) [IMAP](https://home-assistant.io/integrations/imap) | [./packages/imap_content.yaml](./packages/imap_content.yaml)
[<img src="https://brands.home-assistant.io/_/lastfm/icon.png" height="24"/>](https://brands.home-assistant.io/_/lastfm/dark_icon.png#gh-dark-mode-only)[<img src="https://brands.home-assistant.io/_/lastfm/icon.png" height="24"/>](https://brands.home-assistant.io/_/lastfm/icon.png#gh-light-mode-only) [Last.fm](https://home-assistant.io/integrations/lastfm) | Config flow[^1]
[<img src="https://brands.home-assistant.io/_/lg_thinq/icon.png" height="24"/>](https://brands.home-assistant.io/_/lg_thinq/dark_icon.png#gh-dark-mode-only)[<img src="https://brands.home-assistant.io/_/lg_thinq/icon.png" height="24"/>](https://brands.home-assistant.io/_/lg_thinq/icon.png#gh-light-mode-only) [LG ThinQ](https://home-assistant.io/integrations/lg_thinq) | Config flow[^1]
[<img src="https://brands.home-assistant.io/_/local_calendar/icon.png" height="24"/>](https://brands.home-assistant.io/_/local_calendar/dark_icon.png#gh-dark-mode-only)[<img src="https://brands.home-assistant.io/_/local_calendar/icon.png" height="24"/>](https://brands.home-assistant.io/_/local_calendar/icon.png#gh-light-mode-only) [Local Calendar](https://home-assistant.io/integrations/local_calendar) | Config flow[^1]
[<img src="https://brands.home-assistant.io/_/local_todo/icon.png" height="24"/>](https://brands.home-assistant.io/_/local_todo/dark_icon.png#gh-dark-mode-only)[<img src="https://brands.home-assistant.io/_/local_todo/icon.png" height="24"/>](https://brands.home-assistant.io/_/local_todo/icon.png#gh-light-mode-only) [Local To Do](https://home-assistant.io/integrations/local_todo) | Config flow[^1]
[<img src="https://brands.home-assistant.io/_/logger/icon.png" height="24"/>](https://brands.home-assistant.io/_/logger/dark_icon.png#gh-dark-mode-only)[<img src="https://brands.home-assistant.io/_/logger/icon.png" height="24"/>](https://brands.home-assistant.io/_/logger/icon.png#gh-light-mode-only) [Logger](https://home-assistant.io/integrations/logger) | [./configuration.yaml](./configuration.yaml)
[<img src="https://brands.home-assistant.io/_/lovelace/icon.png" height="24"/>](https://brands.home-assistant.io/_/lovelace/dark_icon.png#gh-dark-mode-only)[<img src="https://brands.home-assistant.io/_/lovelace/icon.png" height="24"/>](https://brands.home-assistant.io/_/lovelace/icon.png#gh-light-mode-only) [Lovelace](https://home-assistant.io/integrations/lovelace) | [./ui-lovelace.yaml](./ui-lovelace.yaml)
[<img src="https://brands.home-assistant.io/_/manual/icon.png" height="24"/>](https://brands.home-assistant.io/_/manual/dark_icon.png#gh-dark-mode-only)[<img src="https://brands.home-assistant.io/_/manual/icon.png" height="24"/>](https://brands.home-assistant.io/_/manual/icon.png#gh-light-mode-only) [Manual Alarm control panel](https://home-assistant.io/integrations/manual) | [./package/alarm_control_panel.yaml](./package/alarm_control_panel.yaml)
[<img src="https://brands.home-assistant.io/_/matter/icon.png" height="24"/>](https://brands.home-assistant.io/_/matter/dark_icon.png#gh-dark-mode-only)[<img src="https://brands.home-assistant.io/_/matter/icon.png" height="24"/>](https://brands.home-assistant.io/_/matter/icon.png#gh-light-mode-only) [Matter (BETA)](https://home-assistant.io/integrations/matter) | Config flow[^1]
[<img src="https://brands.home-assistant.io/_/mobile_app/icon.png" height="24"/>](https://brands.home-assistant.io/_/mobile_app/dark_icon.png#gh-dark-mode-only)[<img src="https://brands.home-assistant.io/_/mobile_app/icon.png" height="24"/>](https://brands.home-assistant.io/_/mobile_app/icon.png#gh-light-mode-only) [Mobile App](https://home-assistant.io/integrations/mobile_app) | Config flow[^1]
[<img src="https://brands.home-assistant.io/_/moon/icon.png" height="24"/>](https://brands.home-assistant.io/_/moon/dark_icon.png#gh-dark-mode-only)[<img src="https://brands.home-assistant.io/_/moon/icon.png" height="24"/>](https://brands.home-assistant.io/_/moon/icon.png#gh-light-mode-only) [Moon](https://home-assistant.io/integrations/moon) | Config flow[^1]
[<img src="https://brands.home-assistant.io/_/mqtt/icon.png" height="24"/>](https://brands.home-assistant.io/_/mqtt/dark_icon.png#gh-dark-mode-only)[<img src="https://brands.home-assistant.io/_/mqtt/icon.png" height="24"/>](https://brands.home-assistant.io/_/mqtt/icon.png#gh-light-mode-only) [MQTT](https://home-assistant.io/integrations/mqtt) | Config flow[^1]
[<img src="https://brands.home-assistant.io/_/music_assistant/icon.png" height="24"/>](https://brands.home-assistant.io/_/music_assistant/dark_icon.png#gh-dark-mode-only)[<img src="https://brands.home-assistant.io/_/music_assistant/icon.png" height="24"/>](https://brands.home-assistant.io/_/music_assistant/icon.png#gh-light-mode-only) [Music Assistant](https://home-assistant.io/integrations/music_assistant) | Config flow[^1]
[<img src="https://brands.home-assistant.io/_/my/icon.png" height="24"/>](https://brands.home-assistant.io/_/my/dark_icon.png#gh-dark-mode-only)[<img src="https://brands.home-assistant.io/_/my/icon.png" height="24"/>](https://brands.home-assistant.io/_/my/icon.png#gh-light-mode-only) [My Home Assistant](https://home-assistant.io/integrations/my) | [./configuration.yaml](./configuration.yaml)
[<img src="https://brands.home-assistant.io/_/notify/icon.png" height="24"/>](https://brands.home-assistant.io/_/notify/dark_icon.png#gh-dark-mode-only)[<img src="https://brands.home-assistant.io/_/notify/icon.png" height="24"/>](https://brands.home-assistant.io/_/notify/icon.png#gh-light-mode-only) [notify](https://home-assistant.io/integrations/notify) | [./packages/alerts_and_notifications.yaml](./packages/alerts_and_notifications.yaml)
[<img src="https://brands.home-assistant.io/_/otbr/icon.png" height="24"/>](https://brands.home-assistant.io/_/otbr/dark_icon.png#gh-dark-mode-only)[<img src="https://brands.home-assistant.io/_/otbr/icon.png" height="24"/>](https://brands.home-assistant.io/_/otbr/icon.png#gh-light-mode-only) [Open Thread Border Router](https://home-assistant.io/integrations/otbr) | Config flow[^1]
[<img src="https://brands.home-assistant.io/_/openai_conversation/icon.png" height="24"/>](https://brands.home-assistant.io/_/openai_conversation/dark_icon.png#gh-dark-mode-only)[<img src="https://brands.home-assistant.io/_/openai_conversation/icon.png" height="24"/>](https://brands.home-assistant.io/_/openai_conversation/icon.png#gh-light-mode-only) [OpenAI Conversation](https://home-assistant.io/integrations/openai_conversation) | Config flow[^1]
[<img src="https://brands.home-assistant.io/_/oralb/icon.png" height="24"/>](https://brands.home-assistant.io/_/oralb/dark_icon.png#gh-dark-mode-only)[<img src="https://brands.home-assistant.io/_/oralb/icon.png" height="24"/>](https://brands.home-assistant.io/_/oralb/icon.png#gh-light-mode-only) [Oral-B](https://home-assistant.io/integrations/oralb) | Config flow[^1]
[<img src="https://brands.home-assistant.io/_/ping/icon.png" height="24"/>](https://brands.home-assistant.io/_/ping/dark_icon.png#gh-dark-mode-only)[<img src="https://brands.home-assistant.io/_/ping/icon.png" height="24"/>](https://brands.home-assistant.io/_/ping/icon.png#gh-light-mode-only) [Ping (ICMP)](https://home-assistant.io/integrations/ping) | Config flow[^1]
[<img src="https://brands.home-assistant.io/_/plex/icon.png" height="24"/>](https://brands.home-assistant.io/_/plex/dark_icon.png#gh-dark-mode-only)[<img src="https://brands.home-assistant.io/_/plex/icon.png" height="24"/>](https://brands.home-assistant.io/_/plex/icon.png#gh-light-mode-only) [Plex Media Server](https://home-assistant.io/integrations/plex) | Config flow[^1]
[<img src="https://brands.home-assistant.io/_/private_ble_device/icon.png" height="24"/>](https://brands.home-assistant.io/_/private_ble_device/dark_icon.png#gh-dark-mode-only)[<img src="https://brands.home-assistant.io/_/private_ble_device/icon.png" height="24"/>](https://brands.home-assistant.io/_/private_ble_device/icon.png#gh-light-mode-only) [Private BLE Device](https://home-assistant.io/integrations/private_ble_device) | Config flow[^1]
[<img src="https://brands.home-assistant.io/_/profiler/icon.png" height="24"/>](https://brands.home-assistant.io/_/profiler/dark_icon.png#gh-dark-mode-only)[<img src="https://brands.home-assistant.io/_/profiler/icon.png" height="24"/>](https://brands.home-assistant.io/_/profiler/icon.png#gh-light-mode-only) [Profiler](https://home-assistant.io/integrations/profiler) | Config flow[^1]
[<img src="https://brands.home-assistant.io/_/prometheus/icon.png" height="24"/>](https://brands.home-assistant.io/_/prometheus/dark_icon.png#gh-dark-mode-only)[<img src="https://brands.home-assistant.io/_/prometheus/icon.png" height="24"/>](https://brands.home-assistant.io/_/prometheus/icon.png#gh-light-mode-only) [Prometheus](https://home-assistant.io/integrations/prometheus) | [./configuration.yaml](./configuration.yaml)
[<img src="https://brands.home-assistant.io/_/proximity/icon.png" height="24"/>](https://brands.home-assistant.io/_/proximity/dark_icon.png#gh-dark-mode-only)[<img src="https://brands.home-assistant.io/_/proximity/icon.png" height="24"/>](https://brands.home-assistant.io/_/proximity/icon.png#gh-light-mode-only) [Proximity](https://home-assistant.io/integrations/proximity) | Config flow[^1]
[<img src="https://brands.home-assistant.io/_/recorder/icon.png" height="24"/>](https://brands.home-assistant.io/_/recorder/dark_icon.png#gh-dark-mode-only)[<img src="https://brands.home-assistant.io/_/recorder/icon.png" height="24"/>](https://brands.home-assistant.io/_/recorder/icon.png#gh-light-mode-only) [Recorder](https://home-assistant.io/integrations/recorder) | [./configuration.yaml](./configuration.yaml)
[<img src="https://brands.home-assistant.io/_/scene/icon.png" height="24"/>](https://brands.home-assistant.io/_/scene/dark_icon.png#gh-dark-mode-only)[<img src="https://brands.home-assistant.io/_/scene/icon.png" height="24"/>](https://brands.home-assistant.io/_/scene/icon.png#gh-light-mode-only) [Scene](https://home-assistant.io/integrations/scene) | [./scenes.yaml](./scenes.yaml)
[<img src="https://brands.home-assistant.io/_/script/icon.png" height="24"/>](https://brands.home-assistant.io/_/script/dark_icon.png#gh-dark-mode-only)[<img src="https://brands.home-assistant.io/_/script/icon.png" height="24"/>](https://brands.home-assistant.io/_/script/icon.png#gh-light-mode-only) [Script](https://home-assistant.io/integrations/script) | [./scripts.yaml](./scripts.yaml)
[<img src="https://brands.home-assistant.io/_/season/icon.png" height="24"/>](https://brands.home-assistant.io/_/season/dark_icon.png#gh-dark-mode-only)[<img src="https://brands.home-assistant.io/_/season/icon.png" height="24"/>](https://brands.home-assistant.io/_/season/icon.png#gh-light-mode-only) [Season](https://home-assistant.io/integrations/season) | Config flow[^1]
[<img src="https://brands.home-assistant.io/_/shell_command/icon.png" height="24"/>](https://brands.home-assistant.io/_/shell_command/dark_icon.png#gh-dark-mode-only)[<img src="https://brands.home-assistant.io/_/shell_command/icon.png" height="24"/>](https://brands.home-assistant.io/_/shell_command/icon.png#gh-light-mode-only) [Shell Command](https://home-assistant.io/integrations/shell_command) | [./configuration.yaml](./configuration.yaml)
[<img src="https://brands.home-assistant.io/_/smartthings/icon.png" height="24"/>](https://brands.home-assistant.io/_/smartthings/dark_icon.png#gh-dark-mode-only)[<img src="https://brands.home-assistant.io/_/smartthings/icon.png" height="24"/>](https://brands.home-assistant.io/_/smartthings/icon.png#gh-light-mode-only) [SmartThings](https://home-assistant.io/integrations/smartthings) | Config flow[^1]
[<img src="https://brands.home-assistant.io/_/sql/icon.png" height="24"/>](https://brands.home-assistant.io/_/sql/dark_icon.png#gh-dark-mode-only)[<img src="https://brands.home-assistant.io/_/sql/icon.png" height="24"/>](https://brands.home-assistant.io/_/sql/icon.png#gh-light-mode-only) [SQL](https://home-assistant.io/integrations/sql) | Config flow[^1]
[<img src="https://brands.home-assistant.io/_/steam_online/icon.png" height="24"/>](https://brands.home-assistant.io/_/steam_online/dark_icon.png#gh-dark-mode-only)[<img src="https://brands.home-assistant.io/_/steam_online/icon.png" height="24"/>](https://brands.home-assistant.io/_/steam_online/icon.png#gh-light-mode-only) [Steam](https://home-assistant.io/integrations/steam_online) | Config flow[^1]
[<img src="https://brands.home-assistant.io/_/sun/icon.png" height="24"/>](https://brands.home-assistant.io/_/sun/dark_icon.png#gh-dark-mode-only)[<img src="https://brands.home-assistant.io/_/sun/icon.png" height="24"/>](https://brands.home-assistant.io/_/sun/icon.png#gh-light-mode-only) [Sun](https://home-assistant.io/integrations/sun) | Config flow[^1]
[<img src="https://brands.home-assistant.io/_/hassio/icon.png" height="24"/>](https://brands.home-assistant.io/_/hassio/dark_icon.png#gh-dark-mode-only)[<img src="https://brands.home-assistant.io/_/hassio/icon.png" height="24"/>](https://brands.home-assistant.io/_/hassio/icon.png#gh-light-mode-only) [Supervisor](https://home-assistant.io/integrations/hassio) | Config flow[^1]
[<img src="https://brands.home-assistant.io/_/systemmonitor/icon.png" height="24"/>](https://brands.home-assistant.io/_/systemmonitor/dark_icon.png#gh-dark-mode-only)[<img src="https://brands.home-assistant.io/_/systemmonitor/icon.png" height="24"/>](https://brands.home-assistant.io/_/systemmonitor/icon.png#gh-light-mode-only) [System Monitor](https://home-assistant.io/integrations/systemmonitor) | Config flow[^1]
[<img src="https://brands.home-assistant.io/_/template/icon.png" height="24"/>](https://brands.home-assistant.io/_/template/dark_icon.png#gh-dark-mode-only)[<img src="https://brands.home-assistant.io/_/template/icon.png" height="24"/>](https://brands.home-assistant.io/_/template/icon.png#gh-light-mode-only) [Template](https://home-assistant.io/integrations/template) | [./packages](./packages)
[<img src="https://brands.home-assistant.io/_/thread/icon.png" height="24"/>](https://brands.home-assistant.io/_/thread/dark_icon.png#gh-dark-mode-only)[<img src="https://brands.home-assistant.io/_/thread/icon.png" height="24"/>](https://brands.home-assistant.io/_/thread/icon.png#gh-light-mode-only) [Thread](https://home-assistant.io/integrations/thread) | Config flow[^1]
[<img src="https://brands.home-assistant.io/_/time_date/icon.png" height="24"/>](https://brands.home-assistant.io/_/time_date/dark_icon.png#gh-dark-mode-only)[<img src="https://brands.home-assistant.io/_/time_date/icon.png" height="24"/>](https://brands.home-assistant.io/_/time_date/icon.png#gh-light-mode-only) [Time & Date](https://home-assistant.io/integrations/time_date) | Config flow[^1]
[<img src="https://brands.home-assistant.io/_/todoist/icon.png" height="24"/>](https://brands.home-assistant.io/_/todoist/dark_icon.png#gh-dark-mode-only)[<img src="https://brands.home-assistant.io/_/todoist/icon.png" height="24"/>](https://brands.home-assistant.io/_/todoist/icon.png#gh-light-mode-only) [Todoist](https://home-assistant.io/integrations/todoist) | Config flow[^1]
[<img src="https://brands.home-assistant.io/_/uptime/icon.png" height="24"/>](https://brands.home-assistant.io/_/uptime/dark_icon.png#gh-dark-mode-only)[<img src="https://brands.home-assistant.io/_/uptime/icon.png" height="24"/>](https://brands.home-assistant.io/_/uptime/icon.png#gh-light-mode-only) [Uptime](https://home-assistant.io/integrations/uptime) | Config flow[^1]
[<img src="https://brands.home-assistant.io/_/version/icon.png" height="24"/>](https://brands.home-assistant.io/_/version/dark_icon.png#gh-dark-mode-only)[<img src="https://brands.home-assistant.io/_/version/icon.png" height="24"/>](https://brands.home-assistant.io/_/version/icon.png#gh-light-mode-only) [Version](https://home-assistant.io/integrations/version) | Config flow[^1]
[<img src="https://brands.home-assistant.io/_/withings/icon.png" height="24"/>](https://brands.home-assistant.io/_/withings/dark_icon.png#gh-dark-mode-only)[<img src="https://brands.home-assistant.io/_/withings/icon.png" height="24"/>](https://brands.home-assistant.io/_/withings/icon.png#gh-light-mode-only) [Withings](https://home-assistant.io/integrations/withings) | Config flow[^1]
[<img src="https://brands.home-assistant.io/_/workday/icon.png" height="24"/>](https://brands.home-assistant.io/_/workday/dark_icon.png#gh-dark-mode-only)[<img src="https://brands.home-assistant.io/_/workday/icon.png" height="24"/>](https://brands.home-assistant.io/_/workday/icon.png#gh-light-mode-only) [Workday](https://home-assistant.io/integrations/workday) | Config flow[^1]
[<img src="https://brands.home-assistant.io/_/wyoming/icon.png" height="24"/>](https://brands.home-assistant.io/_/wyoming/dark_icon.png#gh-dark-mode-only)[<img src="https://brands.home-assistant.io/_/wyoming/icon.png" height="24"/>](https://brands.home-assistant.io/_/wyoming/icon.png#gh-light-mode-only) [Wyoming](https://home-assistant.io/integrations/wyoming) | Config flow[^1]
</details>

## Custom Components from HACS

<details>

Name | Description
-- | --
[<img src="https://brands.home-assistant.io/_/gas_station_korea/icon.png" height="24"/>](https://brands.home-assistant.io/_/gas_station_korea/dark_icon.png#gh-dark-mode-only)[<img src="https://brands.home-assistant.io/_/gas_station_korea/icon.png" height="24"/>](https://brands.home-assistant.io/_/gas_station_korea/icon.png#gh-light-mode-only) [[Kr] Gas Station Oil Price Sensor](https://github.com/GrecHouse/gas_station_korea) | Gas station oil price sensor #HA 주유소 유가 정보 센서
[<img src="https://brands.home-assistant.io/_/imazu_wall_pad/icon.png" height="24"/>](https://brands.home-assistant.io/_/imazu_wall_pad/dark_icon.png#gh-dark-mode-only)[<img src="https://brands.home-assistant.io/_/imazu_wall_pad/icon.png" height="24"/>](https://brands.home-assistant.io/_/imazu_wall_pad/icon.png#gh-light-mode-only) [[Kr] Imazu Wall Pad](https://github.com/stkang/ha-component-imazu-wall-pad) | None
[<img src="https://brands.home-assistant.io/_/map_change/icon.png" height="24"/>](https://brands.home-assistant.io/_/map_change/dark_icon.png#gh-dark-mode-only)[<img src="https://brands.home-assistant.io/_/map_change/icon.png" height="24"/>](https://brands.home-assistant.io/_/map_change/icon.png#gh-light-mode-only) [[Kr] Map Change Service](https://github.com/miumida/map_change) | Default Map to NAVER Map. Map Change Service for Home Assistant #HA
[<img src="https://brands.home-assistant.io/_/kwh_to_won/icon.png" height="24"/>](https://brands.home-assistant.io/_/kwh_to_won/dark_icon.png#gh-dark-mode-only)[<img src="https://brands.home-assistant.io/_/kwh_to_won/icon.png" height="24"/>](https://brands.home-assistant.io/_/kwh_to_won/icon.png#gh-light-mode-only) [[KR] 전기요금 계산 센서 (가정용)](https://github.com/dugurs/kwh_to_won) | 한국전력 전기요금 계산기 (가정용)
[<img src="https://brands.home-assistant.io/_/adaptive_lighting/icon.png" height="24"/>](https://brands.home-assistant.io/_/adaptive_lighting/dark_icon.png#gh-dark-mode-only)[<img src="https://brands.home-assistant.io/_/adaptive_lighting/icon.png" height="24"/>](https://brands.home-assistant.io/_/adaptive_lighting/icon.png#gh-light-mode-only) [Adaptive Lighting](https://github.com/basnijholt/adaptive-lighting) | Adaptive Lighting custom component for Home Assistant
[<img src="https://brands.home-assistant.io/_/anniversaries/icon.png" height="24"/>](https://brands.home-assistant.io/_/anniversaries/dark_icon.png#gh-dark-mode-only)[<img src="https://brands.home-assistant.io/_/anniversaries/icon.png" height="24"/>](https://brands.home-assistant.io/_/anniversaries/icon.png#gh-light-mode-only) [Anniversaries](https://github.com/pinkywafer/Anniversaries) | Anniversary Countdown Sensor for Home Assistant
[<img src="https://brands.home-assistant.io/_/discord_game/icon.png" height="24"/>](https://brands.home-assistant.io/_/discord_game/dark_icon.png#gh-dark-mode-only)[<img src="https://brands.home-assistant.io/_/discord_game/icon.png" height="24"/>](https://brands.home-assistant.io/_/discord_game/icon.png#gh-light-mode-only) [Discord Game](https://github.com/LordBoos/discord_game) | Home Assistant custom component to get online and game status of Discord users
[<img src="https://brands.home-assistant.io/_/price_tracker/icon.png" height="24"/>](https://brands.home-assistant.io/_/price_tracker/dark_icon.png#gh-dark-mode-only)[<img src="https://brands.home-assistant.io/_/price_tracker/icon.png" height="24"/>](https://brands.home-assistant.io/_/price_tracker/icon.png#gh-light-mode-only) [E Commerce Price Tracker](https://github.com/hwajin-me/hs-price-tracker) | Home Assistant - E-commerce price tracker
[<img src="https://brands.home-assistant.io/_/fireflyiii_integration/icon.png" height="24"/>](https://brands.home-assistant.io/_/fireflyiii_integration/dark_icon.png#gh-dark-mode-only)[<img src="https://brands.home-assistant.io/_/fireflyiii_integration/icon.png" height="24"/>](https://brands.home-assistant.io/_/fireflyiii_integration/icon.png#gh-light-mode-only) [Fireflyiii Integration](https://github.com/soloam/ha-fireflyiii-integration) | FireflyIII Integration for Home Assistant
[<img src="https://brands.home-assistant.io/_/fontawesome/icon.png" height="24"/>](https://brands.home-assistant.io/_/fontawesome/dark_icon.png#gh-dark-mode-only)[<img src="https://brands.home-assistant.io/_/fontawesome/icon.png" height="24"/>](https://brands.home-assistant.io/_/fontawesome/icon.png#gh-light-mode-only) [Fontawesome](https://github.com/thomasloven/hass-fontawesome) | 🔹 Use icons from fontawesome in home-assistant
[<img src="https://brands.home-assistant.io/_/readme/icon.png" height="24"/>](https://brands.home-assistant.io/_/readme/dark_icon.png#gh-dark-mode-only)[<img src="https://brands.home-assistant.io/_/readme/icon.png" height="24"/>](https://brands.home-assistant.io/_/readme/icon.png#gh-light-mode-only) [Generate Readme](https://github.com/custom-components/readme) | Use Jinja and data from Home Assistant to generate your README.md file
[<img src="https://brands.home-assistant.io/_/grocy/icon.png" height="24"/>](https://brands.home-assistant.io/_/grocy/dark_icon.png#gh-dark-mode-only)[<img src="https://brands.home-assistant.io/_/grocy/icon.png" height="24"/>](https://brands.home-assistant.io/_/grocy/icon.png#gh-light-mode-only) [Grocy Custom Component](https://github.com/custom-components/grocy) | Custom Grocy integration for Home Assistant
[<img src="https://brands.home-assistant.io/_/hacs/icon.png" height="24"/>](https://brands.home-assistant.io/_/hacs/dark_icon.png#gh-dark-mode-only)[<img src="https://brands.home-assistant.io/_/hacs/icon.png" height="24"/>](https://brands.home-assistant.io/_/hacs/icon.png#gh-light-mode-only) [HACS](https://github.com/hacs/integration) | HACS gives you a powerful UI to handle downloads of all your custom needs.
[<img src="https://brands.home-assistant.io/_/hass-hue-icons-integration/icon.png" height="24"/>](https://brands.home-assistant.io/_/hass-hue-icons-integration/dark_icon.png#gh-dark-mode-only)[<img src="https://brands.home-assistant.io/_/hass-hue-icons-integration/icon.png" height="24"/>](https://brands.home-assistant.io/_/hass-hue-icons-integration/icon.png#gh-light-mode-only) [Hass Hue Icons Integration](https://github.com/arallsopp/hass-hue-icons-integration) | Additional vector icons for home assistant to model Philips Hue bulbs and fixtures. 
[<img src="https://brands.home-assistant.io/_/ical/icon.png" height="24"/>](https://brands.home-assistant.io/_/ical/dark_icon.png#gh-dark-mode-only)[<img src="https://brands.home-assistant.io/_/ical/icon.png" height="24"/>](https://brands.home-assistant.io/_/ical/icon.png#gh-light-mode-only) [Ical Sensor](https://github.com/tybritten/ical-sensor-homeassistant) | an iCal Sensor for Home Assistant
[<img src="https://brands.home-assistant.io/_/icloud3/icon.png" height="24"/>](https://brands.home-assistant.io/_/icloud3/dark_icon.png#gh-dark-mode-only)[<img src="https://brands.home-assistant.io/_/icloud3/icon.png" height="24"/>](https://brands.home-assistant.io/_/icloud3/icon.png#gh-light-mode-only) [Icloud3 V3 Idevice Tracker](https://github.com/gcobb321/icloud3) | iCloud3 v3, iDevice Tracker - An advanced iDevice tracker that uses Apple iCloud account and HA Mobile App data for presence detection and location based automations.
[<img src="https://brands.home-assistant.io/_/lastfm_scrobbler/icon.png" height="24"/>](https://brands.home-assistant.io/_/lastfm_scrobbler/dark_icon.png#gh-dark-mode-only)[<img src="https://brands.home-assistant.io/_/lastfm_scrobbler/icon.png" height="24"/>](https://brands.home-assistant.io/_/lastfm_scrobbler/icon.png#gh-light-mode-only) [Lastfm Scrobbler](https://github.com/valentin-gosselin/lastfm-scrobbler-ha-integration) | An Home Assistant integration scrobble to last.fm
[<img src="https://brands.home-assistant.io/_/life360/icon.png" height="24"/>](https://brands.home-assistant.io/_/life360/dark_icon.png#gh-dark-mode-only)[<img src="https://brands.home-assistant.io/_/life360/icon.png" height="24"/>](https://brands.home-assistant.io/_/life360/icon.png#gh-light-mode-only) [Life360](https://github.com/pnbruckner/ha-life360) | A Home Assistant integration for Life360.
[<img src="https://brands.home-assistant.io/_/mediarr/icon.png" height="24"/>](https://brands.home-assistant.io/_/mediarr/dark_icon.png#gh-dark-mode-only)[<img src="https://brands.home-assistant.io/_/mediarr/icon.png" height="24"/>](https://brands.home-assistant.io/_/mediarr/icon.png#gh-light-mode-only) [Mediarr](https://github.com/Vansmak/mediarr_sensor) | None
[<img src="https://brands.home-assistant.io/_/edge_tts/icon.png" height="24"/>](https://brands.home-assistant.io/_/edge_tts/dark_icon.png#gh-dark-mode-only)[<img src="https://brands.home-assistant.io/_/edge_tts/icon.png" height="24"/>](https://brands.home-assistant.io/_/edge_tts/icon.png#gh-light-mode-only) [Microsoft Edge Tts](https://github.com/hasscc/hass-edge-tts) | 🗣️ Microsoft Edge TTS for Home Assistant, no need for app_key
[<img src="https://brands.home-assistant.io/_/scheduler/icon.png" height="24"/>](https://brands.home-assistant.io/_/scheduler/dark_icon.png#gh-dark-mode-only)[<img src="https://brands.home-assistant.io/_/scheduler/icon.png" height="24"/>](https://brands.home-assistant.io/_/scheduler/icon.png#gh-light-mode-only) [Scheduler Component](https://github.com/nielsfaber/scheduler-component) | Custom component for HA that enables the creation of scheduler entities
[<img src="https://brands.home-assistant.io/_/simpleicons/icon.png" height="24"/>](https://brands.home-assistant.io/_/simpleicons/dark_icon.png#gh-dark-mode-only)[<img src="https://brands.home-assistant.io/_/simpleicons/icon.png" height="24"/>](https://brands.home-assistant.io/_/simpleicons/icon.png#gh-light-mode-only) [Simpleicons](https://github.com/vigonotion/hass-simpleicons) | Use Simple Icons in Home Assistant
[<img src="https://brands.home-assistant.io/_/spook/icon.png" height="24"/>](https://brands.home-assistant.io/_/spook/dark_icon.png#gh-dark-mode-only)[<img src="https://brands.home-assistant.io/_/spook/icon.png" height="24"/>](https://brands.home-assistant.io/_/spook/icon.png#gh-light-mode-only) [Spook 👻 Your Homie](https://github.com/frenck/spook) | A scary 👻 powerful toolbox 🧰 for Home Assistant 🏡
[<img src="https://brands.home-assistant.io/_/steam_wishlist/icon.png" height="24"/>](https://brands.home-assistant.io/_/steam_wishlist/dark_icon.png#gh-dark-mode-only)[<img src="https://brands.home-assistant.io/_/steam_wishlist/icon.png" height="24"/>](https://brands.home-assistant.io/_/steam_wishlist/icon.png#gh-light-mode-only) [Steam Wishlist](https://github.com/boralyl/steam-wishlist) | A home assistant integration that monitors games on sale on your Steam wishlist.
[<img src="https://brands.home-assistant.io/_/thermal_comfort/icon.png" height="24"/>](https://brands.home-assistant.io/_/thermal_comfort/dark_icon.png#gh-dark-mode-only)[<img src="https://brands.home-assistant.io/_/thermal_comfort/icon.png" height="24"/>](https://brands.home-assistant.io/_/thermal_comfort/icon.png#gh-light-mode-only) [Thermal Comfort](https://github.com/dolezsa/thermal_comfort) | Thermal Comfort sensor for HA (absolute humidity, heat index, dew point, thermal perception)
[<img src="https://brands.home-assistant.io/_/truenas/icon.png" height="24"/>](https://brands.home-assistant.io/_/truenas/dark_icon.png#gh-dark-mode-only)[<img src="https://brands.home-assistant.io/_/truenas/icon.png" height="24"/>](https://brands.home-assistant.io/_/truenas/icon.png#gh-light-mode-only) [Truenas](https://github.com/tomaae/homeassistant-truenas) | TrueNAS integration for Home Assistant 
[<img src="https://brands.home-assistant.io/_/unifi_site_manager/icon.png" height="24"/>](https://brands.home-assistant.io/_/unifi_site_manager/dark_icon.png#gh-dark-mode-only)[<img src="https://brands.home-assistant.io/_/unifi_site_manager/icon.png" height="24"/>](https://brands.home-assistant.io/_/unifi_site_manager/icon.png#gh-light-mode-only) [Unifi Site Manager](https://github.com/domalab/ha-unifi-site-manager) | This integration allows you to monitor all UniFi sites from Home Assistant
[<img src="https://brands.home-assistant.io/_/korea_bus/icon.png" height="24"/>](https://brands.home-assistant.io/_/korea_bus/dark_icon.png#gh-dark-mode-only)[<img src="https://brands.home-assistant.io/_/korea_bus/icon.png" height="24"/>](https://brands.home-assistant.io/_/korea_bus/icon.png#gh-light-mode-only) [버스(대중교통) 도착 정보](https://github.com/luiseok/ha-korea-bus-arrival) | Home Assistant custom component for South Korean bus arrival information
[<img src="https://brands.home-assistant.io/_/weathernews/icon.png" height="24"/>](https://brands.home-assistant.io/_/weathernews/dark_icon.png#gh-dark-mode-only)[<img src="https://brands.home-assistant.io/_/weathernews/icon.png" height="24"/>](https://brands.home-assistant.io/_/weathernews/icon.png#gh-light-mode-only) [웨더뉴스 Weathernews](https://github.com/dugurs/ha-weathernews) | Home Assistant custom component/integration for Weathernews.com

</details>

# Home Assistant Add-Ons

I use Home Assistant as my main home server, so there are lots of add-ons. I could run Home Assistant as a VM on a dedicated VM server, but I prefer to keep things simple.

[Enterprise smart home syndrome](https://frenck.dev/the-enterprise-smart-home-syndrome/)

<details>

Name | Version | Description
-- | -- | --
Advanced SSH & Web Terminal | 20.0.0 | 
DOODS2 | 1 | 
ESPHome Device Builder | 2024.12.4 | 
File editor | 5.8.0 | 
Firefly III | dev | 
Grocy | 0.23.0 | 
HomeNetwork for Hillstate | 1.1.6 | 
iSponsorBlockTV add-on | 2.1.2 | 
Let's Encrypt | 5.2.12 | 
Mailserver | 3.0.1 | 
MariaDB | 2.7.2 | 
Matter Server | 7.0.0 | 
Mosquitto broker | 6.5.0 | 
MQTT Explorer | browser-1.0.1 | 
Music Assistant Server | 2.3.6 | 
NGINX Home Assistant SSL proxy | 3.11.1 | 
OpenThread Border Router | 2.13.0 | 
phpMyAdmin | 0.11.0 | 
Samba share | 12.4.0 | 
Studio Code Server | 5.18.1 | 
Victoria Metrics | 1.110.0 | 
Whisper | 2.4.0 | 
ytdlp2STRM | 1.0.0 | 

</details>

# Lovelace Dashboard
## Lovelace plugins

<details>

Name | Description
-- | --
[Apexcharts Card](https://github.com/RomRider/apexcharts-card) | 📈 A Lovelace card to display advanced graphs and charts based on ApexChartsJS for Home Assistant
[Atomic Calendar Revive](https://github.com/totaldebug/atomic-calendar-revive) | An advanced calendar card for Home Assistant Lovelace.
[Auto Entities](https://github.com/thomasloven/lovelace-auto-entities) | 🔹Automatically populate the entities-list of lovelace cards
[Bar Card](https://github.com/custom-cards/bar-card) | Customizable Animated Bar card for Home Assistant Lovelace
[Battery State Card / Entity Row](https://github.com/maxwroc/battery-state-card) | Battery state card for Home Assistant
[Bha Icon Pack](https://github.com/hulkhaugen/hass-bha-icons) | Additional icons for Home Assistant to accompany the MDI icons
[Bubble Card](https://github.com/Clooos/Bubble-Card) | Bubble Card is a minimalist card collection for Home Assistant with a nice pop-up touch.
[Button Card](https://github.com/custom-cards/button-card) | ❇️ Lovelace button-card for home assistant
[Card Mod](https://github.com/thomasloven/lovelace-card-mod) | 🔹 Add CSS styles to (almost) any lovelace card
[Custom Brand Icons](https://github.com/elax46/custom-brand-icons) | Custom brand icons for Home Assistant
[Custom Icons](https://github.com/Mariusthvdb/custom-icons) | Several custom made and legacy icons, and icons collected all over the internet in 1 set, UI selectable.
[Custom Icons Pack](https://github.com/MattFryer/Hass-Custom-Icons) | Additional icons for use in Home Assistant UI
[Energy Entity Row](https://github.com/zeronounours/lovelace-energy-entity-row) | Lovelace HA entity row to integrate with energy-date-selection
[Energy Flow Card Plus](https://github.com/flixlix/energy-flow-card-plus) | An upgraded Energy Distribution Card for Home Assistant, with added features like Individual Devices and refined UI enhancements, while maintaining the Energy Dashboard's original design.
[Expander Card](https://github.com/MelleD/lovelace-expander-card) | Expander card for HomeAssistant
[Grocy Tasks And Chores Card](https://github.com/FamousWolf/grocy-tasks-chores) | Custom Home Assistant card for displaying tasks and chores from Grocy. This card requires the custom Grocy integration to be installed in Home Assistant.
[Ha Map Card Korea Radar](https://github.com/hwajin-me/ha-map-card-korea-radar) | Integrates a Korea rain radar overlay in the Home Assistant custom map card
[Hass Hue Icons](https://github.com/arallsopp/hass-hue-icons) | Additional vector icons for home assistant to model Philips  Hue bulbs and fixtures. 
[Hui Element](https://github.com/thomasloven/lovelace-hui-element) | 🔹 Use built-in elements in the wrong place
[Kiosk Mode](https://github.com/NemesisRE/kiosk-mode) | 🙈 Hides the Home Assistant header and/or sidebar
[Layout Card](https://github.com/thomasloven/lovelace-layout-card) | 🔹 Get more control over the placement of lovelace cards.
[List Card](https://github.com/iantrich/list-card) | 📰 Display sensor list data in a table
[Logbook Card](https://github.com/royto/logbook-card) | Logbook card for Home Assistant UI Lovelace
[Lovelace Grocy Chores Card](https://github.com/isabellaalstrom/lovelace-grocy-chores-card) | A card to track chores and tasks in Grocy.
[Lovelace Home Feed Card](https://github.com/gadgetchnnel/lovelace-home-feed-card) | A custom Lovelace card for displaying a combination of persistent notifications, calendar events, and entities in the style of a feed.
[Map Card](https://github.com/nathan-gs/ha-map-card) | A Map Card for Home Assistant
[Meal Plan Card   Lovelace Style](https://github.com/firstof9/lovelace-grocy-meal-plan-card) | Meal Plan Card for Home Assistant Grocy integration
[Mediarr Card](https://github.com/Vansmak/mediarr_card) | custom sonarr component for home assistant
[Mini Graph Card](https://github.com/kalkih/mini-graph-card) | Minimalistic graph card for Home Assistant Lovelace UI
[Mini Media Player](https://github.com/kalkih/mini-media-player) | Minimalistic media card for Home Assistant Lovelace UI
[More Info Card](https://github.com/thomasloven/lovelace-more-info-card) | 🔹 Display the more-info dialog of any entity as a lovelace card
[Multiple Entity Row](https://github.com/benct/lovelace-multiple-entity-row) | Show multiple entity states and attributes on entity rows in Home Assistant's Lovelace UI
[Mushroom](https://github.com/piitaya/lovelace-mushroom) | Build a beautiful Home Assistant dashboard easily
[Nintendo Wishlist Card](https://github.com/custom-cards/nintendo-wishlist-card) | Displays a card showing Nintendo Switch games that are on sale from your wish list.
[Notify Card](https://github.com/bernikr/lovelace-notify-card) | Send notifications directly from the dashboard
[Scheduler Card](https://github.com/nielsfaber/scheduler-card) | HA Lovelace card for control of scheduler entities
[Stack In Card](https://github.com/custom-cards/stack-in-card) | 🛠 group multiple cards into one card without the borders
[Steam Card](https://github.com/mkanet/kb-steam-card-plus) | An enhanced version of the Steam card with builtin support for current custom Roblox integration
[Tabbed Card](https://github.com/kinghat/tabbed-card) | a custom card for home assistant that utilizes tabs to segregate individual cards.
[Template Entity Row](https://github.com/thomasloven/lovelace-template-entity-row) | 🔹 Display whatever you want in an entities card row.
[Thermal Comfort Icons](https://github.com/rautesamtr/thermal_comfort_icons) | Thermal Comfort custom icons for Home Assistant to accompany the MDI icons

</details>

## Themes

<details>

Name | Description
-- | --
[Visionos Theme](https://github.com/Nezz/homeassistant-visionos-theme) | Theme inspired by visionOS for Home Assistant

</details>

***

Generated by the [custom readme integration](https://github.com/custom-components/readme)

Huge Thanks to [Joris Roovers](https://github.com/jorisroovers), this work is heavily influenced by his [work](https://github.com/jorisroovers/casa)

<!-- Footnotes -->
[^1]: UI Configuration

[commits-shield]: https://img.shields.io/github/commit-activity/y/saya6k/hass-config.svg
[commits]: https://github.com/saya6k/hass-config/commits/master
[contributors]: https://github.com/saya6k/hass-config/graphs/contributors
[saya6k]: https://github.com/saya6k
[home-assistant]: https://home-assistant.io
[issue]: https://github.com/saya6k/hass-config/issues
[license-shield]: https://img.shields.io/github/license/saya6k/hass-config.svg
[maintenance-shield]: https://img.shields.io/maintenance/yes/2025.svg
[last-commit-shield]: https://img.shields.io/github/last-commit/saya6k/hass-config.svg
[stars-shield]: https://img.shields.io/github/stars/saya6k/hass-config.svg?style=social&label=Stars
[forks-shield]: https://img.shields.io/github/forks/saya6k/hass-config.svg?style=social&label=Forks
[watchers-shield]: https://img.shields.io/github/watchers/saya6k/hass-config.svg?style=social&label=Watchers