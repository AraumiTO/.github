# Araumi TO 
[![Discord](https://img.shields.io/discord/1233336064052301835?style=for-the-badge&logo=discord&logoColor=ffffff&label=discord&link=https%3A%2F%2Fdiscord.gg%2Feuug57b7NQ)](https://discord.gg/euug57b7NQ)
<div align="center">

![](https://araumi.org/assets/logo.webp)

</div>

## About the game

Tanki Online is a massively multiplayer online game that was released in 2009.
It is a free-to-play game that can be played directly in a web browser, and it was popular for many years.

However, with the obsolescence of Flash technology, game developers decided to make an HTML5 version of the game. The Flash version of the game was completely shut down on December 2, 2020.

## About the project

Araumi TO reimplements the server for the Tanki Online official client. The goal of this project is to support the Flash version of the game so players can enjoy the original Tanki Online gameplay expierence.

This project is currently under development, and it has not yet been determined when it will be publicly available — you can follow the development status on [our website](https://araumi.org/) or [discord server](https://discord.gg/euug57b7NQ).

Please note that HTML5 and mobile version support of the game is not a primary goal of the Araumi TO, and they **may or may not** be supported in the future.

## Features

You can see the game features and their status in the following tables.

* ✅ - The feature is fully implemented and working as intended.
* ⚒️ - Work is currently being done on the feature.
* 🚧 - A prototype version of the feature is implemented. For example, behavior models may not be fully functional yet and/or use dummy data.
* ❌ - The feature has not been implemented yet.
* 🛑 - The feature is not planned to be implemented in the future.

### Authentication

| Feature            | Status | Notes                                   |
|--------------------|--------|-----------------------------------------|
| Login              | ✅     |                                         |
| Registration       | ✅     | Alternative nicknames are not generated |
| Email verification | ❌     |                                         |
| Password reset     | ❌     |                                         |
| Captcha            | ❌     |                                         |

### Lobby

| Feature       | Status | Notes                         |
|---------------|--------|-------------------------------|
| Battle list   | ✅     |                               |
| Battle create | ⚒️     | Battle settings are ignored   |
| Battle info   | ✅     |                               |
| Matchmaking   | 🚧     | Matchmaker is not implemented |
| Global chat   | ⚒️     |                               |

### Garage

| Feature            | Status | Notes                                  |
|--------------------|--------|----------------------------------------|
| Tank preview       | ✅     |                                        |
| Item mounting      | ✅     |                                        |
| Item buying        | ❌     |                                        |
| Micro-upgradess    | ❌     |                                        |
| Hulls              | ✅     |                                        |
| Weapons            | ✅     |                                        |
| Paints             | ✅     |                                        |
| Supplies           | 🚧     |                                        |
| Kits               | ❌     |                                        |
| Containers         | 🚧     |                                        |
| Resistance modules | ❌     |                                        |
| Subscriptions      | ❌     | Premium account, PRO-battle, etc.      |
| Presents           | ❌     |                                        |

### Battles

| Feature             | Status | Notes                         |
|---------------------|--------|-------------------------------|
| Battle join / leave | ✅     |                               |
| Tank (re)spawn      | ✅     |                               |
| Self-destruction    | ✅     |                               |
| Bonuses             | 🚧     | Taking is not implemented     |
| Supplies            | 🚧     | Activation is not implemented |
| Damage system       | 🚧     |                               |
| Fund                | ❌     |                               |
| Score system        | ❌     |                               |
| Battle finish       | 🚧     |                               |

#### Quests

| Feature       | Status | Notes |
|---------------|--------|-------|
| Daily quests  | ❌     |       |
| Weekly quests | ❌     |       |
| Challenges    | ❌     |       |

#### Battle modes

| Mode                   | Status | Notes                                 |
|------------------------|--------|---------------------------------------|
| Deathmatch (DM)        | 🚧     | Score system is required              |
| Team Deathmatch (TDM)  | 🚧     | Score system is required              |
| Capture the Flag (CTF) | 🚧     | Score system is required              |
| Control Points (CP)    | 🚧     |                                       |
| Assault (ASL)          | ❌     |                                       |
| Rubgy (RGB)            | ❌     |                                       |
| Juggernaut (JGR)       | ❌     |                                       |
| Team Juggernaut (TJR)  | ❌     |                                       |
| Siege (SGE)            | 🛑     |                                       |

#### Weapons

| Name         | Status | Notes                               |
|--------------|--------|-------------------------------------|
| Smoky        | ⚒️     |                                     |
| Flamethrower | ⚒️     |                                     |
| Twins        | ⚒️     |                                     |
| Railgun      | ⚒️     |                                     |
| Isida        | ⚒️     |                                     |
| Thunder      | ⚒️     |                                     |
| Freeze       | ⚒️     |                                     |
| Ricochet     | ⚒️     |                                     |
| Shaft        | ⚒️     |                                     |
| Hammer       | ⚒️     |                                     |
| Vulcan       | ⚒️     |                                     |
| Striker      | ⚒️     |                                     |
| Magnum       | ⚒️     |                                     |
| Gauss        | ⚒️     |                                     |
| Terminator   | ⚒️     |                                     |
| Snowman      | ❌     |                                     |
| Tomato Gun   | ❌     |                                     |
| Tesla        | 🛑     | Not implemented in the Flash client |
| B0-NK        | 🛑     | Not implemented in the Flash client |
| Scorpion     | 🛑     | Not implemented in the Flash client |

#### Hulls

| Name       | Status | Notes                               |
|------------|--------|-------------------------------------|
| Wasp       | ✅     |                                     |
| Hunter     | ✅     |                                     |
| Titan      | ✅     |                                     |
| Dictator   | ✅     |                                     |
| Hornet     | ✅     |                                     |
| Viking     | ✅     |                                     |
| Mammonth   | ✅     |                                     |
| Juggernaut | ✅     |                                     |
| Ares       | 🛑     |                                     |
| Hopper     | 🛑     |                                     |
| Crusader   | 🛑     | Not implemented in the Flash client |
| Paladin    | 🛑     | Not implemented in the Flash client |

#### Paints

| Name              | Status | Notes                        |
|-------------------|--------|------------------------------|
| Old paints        | ❌     | Before rebalance (patch 114) |
| New paints        | ❌     |                              |
| Animated paints   | ❌     |                              |
| Paint resistances | ❌     |                              |
