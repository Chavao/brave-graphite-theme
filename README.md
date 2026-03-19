# Brave Graphite Premium

Refined dark theme for Brave Browser, inspired by graphite/black UI with moderate contrast and a more premium look.

## Features

* Nearly black top frame
* Dark graphite toolbar
* Active tab with clean contrast
* Bright active text and slightly desaturated inactive text
* Omnibox matching the top bar
* More balanced look than extreme AMOLED themes

## Installation

1. Go to:
   `brave://extensions`
2. Enable **Developer mode**
3. Click **Load unpacked**
4. Select this theme folder

## Notes

If there is a policy forcing Brave’s color, such as:

```json
{ "BrowserThemeColor": "#000000" }
```

disable it before installing the extension:

```bash
sudo mv /etc/brave/policies/managed/theme.json /etc/brave/policies/managed/theme.json.bak
```

Fully close Brave and open it again.

## Structure

```text
brave-graphite-premium/
├── LICENSE
├── manifest.json
└── README.md
```
