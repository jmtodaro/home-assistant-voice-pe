# Home Assistant Voice: Preview Edition - Streaming Wake Word

The vanilla branch.

This is basically a direct port of [RobMeads' modifications](https://github.com/RobMeades/home-assistant-voice-pe/blob/dev/home-assistant-voice.yaml) to the [current dev branch](https://github.com/esphome/home-assistant-voice-pe/commit/dc2b9b72657bd5b44812ab184c958a29cda5a7ac), with most of the expected behavior of the official firmware restored.

A number of questionable workarounds were employed, mostly in correcting led ring states, audio ducking, and adding the ability to silence the timer bell via streaming wake word, as can be done with the official non-streaming version.

**Use it at your own risk.** But I can tell you that it's working great on my HAVPE!

---

# Home Assistant Voice: Preview Edition

This is the ESPHome source code of the [Home Assistant Voice: Preview Edition](https://www.home-assistant.io/voice-pe/).

See [the documentation](https://voice-pe.home-assistant.io/) for set up and troubleshooting.

If you need to re-install the firmware, [use this installer](https://esphome.github.io/home-assistant-voice-pe/).
