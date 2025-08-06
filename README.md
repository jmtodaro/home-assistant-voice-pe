# Home Assistant Voice: Preview Edition - Streaming Wake Word

So this is basically a direct port of [RobMeads' modifications](https://github.com/RobMeades/home-assistant-voice-pe/blob/dev/home-assistant-voice.yaml) to the [current dev branch](https://github.com/esphome/home-assistant-voice-pe/commit/dc2b9b72657bd5b44812ab184c958a29cda5a7ac), with most of the expected behavior of the official firmware restored.

A number of questionable workarounds were employed, mostly in correcting led ring states, audio ducking, and adding the ability to silence the timer bell via streaming wake word, as can be done with the official non-streaming version.

If you'd like to add a touch of class, try merging my experimental [light_effect_on_idle](https://github.com/jmtodaro/home-assistant-voice-pe/tree/light_effect_on_idle) branch and/or the [announce_led](https://github.com/jmtodaro/home-assistant-voice-pe/tree/announce_led) branch. Or use the [streaming_wake_word-experimental](https://github.com/jmtodaro/home-assistant-voice-pe/tree/streaming_wake_word-experimental) branch which has both of these patched in already.

**light_effect_on_idle:** Adds a toggleable feature to display a subtle twinkle effect when assistant is idle. This also has a bonus feature of exposing any additional [light effects](https://esphome.io/components/light/index.html#light-effects) you add, which can then in theory be used with automations *(untested)*.

**announce_led:** A toggleable feature that displays the "replying" led ring animation when receiving incoming announcements from Home Assistant. Funny story--I thought I was restoring existing functionality to the streaming wake word version when I did this, but as it turns out official doesn't actually do this *(yet?)*.

Both of these features are built against, and can also be used with, the official non-streaming firmware.

---

# Home Assistant Voice: Preview Edition

This is the ESPHome source code of the [Home Assistant Voice: Preview Edition](https://www.home-assistant.io/voice-pe/).

See [the documentation](https://voice-pe.home-assistant.io/) for set up and troubleshooting.

If you need to re-install the firmware, [use this installer](https://esphome.github.io/home-assistant-voice-pe/).
