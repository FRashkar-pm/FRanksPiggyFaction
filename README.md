## FRanksPiggyFaction

A simple plugin addon for <a target="_blank" href="https://poggit.pmmp.io/p/RankSystem/">RankSystem</a> from IvanCraft623 to support <a target="_blank" href="https://poggit.pmmp.io/p/PiggyFactions/">PiggyFactions</a> from DaPigGuy.

## CustomTags

- Player faction name `{fac_name}`

## How to use this plugin

- Open plugin_data /RankSystem/resources
- Add `{fac_name}` in format config.yml
- Restart your server

## Example

```yaml
nametag:
  enabled: true
  format: "{nametag_ranks_prefix}{nametag_name-color}{name}§e[§3{fac_name}§e]§r"

#Configure users's chat
chat:
  enabled: true
  format: "{chat_ranks_prefix}{chat_name-color}{name}§e[§3{fac_name}§e]§r{chat_format}{message}"
```

## Credits

<a target="_blank" href="https://icons8.com/icon/ujEZSSRjrsMQ/rank">Rank</a> icon by <a target="_blank" href="https://icons8.com">Icons8</a>
