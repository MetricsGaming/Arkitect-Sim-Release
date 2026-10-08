# Arkitect Sim

Arkitect Sim keeps trying to join an ARK: Survival Ascended server for you, and can alert your phone the moment you're in.

## Download

Download `ArkitectSim.exe` from the [latest release](https://github.com/MetricsGaming/Arkitect-Sim-Release/releases/latest).

Windows may warn that the app is from an unknown publisher. To run it, click **More info**, then **Run anyway**.

## Requirements

- Windows 10 or 11
- ARK: Survival Ascended

## Get started

1. Start ARK: Survival Ascended and go to the main menu.
2. Run `ArkitectSim.exe`.
3. In the **SERVER** box, enter the number of the server you want, such as `2391`.
4. Click **START SIM**, or press **F9**.

The sim stops by itself once you're in a server.

| Key | Action |
| --- | --- |
| **F9** | Start or stop the sim |
| **F10** | Reload the sim, for example after restarting ARK |
| **F12** | Exit |

## Phone alerts

Arkitect Sim can send alerts to your phone through the free [ntfy](https://ntfy.sh) app when you get into a server or when the sim stops.

To set up phone alerts, follow these steps:

1. Install the ntfy app on your phone.
2. In Arkitect Sim, go to the **Alerts** page and click **Phone setup**.
3. Scan the code with your phone's camera, then open the link.
4. Click **Send test** and check that the alert arrives.
5. Turn on **Send push notifications**.

**Caution:** Anyone who knows your ntfy topic can read your alerts. Use **New topic** for a random one, and don't show the **Phone setup** window on stream.

## Updates

Arkitect Sim checks for a new version each time it starts. When there is one, it asks whether to update, then downloads it, checks that the download is intact, and restarts. If you choose not to update yet, click **Update to vX** in the bottom corner of the window when you're ready. Arkitect Sim never updates while the sim is running.

## Your settings

Arkitect Sim saves your settings in `sim.ini`, next to the exe. The file includes your ntfy topic, so don't share it.
