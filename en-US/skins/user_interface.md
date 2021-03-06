---
name: User Interface
---

# Skinning the User Interface

The gameplay interface includes general skin elements that are present in all game modes. It includes elements such as cursor, main menu skinning, song select skinning, pause interface.

## Cursor

### Main Cursor

`/Cursor/main-cursor.png`

![Main Cursor](/docs/images/Cursor/main-cursor.png)

| Animatable | Alignment | Suggested Size |
| :--------: | :-------: | :------------: |
|     No     | MidCenter |      None      |

**Notes:**

- The mouse cursor that is displayed.
- Hidden during gameplay. Active during menu navigation.

---

## Main Menu Skinning

### Menu Background

`/MainMenu/menu-background.png`

![Menu Background](/docs/images/MainMenu/menu-background.png)

| Animatable | Alignment | Optimal Size |
| :--------: | :-------: | :----------: |
|     No     | MidCenter |  1920x1080   |

**Notes:**

- The background image of the main menu.

---

### Navigation Buttons

###### Deselected Texture Location: `/MainMenu/navigation-button.png`

![Deselected Navigation Button](/docs/images/MainMenu/navigation-button.png)

###### Selected Texture Location: `/MainMenu/navigation-button-selected.png`

![Selected Navigation Button](/docs/images/MainMenu/navigation-button-selected.png)

| Animatable | Alignment | Optimal Size |
| :--------: | :-------: | :----------: |
|     No     |  MidLeft  |    434x52    |

**Notes:**

- The buttons to navigate to different parts of the game (single player, multiplayer, etc)

---

### Menu Tip Panel

`/MainMenu/tip-panel.png`

![Tip Panel](/docs/images/MainMenu/menu-tip-panel.png)

| Animatable |  Alignment  | Optimal Size |
| :--------: | :---------: | :----------: |
|     No     | BottomRight |    484x52    |

**Notes:**

- The panel that displays a random tip.

---

### News Post Panel

`/MainMenu/news-panel.png`

![News Panel](/docs/images/MainMenu/news-panel.png)

| Animatable |  Alignment  | Optimal Size |
| :--------: | :---------: | :----------: |
|     No     | BottomRight |   484x261    |

**Notes:**

- The panel that displays the most recent news post.

---

### Footer Jukebox

`/MainMenu/jukebox-overlay.png`

![Jukebox Overlay](/docs/images/MainMenu/jukebox-overlay.png)

| Animatable |  Alignment   | Optimal Size |
| :--------: | :----------: | :----------: |
|     No     | BottomCenter |    500x54    |

**Notes:**

- The jukebox that displays in the footer of the main menu.

---

## Menu Border Skinning

### Menu Border

`/MenuBorder/menu-border-background.png`

![Menu Borders](/docs/images/MenuBorder/menu-border-background.png)

| Animatable |       Alignment        | Optimal Size |
| :--------: | :--------------------: | :----------: |
|     No     | TopCenter/BottomCenter |   1920x64    |

**Notes:**

- The top and bottom borders of the screen. This will display on every screen.

---

## Song Select Skinning

### Mapset Panel Selection

###### Deselected Texture Location: `/SongSelect/mapset-deselected.png`

![Deselected Mapset Panel](/docs/images/SongSelect/mapset-deselected.png)

###### Selected Texture Location: `/SongSelect/mapset-selected.png`

![Selected Mapset Panel](/docs/images/SongSelect/mapset-selected.png)

###### Hovered Texture Location: `/SongSelect/mapset-hovered.png`

![Hovered Mapset Panel](/docs/images/SongSelect/mapset-hovered.png)

| Animatable | Alignment | Optimal Size |
| :--------: | :-------: | :----------: |
|     No     | MidRight  |   1188x86    |

**Notes:**

- The background image of mapset panel. Does not cover the map's banner.

---

### Mapset Panel Status

###### Ranked Texture Location: `/SongSelect/status-ranked.png`

![Ranked Status](/docs/images/SongSelect/status-ranked.png)

###### Unranked Texture Location: `/SongSelect/status-unranked.png`

![Unranked Status](/docs/images/SongSelect/status-unranked.png)

###### Unsubmitted Texture Location: `/SongSelect/status-notsubmitted.png`

![Not Submitted Status](/docs/images/SongSelect/status-not-submitted.png)

###### Osu Mapset Texture Location: `/SongSelect/status-osu.png`

![Osu Mapset Status](/docs/images/SongSelect/status-other-game-osu.png)

###### Stepmania/Etterna Mapset Texture Location: `/SongSelect/status-sm.png`

![Stepmania/Etterna Mapset Status](/docs/images/SongSelect/status-other-game-etterna.png)

| Animatable | Alignment | Optimal Size |
| :--------: | :-------: | :----------: |
|     No     | MidRight  |    115x28    |

**Notes:**

- The status of the mapset.

---

### Mapset Panel Game Mode

###### 4k Texture Location: `/SongSelect/game-mode-4k.png`

![4k Mode](/docs/images/SongSelect/keys4.png)

###### 7k Texture Location: `/SongSelect/game-mode-7k.png`

![7k Mode](/docs/images/SongSelect/keys7.png)

###### 4k+7k Texture Location: `/SongSelect/game-mode-4k7k.png`

![4k+7k Mode](/docs/images/SongSelect/both-modes-panel.png)

| Animatable | Alignment | Optimal Size |
| :--------: | :-------: | :----------: |
|     No     | MidRight  |    71x28     |

**Notes:**

- The key mode of the mapset.

---

### Leaderboard Panel

###### Leaderboard Panel location: `/SongSelect/leaderboard-panel.png`

![Leaderboard Panel](/docs/images/SongSelect/leaderboard-panel.png)

| Animatable | Alignment | Optimal Size |
| :--------: | :-------: | :----------: |
|     No     |  MidLeft  |   564x664    |

**Notes:**

- The leaderboard panel of the skin.

---

### Personal Best Panel

###### Personal Best Panel location: `/SongSelect/personalbest-panel.png`

![Personal Best Panel](/docs/images/SongSelect/personalbest-panel.png)

| Animatable | Alignment | Optimal Size |
| :--------: | :-------: | :----------: |
|     No     |  MidLeft  |    564x70    |

**Notes:**

- The personal best panel of the skin.