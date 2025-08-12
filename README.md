# Livonia Fast Travel
Hub based fast travel for DayZ Livonia. This fast travel system works on PC and console.

## Installation

Copy all files in the `custom` folder into the `dayzOffline.enoch\custom` folder in your DayZ installation directory.

1. Add the following line to the `objectSpawnersArr` section in your `cfggameplay.json` file:
```json
[
  "./custom/fast-travel.json"
]
```

2. Add the following lines to the `playerRestrictedAreaFiles` section in your `cfggameplay.json` file:
```json
[
  "./custom/fast-travel-adamow-hub.json",
  "./custom/fast-travel-bielawa-hub.json",
  "./custom/fast-travel-brenna-hub.json",
  "./custom/fast-travel-dolnik-hub.json",
  "./custom/fast-travel-gieraltow-hub.json",
  "./custom/fast-travel-gliniska-hub.json",
  "./custom/fast-travel-grabin-hub.json",
  "./custom/fast-travel-hub-adamow.json",
  "./custom/fast-travel-hub-bielawa.json",
  "./custom/fast-travel-hub-brenna.json",
  "./custom/fast-travel-hub-dolnik.json",
  "./custom/fast-travel-hub-gieraltow.json",
  "./custom/fast-travel-hub-gliniska.json",
  "./custom/fast-travel-hub-grabin.json",
  "./custom/fast-travel-hub-kolembrody.json",
  "./custom/fast-travel-hub-lembork.json",
  "./custom/fast-travel-hub-lukow.json",
  "./custom/fast-travel-hub-nadbor.json",
  "./custom/fast-travel-hub-olszanka.json",
  "./custom/fast-travel-hub-polana.json",
  "./custom/fast-travel-hub-radacz.json",
  "./custom/fast-travel-hub-sitnik.json",
  "./custom/fast-travel-hub-sobotka.json",
  "./custom/fast-travel-hub-tarnow.json",
  "./custom/fast-travel-hub-topolin.json",
  "./custom/fast-travel-hub-wrzeszcz.json",
  "./custom/fast-travel-hub-zalesie.json",
  "./custom/fast-travel-kolembrody-hub.json",
  "./custom/fast-travel-lembork-hub.json",
  "./custom/fast-travel-lukow-hub.json",
  "./custom/fast-travel-nadbor-hub.json",
  "./custom/fast-travel-olszanka-hub.json",
  "./custom/fast-travel-polana-hub.json",
  "./custom/fast-travel-radacz-hub.json",
  "./custom/fast-travel-sitnik-hub.json",
  "./custom/fast-travel-sobotka-hub.json",
  "./custom/fast-travel-tarnow-hub.json",
  "./custom/fast-travel-topolin-hub.json",
  "./custom/fast-travel-wrzeszcz-hub.json",
  "./custom/fast-travel-zalesie-hub.json"
]
```

3. Make sure `Enable cfggameplay.json` is checked in your Nitrado configuration.

4. Restart your server and enjoy!