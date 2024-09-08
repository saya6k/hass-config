# Home Assistant Config

![Project Maintenance][maintenance-shield]
[![License][license-shield]](LICENSE)

[![GitHub Activity][commits-shield]][commits]
[![GitHub Last Commit][last-commit-shield]][commits]

![GitHub Stars][stars-shield]
![GitHub Watchers][watchers-shield]
![GitHub Forks][forks-shield]

[!["Buy Me A Coffee"](https://www.buymeacoffee.com/assets/img/custom_images/orange_img.png)](https://www.buymeacoffee.com/my7nmfcm92k)

This is my Home Assistant documentation, updated on 2024-09-08.

I used Home Assistant in 2018 and then migrated to Apple Home.

I started using Home Assistant again in 2022. Now, it has grown significantly, with a total of 1888 entities for now.

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
      <img alt="Pegboard" src="docs/images/pegboard.png"><br>
      Pegboard
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
      <img alt="Zigbee Network Visualization" src="docs/images/zigbee-network.png"><br>
      Zigbee Network Visualization
    </td>
    <td>
      <img alt="Energy Dashboard" src="docs/images/lovelace-energy.png"><br>
      Energy Dashboard
    </td>
    <td>
      <img alt="Monitoring Dashboard" src="docs/images/lovelace-monitoring.png"><br>
      Monitoring Dashboard
    </td>
  </tr>
</table>

# Insights

Domain | Value
-- | --
automations | 43
binary_sensors | 89
device_trackers | 42
lights | 27
media_players | 18
sensors | 1066
switches | 120
switches | 120
others | 483
**Total** | **1888**


Component | Version
-- | --
Home Assistant Core | 2024.9.1
Supervisor | 2024.09.0
Operating System | 13.1

# Software Integrations

## Core Integrations

Integration | Configuration
--|--
[<img src="https://brands.home-assistant.io/_/seventeentrack/icon.png" height="24"/>](https://brands.home-assistant.io/_/seventeentrack/dark_icon.png#gh-dark-mode-only)[<img src="https://brands.home-assistant.io/_/seventeentrack/icon.png" height="24"/>](https://brands.home-assistant.io/_/seventeentrack/icon.png#gh-light-mode-only) [17TRACK](https://home-assistant.io/integrations/seventeentrack) | Config flow[^1]
[<img src="https://brands.home-assistant.io/_/adguard/icon.png" height="24"/>](https://brands.home-assistant.io/_/adguard/dark_icon.png#gh-dark-mode-only)[<img src="https://brands.home-assistant.io/_/adguard/icon.png" height="24"/>](https://brands.home-assistant.io/_/adguard/icon.png#gh-light-mode-only) [AdGuard Home](https://home-assistant.io/integrations/adguard) | Config flow[^1]
[<img src="https://brands.home-assistant.io/_/alert/icon.png" height="24"/>](https://brands.home-assistant.io/_/alert/dark_icon.png#gh-dark-mode-only)[<img src="https://brands.home-assistant.io/_/alert/icon.png" height="24"/>](https://brands.home-assistant.io/_/alert/icon.png#gh-light-mode-only) [alert](https://home-assistant.io/integrations/alert) | [./packages/alerts_and_notifications.yaml](./packages/alerts_and_notifications.yaml)
[<img src="https://brands.home-assistant.io/_/apple_tv/icon.png" height="24"/>](https://brands.home-assistant.io/_/apple_tv/dark_icon.png#gh-dark-mode-only)[<img src="https://brands.home-assistant.io/_/apple_tv/icon.png" height="24"/>](https://brands.home-assistant.io/_/apple_tv/icon.png#gh-light-mode-only) [Apple TV](https://home-assistant.io/integrations/apple_tv) | Config flow[^1]
[<img src="https://brands.home-assistant.io/_/automation/icon.png" height="24"/>](https://brands.home-assistant.io/_/automation/dark_icon.png#gh-dark-mode-only)[<img src="https://brands.home-assistant.io/_/automation/icon.png" height="24"/>](https://brands.home-assistant.io/_/automation/icon.png#gh-light-mode-only) [Automation](https://home-assistant.io/integrations/automation) | [./automations.yaml](./automations.yaml)
[<img src="https://brands.home-assistant.io/_/brother/icon.png" height="24"/>](https://brands.home-assistant.io/_/brother/dark_icon.png#gh-dark-mode-only)[<img src="https://brands.home-assistant.io/_/brother/icon.png" height="24"/>](https://brands.home-assistant.io/_/brother/icon.png#gh-light-mode-only) [Brother Printer](https://home-assistant.io/integrations/brother) | Config flow[^1]
[<img src="https://brands.home-assistant.io/_/calendar/icon.png" height="24"/>](https://brands.home-assistant.io/_/calendar/dark_icon.png#gh-dark-mode-only)[<img src="https://brands.home-assistant.io/_/calendar/icon.png" height="24"/>](https://brands.home-assistant.io/_/calendar/icon.png#gh-light-mode-only) [Calendar](https://home-assistant.io/integrations/calendar) | [./configuration.yaml](./configuration.yaml)
[<img src="https://brands.home-assistant.io/_/command_line/icon.png" height="24"/>](https://brands.home-assistant.io/_/command_line/dark_icon.png#gh-dark-mode-only)[<img src="https://brands.home-assistant.io/_/command_line/icon.png" height="24"/>](https://brands.home-assistant.io/_/command_line/icon.png#gh-light-mode-only) [Command Line](https://home-assistant.io/integrations/command_line) | Config flow[^1]
[<img src="https://brands.home-assistant.io/_/cpuspeed/icon.png" height="24"/>](https://brands.home-assistant.io/_/cpuspeed/dark_icon.png#gh-dark-mode-only)[<img src="https://brands.home-assistant.io/_/cpuspeed/icon.png" height="24"/>](https://brands.home-assistant.io/_/cpuspeed/icon.png#gh-light-mode-only) [CPU Speed](https://home-assistant.io/integrations/cpuspeed) | Config flow[^1]
[<img src="https://brands.home-assistant.io/_/default_config/icon.png" height="24"/>](https://brands.home-assistant.io/_/default_config/dark_icon.png#gh-dark-mode-only)[<img src="https://brands.home-assistant.io/_/default_config/icon.png" height="24"/>](https://brands.home-assistant.io/_/default_config/icon.png#gh-light-mode-only) [Default Config](https://home-assistant.io/integrations/default_config) | [./configuration.yaml](./configuration.yaml)
[<img src="https://brands.home-assistant.io/_/discord/icon.png" height="24"/>](https://brands.home-assistant.io/_/discord/dark_icon.png#gh-dark-mode-only)[<img src="https://brands.home-assistant.io/_/discord/icon.png" height="24"/>](https://brands.home-assistant.io/_/discord/icon.png#gh-light-mode-only) [Discord](https://home-assistant.io/integrations/discord) | Config flow[^1]
[<img src="https://brands.home-assistant.io/_/co2signal/icon.png" height="24"/>](https://brands.home-assistant.io/_/co2signal/dark_icon.png#gh-dark-mode-only)[<img src="https://brands.home-assistant.io/_/co2signal/icon.png" height="24"/>](https://brands.home-assistant.io/_/co2signal/icon.png#gh-light-mode-only) [Electricity Maps](https://home-assistant.io/integrations/co2signal) | Config flow[^1]
[<img src="https://brands.home-assistant.io/_/esphome/icon.png" height="24"/>](https://brands.home-assistant.io/_/esphome/dark_icon.png#gh-dark-mode-only)[<img src="https://brands.home-assistant.io/_/esphome/icon.png" height="24"/>](https://brands.home-assistant.io/_/esphome/icon.png#gh-light-mode-only) [ESPHome](https://home-assistant.io/integrations/esphome) | Config flow[^1]
[<img src="https://brands.home-assistant.io/_/feedreader/icon.png" height="24"/>](https://brands.home-assistant.io/_/feedreader/dark_icon.png#gh-dark-mode-only)[<img src="https://brands.home-assistant.io/_/feedreader/icon.png" height="24"/>](https://brands.home-assistant.io/_/feedreader/icon.png#gh-light-mode-only) [Feedreader](https://home-assistant.io/integrations/feedreader) | Config flow[^1]
[<img src="https://brands.home-assistant.io/_/frontend/icon.png" height="24"/>](https://brands.home-assistant.io/_/frontend/dark_icon.png#gh-dark-mode-only)[<img src="https://brands.home-assistant.io/_/frontend/icon.png" height="24"/>](https://brands.home-assistant.io/_/frontend/icon.png#gh-light-mode-only) [Frontend](https://home-assistant.io/integrations/frontend) | [./configuration.yaml](./configuration.yaml)
[<img src="https://brands.home-assistant.io/_/fully_kiosk/icon.png" height="24"/>](https://brands.home-assistant.io/_/fully_kiosk/dark_icon.png#gh-dark-mode-only)[<img src="https://brands.home-assistant.io/_/fully_kiosk/icon.png" height="24"/>](https://brands.home-assistant.io/_/fully_kiosk/icon.png#gh-light-mode-only) [Fully Kiosk Browser](https://home-assistant.io/integrations/fully_kiosk) | Config flow[^1]
[<img src="https://brands.home-assistant.io/_/github/icon.png" height="24"/>](https://brands.home-assistant.io/_/github/dark_icon.png#gh-dark-mode-only)[<img src="https://brands.home-assistant.io/_/github/icon.png" height="24"/>](https://brands.home-assistant.io/_/github/icon.png#gh-light-mode-only) [GitHub](https://home-assistant.io/integrations/github) | Config flow[^1]
[<img src="https://brands.home-assistant.io/_/google/icon.png" height="24"/>](https://brands.home-assistant.io/_/google/dark_icon.png#gh-dark-mode-only)[<img src="https://brands.home-assistant.io/_/google/icon.png" height="24"/>](https://brands.home-assistant.io/_/google/icon.png#gh-light-mode-only) [Google Calendar](https://home-assistant.io/integrations/google) | Config flow[^1]
[<img src="https://brands.home-assistant.io/_/google_generative_ai_conversation/icon.png" height="24"/>](https://brands.home-assistant.io/_/google_generative_ai_conversation/dark_icon.png#gh-dark-mode-only)[<img src="https://brands.home-assistant.io/_/google_generative_ai_conversation/icon.png" height="24"/>](https://brands.home-assistant.io/_/google_generative_ai_conversation/icon.png#gh-light-mode-only) [Google Generative AI Conversation](https://home-assistant.io/integrations/google_generative_ai_conversation) | Config flow[^1]
[<img src="https://brands.home-assistant.io/_/nest/icon.png" height="24"/>](https://brands.home-assistant.io/_/nest/dark_icon.png#gh-dark-mode-only)[<img src="https://brands.home-assistant.io/_/nest/icon.png" height="24"/>](https://brands.home-assistant.io/_/nest/icon.png#gh-light-mode-only) [Google Nest](https://home-assistant.io/integrations/nest) | Config flow[^1]
[<img src="https://brands.home-assistant.io/_/google_translate/icon.png" height="24"/>](https://brands.home-assistant.io/_/google_translate/dark_icon.png#gh-dark-mode-only)[<img src="https://brands.home-assistant.io/_/google_translate/icon.png" height="24"/>](https://brands.home-assistant.io/_/google_translate/icon.png#gh-light-mode-only) [Google Translate text-to-speech](https://home-assistant.io/integrations/google_translate) | Config flow[^1]
[<img src="https://brands.home-assistant.io/_/history/icon.png" height="24"/>](https://brands.home-assistant.io/_/history/dark_icon.png#gh-dark-mode-only)[<img src="https://brands.home-assistant.io/_/history/icon.png" height="24"/>](https://brands.home-assistant.io/_/history/icon.png#gh-light-mode-only) [History](https://home-assistant.io/integrations/history) | Config flow[^1]
[<img src="https://brands.home-assistant.io/_/cloud/icon.png" height="24"/>](https://brands.home-assistant.io/_/cloud/dark_icon.png#gh-dark-mode-only)[<img src="https://brands.home-assistant.io/_/cloud/icon.png" height="24"/>](https://brands.home-assistant.io/_/cloud/icon.png#gh-light-mode-only) [Home Assistant Cloud](https://home-assistant.io/integrations/cloud) | Config flow[^1]
[<img src="https://brands.home-assistant.io/_/homeassistant/icon.png" height="24"/>](https://brands.home-assistant.io/_/homeassistant/dark_icon.png#gh-dark-mode-only)[<img src="https://brands.home-assistant.io/_/homeassistant/icon.png" height="24"/>](https://brands.home-assistant.io/_/homeassistant/icon.png#gh-light-mode-only) [Home Assistant Core Integration](https://home-assistant.io/integrations/homeassistant) | [./configuration.yaml](./configuration.yaml)
[<img src="https://brands.home-assistant.io/_/homekit/icon.png" height="24"/>](https://brands.home-assistant.io/_/homekit/dark_icon.png#gh-dark-mode-only)[<img src="https://brands.home-assistant.io/_/homekit/icon.png" height="24"/>](https://brands.home-assistant.io/_/homekit/icon.png#gh-light-mode-only) [HomeKit Bridge](https://home-assistant.io/integrations/homekit) | Config flow[^1]
[<img src="https://brands.home-assistant.io/_/homekit_controller/icon.png" height="24"/>](https://brands.home-assistant.io/_/homekit_controller/dark_icon.png#gh-dark-mode-only)[<img src="https://brands.home-assistant.io/_/homekit_controller/icon.png" height="24"/>](https://brands.home-assistant.io/_/homekit_controller/icon.png#gh-light-mode-only) [HomeKit Device](https://home-assistant.io/integrations/homekit_controller) | Config flow[^1]
[<img src="https://brands.home-assistant.io/_/http/icon.png" height="24"/>](https://brands.home-assistant.io/_/http/dark_icon.png#gh-dark-mode-only)[<img src="https://brands.home-assistant.io/_/http/icon.png" height="24"/>](https://brands.home-assistant.io/_/http/icon.png#gh-light-mode-only) [HTTP](https://home-assistant.io/integrations/http) | [./configuration.yaml](./configuration.yaml)
[<img src="https://brands.home-assistant.io/_/imap/icon.png" height="24"/>](https://brands.home-assistant.io/_/imap/dark_icon.png#gh-dark-mode-only)[<img src="https://brands.home-assistant.io/_/imap/icon.png" height="24"/>](https://brands.home-assistant.io/_/imap/icon.png#gh-light-mode-only) [IMAP](https://home-assistant.io/integrations/imap) | Config flow[^1]
[<img src="https://brands.home-assistant.io/_/ipp/icon.png" height="24"/>](https://brands.home-assistant.io/_/ipp/dark_icon.png#gh-dark-mode-only)[<img src="https://brands.home-assistant.io/_/ipp/icon.png" height="24"/>](https://brands.home-assistant.io/_/ipp/icon.png#gh-light-mode-only) [Internet Printing Protocol (IPP)](https://home-assistant.io/integrations/ipp) | Config flow[^1]
[<img src="https://brands.home-assistant.io/_/lastfm/icon.png" height="24"/>](https://brands.home-assistant.io/_/lastfm/dark_icon.png#gh-dark-mode-only)[<img src="https://brands.home-assistant.io/_/lastfm/icon.png" height="24"/>](https://brands.home-assistant.io/_/lastfm/icon.png#gh-light-mode-only) [Last.fm](https://home-assistant.io/integrations/lastfm) | Config flow[^1]
[<img src="https://brands.home-assistant.io/_/local_calendar/icon.png" height="24"/>](https://brands.home-assistant.io/_/local_calendar/dark_icon.png#gh-dark-mode-only)[<img src="https://brands.home-assistant.io/_/local_calendar/icon.png" height="24"/>](https://brands.home-assistant.io/_/local_calendar/icon.png#gh-light-mode-only) [Local Calendar](https://home-assistant.io/integrations/local_calendar) | Config flow[^1]
[<img src="https://brands.home-assistant.io/_/local_todo/icon.png" height="24"/>](https://brands.home-assistant.io/_/local_todo/dark_icon.png#gh-dark-mode-only)[<img src="https://brands.home-assistant.io/_/local_todo/icon.png" height="24"/>](https://brands.home-assistant.io/_/local_todo/icon.png#gh-light-mode-only) [Local To Do](https://home-assistant.io/integrations/local_todo) | Config flow[^1]
[<img src="https://brands.home-assistant.io/_/logger/icon.png" height="24"/>](https://brands.home-assistant.io/_/logger/dark_icon.png#gh-dark-mode-only)[<img src="https://brands.home-assistant.io/_/logger/icon.png" height="24"/>](https://brands.home-assistant.io/_/logger/icon.png#gh-light-mode-only) [Logger](https://home-assistant.io/integrations/logger) | [./configuration.yaml](./configuration.yaml)
[<img src="https://brands.home-assistant.io/_/lovelace/icon.png" height="24"/>](https://brands.home-assistant.io/_/lovelace/dark_icon.png#gh-dark-mode-only)[<img src="https://brands.home-assistant.io/_/lovelace/icon.png" height="24"/>](https://brands.home-assistant.io/_/lovelace/icon.png#gh-light-mode-only) [Lovelace](https://home-assistant.io/integrations/lovelace) | [./configuration.yaml](./configuration.yaml)
[<img src="https://brands.home-assistant.io/_/matter/icon.png" height="24"/>](https://brands.home-assistant.io/_/matter/dark_icon.png#gh-dark-mode-only)[<img src="https://brands.home-assistant.io/_/matter/icon.png" height="24"/>](https://brands.home-assistant.io/_/matter/icon.png#gh-light-mode-only) [Matter (BETA)](https://home-assistant.io/integrations/matter) | Config flow[^1]
[<img src="https://brands.home-assistant.io/_/mealie/icon.png" height="24"/>](https://brands.home-assistant.io/_/mealie/dark_icon.png#gh-dark-mode-only)[<img src="https://brands.home-assistant.io/_/mealie/icon.png" height="24"/>](https://brands.home-assistant.io/_/mealie/icon.png#gh-light-mode-only) [Mealie](https://home-assistant.io/integrations/mealie) | Config flow[^1]
[<img src="https://brands.home-assistant.io/_/mobile_app/icon.png" height="24"/>](https://brands.home-assistant.io/_/mobile_app/dark_icon.png#gh-dark-mode-only)[<img src="https://brands.home-assistant.io/_/mobile_app/icon.png" height="24"/>](https://brands.home-assistant.io/_/mobile_app/icon.png#gh-light-mode-only) [Mobile App](https://home-assistant.io/integrations/mobile_app) | Config flow[^1]
[<img src="https://brands.home-assistant.io/_/moon/icon.png" height="24"/>](https://brands.home-assistant.io/_/moon/dark_icon.png#gh-dark-mode-only)[<img src="https://brands.home-assistant.io/_/moon/icon.png" height="24"/>](https://brands.home-assistant.io/_/moon/icon.png#gh-light-mode-only) [Moon](https://home-assistant.io/integrations/moon) | Config flow[^1]
[<img src="https://brands.home-assistant.io/_/mqtt/icon.png" height="24"/>](https://brands.home-assistant.io/_/mqtt/dark_icon.png#gh-dark-mode-only)[<img src="https://brands.home-assistant.io/_/mqtt/icon.png" height="24"/>](https://brands.home-assistant.io/_/mqtt/icon.png#gh-light-mode-only) [MQTT](https://home-assistant.io/integrations/mqtt) | Config flow[^1]
[<img src="https://brands.home-assistant.io/_/my/icon.png" height="24"/>](https://brands.home-assistant.io/_/my/dark_icon.png#gh-dark-mode-only)[<img src="https://brands.home-assistant.io/_/my/icon.png" height="24"/>](https://brands.home-assistant.io/_/my/icon.png#gh-light-mode-only) [My Home Assistant](https://home-assistant.io/integrations/my) | [./configuration.yaml](./configuration.yaml)
[<img src="https://brands.home-assistant.io/_/notify/icon.png" height="24"/>](https://brands.home-assistant.io/_/notify/dark_icon.png#gh-dark-mode-only)[<img src="https://brands.home-assistant.io/_/notify/icon.png" height="24"/>](https://brands.home-assistant.io/_/notify/icon.png#gh-light-mode-only) [notify](https://home-assistant.io/integrations/notify) | [./packages/alerts_and_notifications.yaml](./packages/alerts_and_notifications.yaml)
[<img src="https://brands.home-assistant.io/_/ollama/icon.png" height="24"/>](https://brands.home-assistant.io/_/ollama/dark_icon.png#gh-dark-mode-only)[<img src="https://brands.home-assistant.io/_/ollama/icon.png" height="24"/>](https://brands.home-assistant.io/_/ollama/icon.png#gh-light-mode-only) [Ollama](https://home-assistant.io/integrations/ollama) | Config flow[^1]
[<img src="https://brands.home-assistant.io/_/otbr/icon.png" height="24"/>](https://brands.home-assistant.io/_/otbr/dark_icon.png#gh-dark-mode-only)[<img src="https://brands.home-assistant.io/_/otbr/icon.png" height="24"/>](https://brands.home-assistant.io/_/otbr/icon.png#gh-light-mode-only) [Open Thread Border Router](https://home-assistant.io/integrations/otbr) | Config flow[^1]
[<img src="https://brands.home-assistant.io/_/openai_conversation/icon.png" height="24"/>](https://brands.home-assistant.io/_/openai_conversation/dark_icon.png#gh-dark-mode-only)[<img src="https://brands.home-assistant.io/_/openai_conversation/icon.png" height="24"/>](https://brands.home-assistant.io/_/openai_conversation/icon.png#gh-light-mode-only) [OpenAI Conversation](https://home-assistant.io/integrations/openai_conversation) | Config flow[^1]
[<img src="https://brands.home-assistant.io/_/ping/icon.png" height="24"/>](https://brands.home-assistant.io/_/ping/dark_icon.png#gh-dark-mode-only)[<img src="https://brands.home-assistant.io/_/ping/icon.png" height="24"/>](https://brands.home-assistant.io/_/ping/icon.png#gh-light-mode-only) [Ping (ICMP)](https://home-assistant.io/integrations/ping) | Config flow[^1]
[<img src="https://brands.home-assistant.io/_/plex/icon.png" height="24"/>](https://brands.home-assistant.io/_/plex/dark_icon.png#gh-dark-mode-only)[<img src="https://brands.home-assistant.io/_/plex/icon.png" height="24"/>](https://brands.home-assistant.io/_/plex/icon.png#gh-light-mode-only) [Plex Media Server](https://home-assistant.io/integrations/plex) | Config flow[^1]
[<img src="https://brands.home-assistant.io/_/profiler/icon.png" height="24"/>](https://brands.home-assistant.io/_/profiler/dark_icon.png#gh-dark-mode-only)[<img src="https://brands.home-assistant.io/_/profiler/icon.png" height="24"/>](https://brands.home-assistant.io/_/profiler/icon.png#gh-light-mode-only) [Profiler](https://home-assistant.io/integrations/profiler) | Config flow[^1]
[<img src="https://brands.home-assistant.io/_/prometheus/icon.png" height="24"/>](https://brands.home-assistant.io/_/prometheus/dark_icon.png#gh-dark-mode-only)[<img src="https://brands.home-assistant.io/_/prometheus/icon.png" height="24"/>](https://brands.home-assistant.io/_/prometheus/icon.png#gh-light-mode-only) [Prometheus](https://home-assistant.io/integrations/prometheus) | [./configuration.yaml](./configuration.yaml)
[<img src="https://brands.home-assistant.io/_/recorder/icon.png" height="24"/>](https://brands.home-assistant.io/_/recorder/dark_icon.png#gh-dark-mode-only)[<img src="https://brands.home-assistant.io/_/recorder/icon.png" height="24"/>](https://brands.home-assistant.io/_/recorder/icon.png#gh-light-mode-only) [Recorder](https://home-assistant.io/integrations/recorder) | [./configuration.yaml](./configuration.yaml)
[<img src="https://brands.home-assistant.io/_/rest_command/icon.png" height="24"/>](https://brands.home-assistant.io/_/rest_command/dark_icon.png#gh-dark-mode-only)[<img src="https://brands.home-assistant.io/_/rest_command/icon.png" height="24"/>](https://brands.home-assistant.io/_/rest_command/icon.png#gh-light-mode-only) [RESTful Command](https://home-assistant.io/integrations/rest_command) | [./packages/rest_commands.yaml](./packages/rest_commands.yaml)
[<img src="https://brands.home-assistant.io/_/scene/icon.png" height="24"/>](https://brands.home-assistant.io/_/scene/dark_icon.png#gh-dark-mode-only)[<img src="https://brands.home-assistant.io/_/scene/icon.png" height="24"/>](https://brands.home-assistant.io/_/scene/icon.png#gh-light-mode-only) [Scene](https://home-assistant.io/integrations/scene) | [./scenes.yaml](./scenes.yaml)
[<img src="https://brands.home-assistant.io/_/script/icon.png" height="24"/>](https://brands.home-assistant.io/_/script/dark_icon.png#gh-dark-mode-only)[<img src="https://brands.home-assistant.io/_/script/icon.png" height="24"/>](https://brands.home-assistant.io/_/script/icon.png#gh-light-mode-only) [Script](https://home-assistant.io/integrations/script) | [./scripts.yaml](./scripts.yaml)
[<img src="https://brands.home-assistant.io/_/shell_command/icon.png" height="24"/>](https://brands.home-assistant.io/_/shell_command/dark_icon.png#gh-dark-mode-only)[<img src="https://brands.home-assistant.io/_/shell_command/icon.png" height="24"/>](https://brands.home-assistant.io/_/shell_command/icon.png#gh-light-mode-only) [Shell Command](https://home-assistant.io/integrations/shell_command) | [./configuration.yaml](./configuration.yaml)
[<img src="https://brands.home-assistant.io/_/stt/icon.png" height="24"/>](https://brands.home-assistant.io/_/stt/dark_icon.png#gh-dark-mode-only)[<img src="https://brands.home-assistant.io/_/stt/icon.png" height="24"/>](https://brands.home-assistant.io/_/stt/icon.png#gh-light-mode-only) [Speech-to-text (STT)](https://home-assistant.io/integrations/stt) | [./configuration.yaml](./configuration.yaml)
[<img src="https://brands.home-assistant.io/_/speedtestdotnet/icon.png" height="24"/>](https://brands.home-assistant.io/_/speedtestdotnet/dark_icon.png#gh-dark-mode-only)[<img src="https://brands.home-assistant.io/_/speedtestdotnet/icon.png" height="24"/>](https://brands.home-assistant.io/_/speedtestdotnet/icon.png#gh-light-mode-only) [Speedtest.net](https://home-assistant.io/integrations/speedtestdotnet) | Config flow[^1]
[<img src="https://brands.home-assistant.io/_/sql/icon.png" height="24"/>](https://brands.home-assistant.io/_/sql/dark_icon.png#gh-dark-mode-only)[<img src="https://brands.home-assistant.io/_/sql/icon.png" height="24"/>](https://brands.home-assistant.io/_/sql/icon.png#gh-light-mode-only) [SQL](https://home-assistant.io/integrations/sql) | Config flow[^1]
[<img src="https://brands.home-assistant.io/_/steam_online/icon.png" height="24"/>](https://brands.home-assistant.io/_/steam_online/dark_icon.png#gh-dark-mode-only)[<img src="https://brands.home-assistant.io/_/steam_online/icon.png" height="24"/>](https://brands.home-assistant.io/_/steam_online/icon.png#gh-light-mode-only) [Steam](https://home-assistant.io/integrations/steam_online) | Config flow[^1]
[<img src="https://brands.home-assistant.io/_/sun/icon.png" height="24"/>](https://brands.home-assistant.io/_/sun/dark_icon.png#gh-dark-mode-only)[<img src="https://brands.home-assistant.io/_/sun/icon.png" height="24"/>](https://brands.home-assistant.io/_/sun/icon.png#gh-light-mode-only) [Sun](https://home-assistant.io/integrations/sun) | Config flow[^1]
[<img src="https://brands.home-assistant.io/_/hassio/icon.png" height="24"/>](https://brands.home-assistant.io/_/hassio/dark_icon.png#gh-dark-mode-only)[<img src="https://brands.home-assistant.io/_/hassio/icon.png" height="24"/>](https://brands.home-assistant.io/_/hassio/icon.png#gh-light-mode-only) [Supervisor](https://home-assistant.io/integrations/hassio) | Config flow[^1]
[<img src="https://brands.home-assistant.io/_/systemmonitor/icon.png" height="24"/>](https://brands.home-assistant.io/_/systemmonitor/dark_icon.png#gh-dark-mode-only)[<img src="https://brands.home-assistant.io/_/systemmonitor/icon.png" height="24"/>](https://brands.home-assistant.io/_/systemmonitor/icon.png#gh-light-mode-only) [System Monitor](https://home-assistant.io/integrations/systemmonitor) | Config flow[^1]
[<img src="https://brands.home-assistant.io/_/template/icon.png" height="24"/>](https://brands.home-assistant.io/_/template/dark_icon.png#gh-dark-mode-only)[<img src="https://brands.home-assistant.io/_/template/icon.png" height="24"/>](https://brands.home-assistant.io/_/template/icon.png#gh-light-mode-only) [Template](https://home-assistant.io/integrations/template) | [./packages](./packages)
[<img src="https://brands.home-assistant.io/_/thread/icon.png" height="24"/>](https://brands.home-assistant.io/_/thread/dark_icon.png#gh-dark-mode-only)[<img src="https://brands.home-assistant.io/_/thread/icon.png" height="24"/>](https://brands.home-assistant.io/_/thread/icon.png#gh-light-mode-only) [Thread](https://home-assistant.io/integrations/thread) | Config flow[^1]
[<img src="https://brands.home-assistant.io/_/time_date/icon.png" height="24"/>](https://brands.home-assistant.io/_/time_date/dark_icon.png#gh-dark-mode-only)[<img src="https://brands.home-assistant.io/_/time_date/icon.png" height="24"/>](https://brands.home-assistant.io/_/time_date/icon.png#gh-light-mode-only) [Time & Date](https://home-assistant.io/integrations/time_date) | Config flow[^1]
[<img src="https://brands.home-assistant.io/_/unifi/icon.png" height="24"/>](https://brands.home-assistant.io/_/unifi/dark_icon.png#gh-dark-mode-only)[<img src="https://brands.home-assistant.io/_/unifi/icon.png" height="24"/>](https://brands.home-assistant.io/_/unifi/icon.png#gh-light-mode-only) [Unifi Network](https://home-assistant.io/integrations/unifi) | Config flow[^1]
[<img src="https://brands.home-assistant.io/_/uptime/icon.png" height="24"/>](https://brands.home-assistant.io/_/uptime/dark_icon.png#gh-dark-mode-only)[<img src="https://brands.home-assistant.io/_/uptime/icon.png" height="24"/>](https://brands.home-assistant.io/_/uptime/icon.png#gh-light-mode-only) [Uptime](https://home-assistant.io/integrations/uptime) | Config flow[^1]
[<img src="https://brands.home-assistant.io/_/version/icon.png" height="24"/>](https://brands.home-assistant.io/_/version/dark_icon.png#gh-dark-mode-only)[<img src="https://brands.home-assistant.io/_/version/icon.png" height="24"/>](https://brands.home-assistant.io/_/version/icon.png#gh-light-mode-only) [Version](https://home-assistant.io/integrations/version) | Config flow[^1]
[<img src="https://brands.home-assistant.io/_/withings/icon.png" height="24"/>](https://brands.home-assistant.io/_/withings/dark_icon.png#gh-dark-mode-only)[<img src="https://brands.home-assistant.io/_/withings/icon.png" height="24"/>](https://brands.home-assistant.io/_/withings/icon.png#gh-light-mode-only) [Withings](https://home-assistant.io/integrations/withings) | Config flow[^1]
[<img src="https://brands.home-assistant.io/_/workday/icon.png" height="24"/>](https://brands.home-assistant.io/_/workday/dark_icon.png#gh-dark-mode-only)[<img src="https://brands.home-assistant.io/_/workday/icon.png" height="24"/>](https://brands.home-assistant.io/_/workday/icon.png#gh-light-mode-only) [Workday](https://home-assistant.io/integrations/workday) | Config flow[^1]
[<img src="https://brands.home-assistant.io/_/wyoming/icon.png" height="24"/>](https://brands.home-assistant.io/_/wyoming/dark_icon.png#gh-dark-mode-only)[<img src="https://brands.home-assistant.io/_/wyoming/icon.png" height="24"/>](https://brands.home-assistant.io/_/wyoming/icon.png#gh-light-mode-only) [Wyoming](https://home-assistant.io/integrations/wyoming) | Config flow[^1]
[<img src="https://brands.home-assistant.io/_/zha/icon.png" height="24"/>](https://brands.home-assistant.io/_/zha/dark_icon.png#gh-dark-mode-only)[<img src="https://brands.home-assistant.io/_/zha/icon.png" height="24"/>](https://brands.home-assistant.io/_/zha/icon.png#gh-light-mode-only) [Zigbee Home Automation](https://home-assistant.io/integrations/zha) | Config flow[^1]
## Custom Components from HACS

Name | Description
-- | --
[<img src="https://brands.home-assistant.io/_/gas_station_korea/icon.png" height="24"/>](https://brands.home-assistant.io/_/gas_station_korea/dark_icon.png#gh-dark-mode-only)[<img src="https://brands.home-assistant.io/_/gas_station_korea/icon.png" height="24"/>](https://brands.home-assistant.io/_/gas_station_korea/icon.png#gh-light-mode-only) [[Kr] Gas Station Oil Price Sensor](https://github.com/GrecHouse/gas_station_korea) | Gas station oil price sensor #HA 주유소 유가 정보 센서
[<img src="https://brands.home-assistant.io/_/map_change/icon.png" height="24"/>](https://brands.home-assistant.io/_/map_change/dark_icon.png#gh-dark-mode-only)[<img src="https://brands.home-assistant.io/_/map_change/icon.png" height="24"/>](https://brands.home-assistant.io/_/map_change/icon.png#gh-light-mode-only) [[Kr] Map Change Service](https://github.com/miumida/map_change) | Default Map to NAVER Map. Map Change Service for Home Assistant #HA
[<img src="https://brands.home-assistant.io/_/seoul_bus/icon.png" height="24"/>](https://brands.home-assistant.io/_/seoul_bus/dark_icon.png#gh-dark-mode-only)[<img src="https://brands.home-assistant.io/_/seoul_bus/icon.png" height="24"/>](https://brands.home-assistant.io/_/seoul_bus/icon.png#gh-light-mode-only) [[Kr] Seoul Bus](https://github.com/miumida/seoul_bus) | Seoul Bus Sensor for Home Assistant #HA
[<img src="https://brands.home-assistant.io/_/naver_weather/icon.png" height="24"/>](https://brands.home-assistant.io/_/naver_weather/dark_icon.png#gh-dark-mode-only)[<img src="https://brands.home-assistant.io/_/naver_weather/icon.png" height="24"/>](https://brands.home-assistant.io/_/naver_weather/icon.png#gh-light-mode-only) [[KR] 네이버 날씨](https://github.com/miumida/naver_weather) | Naver Weather Sensor for Home Assistant #HA
[<img src="https://brands.home-assistant.io/_/dh_lottery/icon.png" height="24"/>](https://brands.home-assistant.io/_/dh_lottery/dark_icon.png#gh-dark-mode-only)[<img src="https://brands.home-assistant.io/_/dh_lottery/icon.png" height="24"/>](https://brands.home-assistant.io/_/dh_lottery/icon.png#gh-light-mode-only) [[KR] 동행 복권](https://github.com/stkang/ha-component-dh-lottery) | None
[<img src="https://brands.home-assistant.io/_/kwh_to_won/icon.png" height="24"/>](https://brands.home-assistant.io/_/kwh_to_won/dark_icon.png#gh-dark-mode-only)[<img src="https://brands.home-assistant.io/_/kwh_to_won/icon.png" height="24"/>](https://brands.home-assistant.io/_/kwh_to_won/icon.png#gh-light-mode-only) [[KR] 전기요금 계산 센서 (가정용)](https://github.com/dugurs/kwh_to_won) | 한국전력 전기요금 계산기 (가정용)
[<img src="https://brands.home-assistant.io/_/adaptive_lighting/icon.png" height="24"/>](https://brands.home-assistant.io/_/adaptive_lighting/dark_icon.png#gh-dark-mode-only)[<img src="https://brands.home-assistant.io/_/adaptive_lighting/icon.png" height="24"/>](https://brands.home-assistant.io/_/adaptive_lighting/icon.png#gh-light-mode-only) [Adaptive Lighting](https://github.com/basnijholt/adaptive-lighting) | Adaptive Lighting custom component for Home Assistant
[<img src="https://brands.home-assistant.io/_/alarmo/icon.png" height="24"/>](https://brands.home-assistant.io/_/alarmo/dark_icon.png#gh-dark-mode-only)[<img src="https://brands.home-assistant.io/_/alarmo/icon.png" height="24"/>](https://brands.home-assistant.io/_/alarmo/icon.png#gh-light-mode-only) [Alarmo](https://github.com/nielsfaber/alarmo) | Easy to use alarm system integration for Home Assistant
[<img src="https://brands.home-assistant.io/_/anniversaries/icon.png" height="24"/>](https://brands.home-assistant.io/_/anniversaries/dark_icon.png#gh-dark-mode-only)[<img src="https://brands.home-assistant.io/_/anniversaries/icon.png" height="24"/>](https://brands.home-assistant.io/_/anniversaries/icon.png#gh-light-mode-only) [Anniversaries](https://github.com/pinkywafer/Anniversaries) | Anniversary Countdown Sensor for Home Assistant
[<img src="https://brands.home-assistant.io/_/aten_pe/icon.png" height="24"/>](https://brands.home-assistant.io/_/aten_pe/dark_icon.png#gh-dark-mode-only)[<img src="https://brands.home-assistant.io/_/aten_pe/icon.png" height="24"/>](https://brands.home-assistant.io/_/aten_pe/icon.png#gh-light-mode-only) [Aten Rack Pdu](https://github.com/mtdcr/homeassistant-aten-pe) | Home Assistant integration for ATEN Rack PDUs
[<img src="https://brands.home-assistant.io/_/auto_backup/icon.png" height="24"/>](https://brands.home-assistant.io/_/auto_backup/dark_icon.png#gh-dark-mode-only)[<img src="https://brands.home-assistant.io/_/auto_backup/icon.png" height="24"/>](https://brands.home-assistant.io/_/auto_backup/icon.png#gh-light-mode-only) [Auto Backup](https://github.com/jcwillox/hass-auto-backup) | 🗃️ Improved Backup Service for Home Assistant that can Automatically Remove Backups and Supports Generational Backup Schemes.
[<img src="https://brands.home-assistant.io/_/citywaste_korea/icon.png" height="24"/>](https://brands.home-assistant.io/_/citywaste_korea/dark_icon.png#gh-dark-mode-only)[<img src="https://brands.home-assistant.io/_/citywaste_korea/icon.png" height="24"/>](https://brands.home-assistant.io/_/citywaste_korea/icon.png#gh-light-mode-only) [Citywaste Korea](https://github.com/staiji/citywaste_korea) | Home Assistant CityWaste Korea Component (음식물 쓰레기 배출량 조회)
[<img src="https://brands.home-assistant.io/_/config_editor/icon.png" height="24"/>](https://brands.home-assistant.io/_/config_editor/dark_icon.png#gh-dark-mode-only)[<img src="https://brands.home-assistant.io/_/config_editor/icon.png" height="24"/>](https://brands.home-assistant.io/_/config_editor/icon.png#gh-light-mode-only) [Config Editor](https://github.com/junkfix/config-editor) | Home Assistant Configuration Editor Helper
[<img src="https://brands.home-assistant.io/_/sihas/icon.png" height="24"/>](https://brands.home-assistant.io/_/sihas/dark_icon.png#gh-dark-mode-only)[<img src="https://brands.home-assistant.io/_/sihas/icon.png" height="24"/>](https://brands.home-assistant.io/_/sihas/icon.png#gh-light-mode-only) [Custom Component For Sihas Wi Fi Device](https://github.com/cmsong-shina/sihas-canary) | HA custom component for SiHAS Wi-Fi devices.
[<img src="https://brands.home-assistant.io/_/danawa_shopping/icon.png" height="24"/>](https://brands.home-assistant.io/_/danawa_shopping/dark_icon.png#gh-dark-mode-only)[<img src="https://brands.home-assistant.io/_/danawa_shopping/icon.png" height="24"/>](https://brands.home-assistant.io/_/danawa_shopping/icon.png#gh-light-mode-only) [Danawa Shopping](https://github.com/oukene/danawa_shopping) | 다나와 쇼핑검색
[<img src="https://brands.home-assistant.io/_/discord_game/icon.png" height="24"/>](https://brands.home-assistant.io/_/discord_game/dark_icon.png#gh-dark-mode-only)[<img src="https://brands.home-assistant.io/_/discord_game/icon.png" height="24"/>](https://brands.home-assistant.io/_/discord_game/icon.png#gh-light-mode-only) [Discord Game](https://github.com/LordBoos/discord_game) | Home Assistant custom component to get online and game status of Discord users
[<img src="https://brands.home-assistant.io/_/easyroll_blind/icon.png" height="24"/>](https://brands.home-assistant.io/_/easyroll_blind/dark_icon.png#gh-dark-mode-only)[<img src="https://brands.home-assistant.io/_/easyroll_blind/icon.png" height="24"/>](https://brands.home-assistant.io/_/easyroll_blind/icon.png#gh-light-mode-only) [Easyroll Blind](https://github.com/oukene/easyroll_blind) | HA 용 이지롤 블라인드 통합구성요소
[<img src="https://brands.home-assistant.io/_/elevenlabs_tts/icon.png" height="24"/>](https://brands.home-assistant.io/_/elevenlabs_tts/dark_icon.png#gh-dark-mode-only)[<img src="https://brands.home-assistant.io/_/elevenlabs_tts/icon.png" height="24"/>](https://brands.home-assistant.io/_/elevenlabs_tts/icon.png#gh-light-mode-only) [Elevenlabs Tts](https://github.com/carleeno/elevenlabs_tts) | Custom TTS Integration using ElevenLabs API
[<img src="https://brands.home-assistant.io/_/extended_openai_conversation/icon.png" height="24"/>](https://brands.home-assistant.io/_/extended_openai_conversation/dark_icon.png#gh-dark-mode-only)[<img src="https://brands.home-assistant.io/_/extended_openai_conversation/icon.png" height="24"/>](https://brands.home-assistant.io/_/extended_openai_conversation/icon.png#gh-light-mode-only) [Extended Openai Conversation](https://github.com/jekalmin/extended_openai_conversation) | Home Assistant custom component of conversation agent. It uses OpenAI to control your devices.
[<img src="https://brands.home-assistant.io/_/fallback_conversation/icon.png" height="24"/>](https://brands.home-assistant.io/_/fallback_conversation/dark_icon.png#gh-dark-mode-only)[<img src="https://brands.home-assistant.io/_/fallback_conversation/icon.png" height="24"/>](https://brands.home-assistant.io/_/fallback_conversation/icon.png#gh-light-mode-only) [Fallback Conversation](https://github.com/m50/ha-fallback-conversation) | HomeAssistant Assist Fallback Conversation Agent
[<img src="https://brands.home-assistant.io/_/fireflyiii_integration/icon.png" height="24"/>](https://brands.home-assistant.io/_/fireflyiii_integration/dark_icon.png#gh-dark-mode-only)[<img src="https://brands.home-assistant.io/_/fireflyiii_integration/icon.png" height="24"/>](https://brands.home-assistant.io/_/fireflyiii_integration/icon.png#gh-light-mode-only) [Fireflyiii Integration](https://github.com/soloam/ha-fireflyiii-integration) | FireflyIII Integration for Home Assistant
[<img src="https://brands.home-assistant.io/_/fontawesome/icon.png" height="24"/>](https://brands.home-assistant.io/_/fontawesome/dark_icon.png#gh-dark-mode-only)[<img src="https://brands.home-assistant.io/_/fontawesome/icon.png" height="24"/>](https://brands.home-assistant.io/_/fontawesome/icon.png#gh-light-mode-only) [Fontawesome](https://github.com/thomasloven/hass-fontawesome) | 🔹 Use icons from fontawesome in home-assistant
[<img src="https://brands.home-assistant.io/_/fortune/icon.png" height="24"/>](https://brands.home-assistant.io/_/fortune/dark_icon.png#gh-dark-mode-only)[<img src="https://brands.home-assistant.io/_/fortune/icon.png" height="24"/>](https://brands.home-assistant.io/_/fortune/icon.png#gh-light-mode-only) [Fortune](https://github.com/oukene/fortune) | Horoscope, Zodiac
[<img src="https://brands.home-assistant.io/_/frigate/icon.png" height="24"/>](https://brands.home-assistant.io/_/frigate/dark_icon.png#gh-dark-mode-only)[<img src="https://brands.home-assistant.io/_/frigate/icon.png" height="24"/>](https://brands.home-assistant.io/_/frigate/icon.png#gh-light-mode-only) [Frigate](https://github.com/blakeblackshear/frigate-hass-integration) | Frigate integration for Home Assistant
[<img src="https://brands.home-assistant.io/_/readme/icon.png" height="24"/>](https://brands.home-assistant.io/_/readme/dark_icon.png#gh-dark-mode-only)[<img src="https://brands.home-assistant.io/_/readme/icon.png" height="24"/>](https://brands.home-assistant.io/_/readme/icon.png#gh-light-mode-only) [Generate Readme](https://github.com/custom-components/readme) | Use Jinja and data from Home Assistant to generate your README.md file
[<img src="https://brands.home-assistant.io/_/grocy/icon.png" height="24"/>](https://brands.home-assistant.io/_/grocy/dark_icon.png#gh-dark-mode-only)[<img src="https://brands.home-assistant.io/_/grocy/icon.png" height="24"/>](https://brands.home-assistant.io/_/grocy/icon.png#gh-light-mode-only) [Grocy Custom Component](https://github.com/custom-components/grocy) | Custom Grocy integration for Home Assistant
[<img src="https://brands.home-assistant.io/_/groqcloud_whisper/icon.png" height="24"/>](https://brands.home-assistant.io/_/groqcloud_whisper/dark_icon.png#gh-dark-mode-only)[<img src="https://brands.home-assistant.io/_/groqcloud_whisper/icon.png" height="24"/>](https://brands.home-assistant.io/_/groqcloud_whisper/icon.png#gh-light-mode-only) [Groqcloud Whisper](https://github.com/fabio-garavini/ha-groq-whisper-stt-api) | HACS custom integration for using GroqCloud speech-to-text (Whisper) API in the Assist pipeline, reducing the workload on the Home Assistant server. 
[<img src="https://brands.home-assistant.io/_/whisper_api_stt/icon.png" height="24"/>](https://brands.home-assistant.io/_/whisper_api_stt/dark_icon.png#gh-dark-mode-only)[<img src="https://brands.home-assistant.io/_/whisper_api_stt/icon.png" height="24"/>](https://brands.home-assistant.io/_/whisper_api_stt/icon.png#gh-light-mode-only) [Ha Whisper Api Stt](https://github.com/davidohne/ha_whisper-api_stt) | Home Assistant Whisper API SST integration
[<img src="https://brands.home-assistant.io/_/hacs/icon.png" height="24"/>](https://brands.home-assistant.io/_/hacs/dark_icon.png#gh-dark-mode-only)[<img src="https://brands.home-assistant.io/_/hacs/icon.png" height="24"/>](https://brands.home-assistant.io/_/hacs/icon.png#gh-light-mode-only) [HACS](https://github.com/hacs/integration) | HACS gives you a powerful UI to handle downloads of all your custom needs.
[<img src="https://brands.home-assistant.io/_/hass-hue-icons-integration/icon.png" height="24"/>](https://brands.home-assistant.io/_/hass-hue-icons-integration/dark_icon.png#gh-dark-mode-only)[<img src="https://brands.home-assistant.io/_/hass-hue-icons-integration/icon.png" height="24"/>](https://brands.home-assistant.io/_/hass-hue-icons-integration/icon.png#gh-light-mode-only) [Hass Hue Icons Integration](https://github.com/arallsopp/hass-hue-icons-integration) | Additional vector icons for home assistant to model Philips Hue bulbs and fixtures. 
[<img src="https://brands.home-assistant.io/_/ical/icon.png" height="24"/>](https://brands.home-assistant.io/_/ical/dark_icon.png#gh-dark-mode-only)[<img src="https://brands.home-assistant.io/_/ical/icon.png" height="24"/>](https://brands.home-assistant.io/_/ical/icon.png#gh-light-mode-only) [Ical Sensor](https://github.com/tybritten/ical-sensor-homeassistant) | an iCal Sensor for Home Assistant
[<img src="https://brands.home-assistant.io/_/icloud3/icon.png" height="24"/>](https://brands.home-assistant.io/_/icloud3/dark_icon.png#gh-dark-mode-only)[<img src="https://brands.home-assistant.io/_/icloud3/icon.png" height="24"/>](https://brands.home-assistant.io/_/icloud3/icon.png#gh-light-mode-only) [Icloud3 V3 Idevice Tracker](https://github.com/gcobb321/icloud3) | iCloud3 v3 - iCloud3 is an advanced iDevice tracker that uses Apple iCloud account and HA Companion App data for presence detection and location based automations.
[<img src="https://brands.home-assistant.io/_/ics_calendar/icon.png" height="24"/>](https://brands.home-assistant.io/_/ics_calendar/dark_icon.png#gh-dark-mode-only)[<img src="https://brands.home-assistant.io/_/ics_calendar/icon.png" height="24"/>](https://brands.home-assistant.io/_/ics_calendar/icon.png#gh-light-mode-only) [Ics Calendar (Icalendar)](https://github.com/franc6/ics_calendar) | Provides an ICS (icalendar) platform for the Home Assistant calendar
[<img src="https://brands.home-assistant.io/_/ingress/icon.png" height="24"/>](https://brands.home-assistant.io/_/ingress/dark_icon.png#gh-dark-mode-only)[<img src="https://brands.home-assistant.io/_/ingress/icon.png" height="24"/>](https://brands.home-assistant.io/_/ingress/icon.png#gh-light-mode-only) [Ingress](https://github.com/lovelylain/hass_ingress) | Home Assistant ingress feature, add additional ingress panels to your Home Assistant frontend.
[<img src="https://brands.home-assistant.io/_/lastfm_scrobbler/icon.png" height="24"/>](https://brands.home-assistant.io/_/lastfm_scrobbler/dark_icon.png#gh-dark-mode-only)[<img src="https://brands.home-assistant.io/_/lastfm_scrobbler/icon.png" height="24"/>](https://brands.home-assistant.io/_/lastfm_scrobbler/icon.png#gh-light-mode-only) [Lastfm Scrobbler](https://github.com/valentin-gosselin/lastfm-scrobbler-ha-integration) | An Home Assistant integration scrobble to last.fm
[<img src="https://brands.home-assistant.io/_/life360/icon.png" height="24"/>](https://brands.home-assistant.io/_/life360/dark_icon.png#gh-dark-mode-only)[<img src="https://brands.home-assistant.io/_/life360/icon.png" height="24"/>](https://brands.home-assistant.io/_/life360/icon.png#gh-light-mode-only) [Life360](https://github.com/pnbruckner/ha-life360) | A Home Assistant integration for Life360.
[<img src="https://brands.home-assistant.io/_/ltss/icon.png" height="24"/>](https://brands.home-assistant.io/_/ltss/dark_icon.png#gh-dark-mode-only)[<img src="https://brands.home-assistant.io/_/ltss/icon.png" height="24"/>](https://brands.home-assistant.io/_/ltss/icon.png#gh-light-mode-only) [Ltss](https://github.com/freol35241/ltss) | Long time state storage (LTSS) custom component for Home Assistant using Timescale DB
[<img src="https://brands.home-assistant.io/_/ms365_calendar/icon.png" height="24"/>](https://brands.home-assistant.io/_/ms365_calendar/dark_icon.png#gh-dark-mode-only)[<img src="https://brands.home-assistant.io/_/ms365_calendar/icon.png" height="24"/>](https://brands.home-assistant.io/_/ms365_calendar/icon.png#gh-light-mode-only) [Microsoft 365   Calendar](https://github.com/RogerSelwyn/MS365-Calendar) | Microsoft 365 Calendar Integration for Home Assistant
[<img src="https://brands.home-assistant.io/_/ms365_mail/icon.png" height="24"/>](https://brands.home-assistant.io/_/ms365_mail/dark_icon.png#gh-dark-mode-only)[<img src="https://brands.home-assistant.io/_/ms365_mail/icon.png" height="24"/>](https://brands.home-assistant.io/_/ms365_mail/icon.png#gh-light-mode-only) [Microsoft 365   Mail](https://github.com/RogerSelwyn/MS365-Mail) | Microsoft 365 Mail Integration for Home Assistant
[<img src="https://brands.home-assistant.io/_/ms365_todo/icon.png" height="24"/>](https://brands.home-assistant.io/_/ms365_todo/dark_icon.png#gh-dark-mode-only)[<img src="https://brands.home-assistant.io/_/ms365_todo/icon.png" height="24"/>](https://brands.home-assistant.io/_/ms365_todo/icon.png#gh-light-mode-only) [Microsoft 365   To Do](https://github.com/RogerSelwyn/MS365-ToDo) | Microsoft 365 To Do Integration for Home Assistant
[<img src="https://brands.home-assistant.io/_/multiscrape/icon.png" height="24"/>](https://brands.home-assistant.io/_/multiscrape/dark_icon.png#gh-dark-mode-only)[<img src="https://brands.home-assistant.io/_/multiscrape/icon.png" height="24"/>](https://brands.home-assistant.io/_/multiscrape/icon.png#gh-light-mode-only) [Multiscrape](https://github.com/danieldotnl/ha-multiscrape) | Home Assistant custom component for scraping (html, xml or json) multiple values (from a single HTTP request) with a separate sensor/attribute for each value. Support for (login) form-submit functionality.
[<img src="https://brands.home-assistant.io/_/mass/icon.png" height="24"/>](https://brands.home-assistant.io/_/mass/dark_icon.png#gh-dark-mode-only)[<img src="https://brands.home-assistant.io/_/mass/icon.png" height="24"/>](https://brands.home-assistant.io/_/mass/icon.png#gh-light-mode-only) [Music Assistant](https://github.com/music-assistant/hass-music-assistant) | Turn your Home Assistant instance into a jukebox, hassle free streaming of your favorite media to Home Assistant media players.
[<img src="https://brands.home-assistant.io/_/naver_finance/icon.png" height="24"/>](https://brands.home-assistant.io/_/naver_finance/dark_icon.png#gh-dark-mode-only)[<img src="https://brands.home-assistant.io/_/naver_finance/icon.png" height="24"/>](https://brands.home-assistant.io/_/naver_finance/icon.png#gh-light-mode-only) [Naver Finance](https://github.com/oukene/naver_finance) | 네이버 금융
[<img src="https://brands.home-assistant.io/_/openai_tts/icon.png" height="24"/>](https://brands.home-assistant.io/_/openai_tts/dark_icon.png#gh-dark-mode-only)[<img src="https://brands.home-assistant.io/_/openai_tts/icon.png" height="24"/>](https://brands.home-assistant.io/_/openai_tts/icon.png#gh-light-mode-only) [Openai Tts Speech Service](https://github.com/sfortis/openai_tts) | OpenAI TTS custom component for HA
[<img src="https://brands.home-assistant.io/_/overseerr/icon.png" height="24"/>](https://brands.home-assistant.io/_/overseerr/dark_icon.png#gh-dark-mode-only)[<img src="https://brands.home-assistant.io/_/overseerr/icon.png" height="24"/>](https://brands.home-assistant.io/_/overseerr/icon.png#gh-light-mode-only) [Overseerr](https://github.com/vaparr/ha-overseerr) | Home Assistant Custom component for Overseerr
[<img src="https://brands.home-assistant.io/_/plex_recently_added/icon.png" height="24"/>](https://brands.home-assistant.io/_/plex_recently_added/dark_icon.png#gh-dark-mode-only)[<img src="https://brands.home-assistant.io/_/plex_recently_added/icon.png" height="24"/>](https://brands.home-assistant.io/_/plex_recently_added/icon.png#gh-light-mode-only) [Plex Recently Added](https://github.com/custom-components/sensor.plex_recently_added) | ▶️ Plex component to feed Upcoming Media Card.
[<img src="https://brands.home-assistant.io/_/powercalc/icon.png" height="24"/>](https://brands.home-assistant.io/_/powercalc/dark_icon.png#gh-dark-mode-only)[<img src="https://brands.home-assistant.io/_/powercalc/icon.png" height="24"/>](https://brands.home-assistant.io/_/powercalc/icon.png#gh-light-mode-only) [Powercalc](https://github.com/bramstroker/homeassistant-powercalc) | Custom component to calculate estimated power consumption of lights and other appliances
[<img src="https://brands.home-assistant.io/_/pyscript/icon.png" height="24"/>](https://brands.home-assistant.io/_/pyscript/dark_icon.png#gh-dark-mode-only)[<img src="https://brands.home-assistant.io/_/pyscript/icon.png" height="24"/>](https://brands.home-assistant.io/_/pyscript/icon.png#gh-light-mode-only) [Pyscript](https://github.com/custom-components/pyscript) | Pyscript adds rich Python scripting to HASS
[<img src="https://brands.home-assistant.io/_/remote_homeassistant/icon.png" height="24"/>](https://brands.home-assistant.io/_/remote_homeassistant/dark_icon.png#gh-dark-mode-only)[<img src="https://brands.home-assistant.io/_/remote_homeassistant/icon.png" height="24"/>](https://brands.home-assistant.io/_/remote_homeassistant/icon.png#gh-light-mode-only) [Remote Home Assistant](https://github.com/custom-components/remote_homeassistant) | Links multiple home-assistant instances together
[<img src="https://brands.home-assistant.io/_/scheduler/icon.png" height="24"/>](https://brands.home-assistant.io/_/scheduler/dark_icon.png#gh-dark-mode-only)[<img src="https://brands.home-assistant.io/_/scheduler/icon.png" height="24"/>](https://brands.home-assistant.io/_/scheduler/icon.png#gh-light-mode-only) [Scheduler Component](https://github.com/nielsfaber/scheduler-component) | Custom component for HA that enables the creation of scheduler entities
[<img src="https://brands.home-assistant.io/_/simpleicons/icon.png" height="24"/>](https://brands.home-assistant.io/_/simpleicons/dark_icon.png#gh-dark-mode-only)[<img src="https://brands.home-assistant.io/_/simpleicons/icon.png" height="24"/>](https://brands.home-assistant.io/_/simpleicons/icon.png#gh-light-mode-only) [Simpleicons](https://github.com/vigonotion/hass-simpleicons) | Use Simple Icons in Home Assistant
[<img src="https://brands.home-assistant.io/_/smartthings_customize/icon.png" height="24"/>](https://brands.home-assistant.io/_/smartthings_customize/dark_icon.png#gh-dark-mode-only)[<img src="https://brands.home-assistant.io/_/smartthings_customize/icon.png" height="24"/>](https://brands.home-assistant.io/_/smartthings_customize/icon.png#gh-light-mode-only) [Smartthings Customize](https://github.com/oukene/smartthings_customize) | None
[<img src="https://brands.home-assistant.io/_/spook/icon.png" height="24"/>](https://brands.home-assistant.io/_/spook/dark_icon.png#gh-dark-mode-only)[<img src="https://brands.home-assistant.io/_/spook/icon.png" height="24"/>](https://brands.home-assistant.io/_/spook/icon.png#gh-light-mode-only) [Spook 👻 Your Homie](https://github.com/frenck/spook) | A scary 👻 powerful toolbox 🧰 for Home Assistant 🏡
[<img src="https://brands.home-assistant.io/_/spotcast/icon.png" height="24"/>](https://brands.home-assistant.io/_/spotcast/dark_icon.png#gh-dark-mode-only)[<img src="https://brands.home-assistant.io/_/spotcast/icon.png" height="24"/>](https://brands.home-assistant.io/_/spotcast/icon.png#gh-light-mode-only) [Spotcast](https://github.com/fondberg/spotcast) | Home assistant custom component to start Spotify playback on an idle chromecast device as well as control spotify connect devices
[<img src="https://brands.home-assistant.io/_/steam_wishlist/icon.png" height="24"/>](https://brands.home-assistant.io/_/steam_wishlist/dark_icon.png#gh-dark-mode-only)[<img src="https://brands.home-assistant.io/_/steam_wishlist/icon.png" height="24"/>](https://brands.home-assistant.io/_/steam_wishlist/icon.png#gh-light-mode-only) [Steam Wishlist](https://github.com/boralyl/steam-wishlist) | A home assistant integration that monitors games on sale on your Steam wishlist.
[<img src="https://brands.home-assistant.io/_/xiaomi_cloud_map_extractor/icon.png" height="24"/>](https://brands.home-assistant.io/_/xiaomi_cloud_map_extractor/dark_icon.png#gh-dark-mode-only)[<img src="https://brands.home-assistant.io/_/xiaomi_cloud_map_extractor/icon.png" height="24"/>](https://brands.home-assistant.io/_/xiaomi_cloud_map_extractor/icon.png#gh-light-mode-only) [Xiaomi Cloud Map Extractor](https://github.com/PiotrMachowski/Home-Assistant-custom-components-Xiaomi-Cloud-Map-Extractor) | This custom integration provides a way to present a live view of a map for Xiaomi (Roborock/Viomi/Roidmi/Dreame) vacuums without a need for rooting.
[<img src="https://brands.home-assistant.io/_/xiaomi_miot/icon.png" height="24"/>](https://brands.home-assistant.io/_/xiaomi_miot/dark_icon.png#gh-dark-mode-only)[<img src="https://brands.home-assistant.io/_/xiaomi_miot/icon.png" height="24"/>](https://brands.home-assistant.io/_/xiaomi_miot/icon.png#gh-light-mode-only) [Xiaomi Miot Auto](https://github.com/al-one/hass-xiaomi-miot) | Automatic integrate all Xiaomi devices to HomeAssistant via miot-spec, support Wi-Fi, BLE, ZigBee devices. 小米米家智能家居设备接入Hass集成
[<img src="https://brands.home-assistant.io/_/weathernews/icon.png" height="24"/>](https://brands.home-assistant.io/_/weathernews/dark_icon.png#gh-dark-mode-only)[<img src="https://brands.home-assistant.io/_/weathernews/icon.png" height="24"/>](https://brands.home-assistant.io/_/weathernews/icon.png#gh-light-mode-only) [웨더뉴스 Weathernews](https://github.com/dugurs/ha-weathernews) | Home Assistant custom component/integration for Weathernews.com

# Home Assistant Add-Ons

I use Home Assistant as my main home server, so there are lots of add-ons. I could run Home Assistant as a VM on a dedicated VM server, but I prefer to keep things simple.

[Enterprise smart home syndrome](https://frenck.dev/the-enterprise-smart-home-syndrome/)

Name | Version | Description
-- | -- | --
AdGuard Home | 5.1.1 | 
Advanced SSH & Web Terminal | 18.0.0 | 
Authelia | 0.1.2 | 
Barcode Buddy for Grocy | dev-docker-based | 
Brother-QL-Web | 0.2.1b3 | 
Browserless Chromium | 2.18.0 | 
ESPHome | 2024.8.3 | 
File editor | 5.8.0 | 
Firefly iii | 6.1.19 | 
Frigate (Full Access) | 0.14.1 | 
Fusion | 2024.7.1 | 
Grafana | 10.0.0 | 
Grocy | 0.21.0 | 
Home Assistant Google Drive Backup | 0.112.1 | 
Jellyfin NAS | 10.9.10 | 
Let's Encrypt | 5.1.4 | 
Mailfilter | 3.1.6 | 
Mailserver | 2.0.8 | 
MariaDB | 2.7.1 | 
Matter Server | 6.4.2 | 
Mealie | v1.12.0-2 | 
Mosquitto broker | 6.4.1 | 
Music Assistant Server | 2.2.3 | 
NGINX Home Assistant SSL proxy | 3.10.1 | 
OpenThread Border Router | 2.10.0 | 
phpMyAdmin | 0.9.1 | 
Samba share | 12.3.2 | 
Studio Code Server | 5.15.0 | 
Victoria Metrics | 1.9.2 | 
Voice Kit FPC | 0.0.1 | 
Whisper | 2.1.2 | 
Z-Wave JS | 0.6.2 | 
Z-Wave JS UI | 3.10.0 | 

# Lovelace Dashboard
## Lovelace plugins
Name | Description
-- | --
[Alarmo Card](https://github.com/nielsfaber/alarmo-card) | Home Assistant card for controlling the Alarmo component
[Apexcharts Card](https://github.com/RomRider/apexcharts-card) | 📈 A Lovelace card to display advanced graphs and charts based on ApexChartsJS for Home Assistant
[Atomic Calendar Revive](https://github.com/totaldebug/atomic-calendar-revive) | An advanced calendar card for Home Assistant Lovelace.
[Auto Entities](https://github.com/thomasloven/lovelace-auto-entities) | 🔹Automatically populate the entities-list of lovelace cards
[Bar Card](https://github.com/custom-cards/bar-card) | Customizable Animated Bar card for Home Assistant Lovelace
[Battery State Card / Entity Row](https://github.com/maxwroc/battery-state-card) | Battery state card for Home Assistant
[Bha Icon Pack](https://github.com/hulkhaugen/hass-bha-icons) | Additional icons for Home Assistant to accompany the MDI icons
[Bubble Card](https://github.com/Clooos/Bubble-Card) | Bubble Card is a minimalist card collection for Home Assistant with a nice pop-up touch.
[Button Card](https://github.com/custom-cards/button-card) | ❇️ Lovelace button-card for home assistant
[Card Mod](https://github.com/thomasloven/lovelace-card-mod) | 🔹 Add CSS styles to (almost) any lovelace card
[Card Tools](https://github.com/thomasloven/lovelace-card-tools) | 🔹A collection of tools for other lovelace plugins to use
[Climate Thermostat Card](https://github.com/fineemb/lovelace-thermostat-card) | Thermostat Lovelace card
[Collapsable Cards](https://github.com/RossMcMillan92/lovelace-collapsable-cards) | A custom Lovelace card that hides other cards behind a dropdown toggle
[Config Editor Card](https://github.com/junkfix/config-editor-card) | Home Assistant Configuration Files Editor for Lovelace
[Custom Brand Icons](https://github.com/elax46/custom-brand-icons) | Custom brand icons for Home Assistant
[Custom Icons](https://github.com/Mariusthvdb/custom-icons) | Several custom made and legacy icons, and icons collected all over the internet in 1 set, UI selectable.
[Custom Icons Pack](https://github.com/MattFryer/Hass-Custom-Icons) | Additional icons for use in Home Assistant UI
[Energy Flow Card Plus](https://github.com/flixlix/energy-flow-card-plus) | An upgraded Energy Distribution Card for Home Assistant, with added features like Individual Devices and refined UI enhancements, while maintaining the Energy Dashboard's original design.
[Firemote Card](https://github.com/PRProd/HA-Firemote) | Apple TV, Amazon Fire TV, Fire streaming stick, Chromecast, NVIDIA Shield, onn., Roku, Xiaomi Mi, and Android TV remote control card for Home Assistant
[Frigate Card](https://github.com/dermotduffy/frigate-hass-card) | A Lovelace card for Frigate in Home Assistant
[Gallery Card 2024](https://github.com/lukelalo/gallery-card) | A custom card for Home Assistant that will display images and/or videos from a folder in the style of a gallery.  
[Ha Floorplan 🖌🎨 | Your Imagination Just Became The New Limit](https://github.com/ExperienceLovelace/ha-floorplan) | Bring new life to Home Assistant. By mapping entities to a SVG-object, you're able to control devices, show states, calling services - and much more. Add custom styling on top, to visualize whatever you can think of. Your imagination just became the new limit.
[Hass Dual Color Icons](https://github.com/sisimomo/hass-dual-color-icons) | Dual colors vector icons for Home Assistant. These icons are dual color counter fit of other home assistant icons set like Material Design Icons (MDI) or hass-hue-icons.
[Hass Hue Icons](https://github.com/arallsopp/hass-hue-icons) | Additional vector icons for home assistant to model Philips  Hue bulbs and fixtures. 
[Honeycomb Menu](https://github.com/Sian-Lee-SA/honeycomb-menu) | Honeycomb menu is a Home Assistant module (not a card) that can be applied to any lovelace card. When activated by the defined action on said card, the module will display a 'rounded' list of honeycomb buttons with an optional XY pad to make interfacing with lovelace more fluent
[Hui Element](https://github.com/thomasloven/lovelace-hui-element) | 🔹 Use built-in elements in the wrong place
[Kiosk Mode](https://github.com/NemesisRE/kiosk-mode) | 🙈 Hides the Home Assistant header and/or sidebar
[Knx User Forum Icon Set](https://github.com/mampfes/ha-knx-uf-iconset) | Icon set from KNX User Forum for Home Assistant. The icon set contains more than 900 icons for home automation.
[Layout Card](https://github.com/thomasloven/lovelace-layout-card) | 🔹 Get more control over the placement of lovelace cards.
[List Card](https://github.com/iantrich/list-card) | 📰 Display sensor list data in a table
[Logbook Card](https://github.com/royto/logbook-card) | Logbook card for Home Assistant UI Lovelace
[Lovelace Card Templater](https://github.com/gadgetchnnel/lovelace-card-templater) | Custom Lovelace card which allows Jinja2 templates to be applied to other cards
[Lovelace Grocy Chores Card](https://github.com/isabellaalstrom/lovelace-grocy-chores-card) | A card to track chores and tasks in Grocy.
[Lovelace Home Feed Card](https://github.com/gadgetchnnel/lovelace-home-feed-card) | A custom Lovelace card for displaying a combination of persistent notifications, calendar events, and entities in the style of a feed.
[Map Card](https://github.com/nathan-gs/ha-map-card) | A Map Card for Home Assistant
[Maxi Media Player](https://github.com/punxaphil/maxi-media-player) | Media card for Home Assistant UI with a focus on managing multiple media players, but not excluding single player setups.
[Meal Plan Card   Lovelace Style](https://github.com/firstof9/lovelace-grocy-meal-plan-card) | Meal Plan Card for Home Assistant Grocy integration
[Mini Graph Card](https://github.com/kalkih/mini-graph-card) | Minimalistic graph card for Home Assistant Lovelace UI
[Mini Media Player](https://github.com/kalkih/mini-media-player) | Minimalistic media card for Home Assistant Lovelace UI
[More Info Card](https://github.com/thomasloven/lovelace-more-info-card) | 🔹 Display the more-info dialog of any entity as a lovelace card
[Multiple Entity Row](https://github.com/benct/lovelace-multiple-entity-row) | Show multiple entity states and attributes on entity rows in Home Assistant's Lovelace UI
[Mushroom](https://github.com/piitaya/lovelace-mushroom) | Build a beautiful Home Assistant dashboard easily
[Nintendo Wishlist Card](https://github.com/custom-cards/nintendo-wishlist-card) | Displays a card showing Nintendo Switch games that are on sale from your wish list.
[Power Flow Card Plus](https://github.com/flixlix/power-flow-card-plus) | A power distribution card inspired by the official Energy Distribution card for Home Assistant
[Scheduler Card](https://github.com/nielsfaber/scheduler-card) | HA Lovelace card for control of scheduler entities
[Stack In Card](https://github.com/custom-cards/stack-in-card) | 🛠 group multiple cards into one card without the borders
[State Switch](https://github.com/thomasloven/lovelace-state-switch) | 🔹Dynamically replace lovelace cards depending on occasion
[Steam Card](https://github.com/mkanet/kb-steam-card-plus) | An enhanced version of the Steam card with builtin support for current custom Roblox integration
[Tabbed Card](https://github.com/kinghat/tabbed-card) | a custom card for home assistant that utilizes tabs to segregate individual cards.
[Template Entity Row](https://github.com/thomasloven/lovelace-template-entity-row) | 🔹 Display whatever you want in an entities card row.
[Upcoming Media Card](https://github.com/NemesisRE/upcoming-media-card) | 📺 A card to display upcoming episodes and movies from services like: Plex, Kodi, Radarr, Sonarr, and Trakt.
[Vacuum Card](https://github.com/denysdovhan/vacuum-card) | Vacuum cleaner card for Home Assistant Lovelace UI
[Xiaomi Vacuum Map Card](https://github.com/PiotrMachowski/lovelace-xiaomi-vacuum-map-card) | This card provides a user-friendly way to fully control map-based vacuums in Home Assistant. Supported brands include Xiaomi (Roborock/Viomi/Dreame/Roidmi/Valetudo/Valetudo RE), Neato, Wyze, Roomba, Ecovacs (and probably more).

## Themes
Name | Description
-- | --
[Metrology   Metro + Fluent + Windows Themes   By Mmak.Es](https://github.com/Madelena/Metrology-for-Hass) | 🎨 Give your Home Assistant a modern and clean facelift. 🟥🟧🟩🟦🟪 24 Variations with 2 Styles + 6 Colors (Magenta Red / Orange / Green / Blue / Purple) + 🌞 Light and 🌚 Dark modes included. Based on Metro and Fluent UI Design Systems from Microsoft Windows.
[Mushroom Themes](https://github.com/piitaya/lovelace-mushroom-themes) | Additional themes for Lovelace Mushroom Cards 🍄

***

Generated by the [custom readme integration](https://github.com/custom-components/readme)

Huge Thanks to [Joris Roovers](https://github.com/jorisroovers), this work is heavily influenced by his [work](https://github.com/jorisroovers/casa)

<!-- Footnotes -->
[^1]: UI Configuration

[commits-shield]: https://img.shields.io/github/commit-activity/y/saya6k/home-assistant-config.svg
[commits]: https://github.com/saya6k/home-assistant-config/commits/master
[contributors]: https://github.com/saya6k/home-assistant-config/graphs/contributors
[saya]: https://github.com/saya6k
[home-assistant]: https://home-assistant.io
[issue]: https://github.com/saya6k/home-assistant-config/issues
[license-shield]: https://img.shields.io/github/license/saya6k/home-assistant-config.svg
[maintenance-shield]: https://img.shields.io/maintenance/yes/2024.svg
[last-commit-shield]: https://img.shields.io/github/last-commit/saya6k/home-assistant-config.svg
[stars-shield]: https://img.shields.io/github/stars/saya6k/home-assistant-config.svg?style=social&label=Stars
[forks-shield]: https://img.shields.io/github/forks/saya6k/home-assistant-config.svg?style=social&label=Forks
[watchers-shield]: https://img.shields.io/github/watchers/saya6k/home-assistant-config.svg?style=social&label=Watchers