# Block Elevators

<table>
	<thead>
		<tr>
			<th align="center">English</th>
			<th align="center"><a href="README_ja.md">日本語</a></th>
		</tr>
	</thead>
</table>

A Paper plugin that lets you create elevators by stacking blocks vertically.

Create elevators with blocks. Jump up, sneak down.

## Demo

<a href="https://youtu.be/RzJluRqwEJk">
  <img src="https://img.youtube.com/vi/RzJluRqwEJk/maxresdefault.jpg" alt="Block Elevators Demo" width="500">
</a>

## Download

- [GitHub Releases](https://github.com/ryusei-sky/Block-Elevators/releases/latest)
- [Modrinth](https://modrinth.com/plugin/block-elevators)

## Features

- Configurable elevator blocks
- Customizable elevator behavior
- Create hidden elevators using liquids, carpets, slabs, and other blocks
- Supports Paper 1.21.x

## Installation

1. Place the JAR file into your server's `plugins` folder.
2. Start or restart your server.
3. Edit `config.yml` to customize the plugin.

## Commands

| Command | Description |
|----------|-------------|
| `/block-elevators-reload` | Reload config |

## Permissions

| Permission | Description | Default |
|------------|-------------|---------|
| `blockelevators.use` | Use elevators | `true` |
| `blockelevators.reload` | Reload config | `op` |

## config.yml

```yml
# Permissions:
# blockelevators.use - Use elevators (Default: true)
# blockelevators.reload - Reload config (Default: op)

# Worlds where elevators are enabled
# Empty list means all worlds
worlds: []
#  - world

# Cooldown between elevator uses (seconds)
# 0 disables cooldown
cooldown: 0

# Materials to be used as elevator blocks
materials:
  - IRON_BLOCK

# Maximum search range
# 0 means unlimited
max-search-range: 0

sound:
  enable: true
  name: entity.iron_golem.attack
  volume: 1.0
  jump-pitch: 1.2
  sneak-pitch: 0.8
```

## License

[MIT License](https://files.ryusei.space/docs/mit.txt)
