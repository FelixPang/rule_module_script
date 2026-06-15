# Egern Config

Egern configuration snippets and JavaScript widgets.

## Widgets

### World Cup Schedule

- Script: `scripts/WorldCup_Widget.js`
- Config snippet: `configs/WorldCup_Widget.yaml`
- Surge module: `configs/WorldCup_Surge.sgmodule`
- Data source: ESPN FIFA World Cup (`fifa.world`)

Default widget env:

```yaml
# No env is required when using the default ESPN source.
```

The widget shows yesterday, today, and tomorrow in Beijing time. The default ESPN source does not require an API key or environment variables. Finished matches show scores, live matches show `进行中`, and scheduled matches show kickoff time. Team names are displayed in Chinese with country flags when the team can be matched.

Surge panel module:

```text
https://raw.githubusercontent.com/FelixPang/ProxyKit/main/configs/WorldCup_Surge.sgmodule
```

### QWeather

- Script: `scripts/QWeather_Widget.js`
