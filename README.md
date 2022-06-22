# kiosk-mode2


Hides the header and/or sidebar drawer in [Home Assistant](https://www.home-assistant.io/)

## Config Options

| Config Option | Type | Default | Description |
|:---------------|:---------------|:---------------|:----------|
|`kiosk:`| Boolean | false | Hides both the header and sidebar.
|`hide_header:` | Boolean | false | Hides only the header.
|`hide_sidebar:` | Boolean | false | Hides only the sidebar. Disables swipe to open.
|`hide_menubutton:` | Boolean | false | Hides only the sidebar menu icon. Does not disable swipe to open.
|`hide_overflow:` | Boolean | false | Hides the top right menu.
|`ignore_entity_settings:` | Boolean | false | Useful for [conditional configs](#conditional-lovelace-config) and will cause `entity_settings` to be ignored.
|`ignore_mobile_settings:` | Boolean | false | Useful for [conditional configs](#conditional-lovelace-config) and will cause `mobile_settings` to be ignored.

