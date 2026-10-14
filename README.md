# HandRacer

HandRacer is a Unity racing game that lets players drive with Leap Motion hand gestures or a keyboard. Race against an AI opponent, or compete in a two-player race with one keyboard player and one gesture player. Speed boost zones and item boxes add variety to each race.

## Download and play

1. Download the Windows ZIP file from the [latest release](../../releases/latest).
2. Extract the **entire** ZIP file to a folder.
3. Run `HandRacer.exe` from that folder. Keep `HandRacer_Data`, `MonoBleedingEdge`, `UnityPlayer.dll`, and the other included files beside the executable.

For gesture control, connect a compatible Leap Motion device and install its required tracking software. Then launch the game with the `-leap` argument. For example, in PowerShell, run this from the extracted game folder:

```powershell
& ".\HandRacer.exe" -leap
```

You can also create a Windows shortcut and add ` -leap` after the quoted executable path in its **Target** field.

## Controls

| Keyboard | Action |
| --- | --- |
| `W` | Accelerate |
| `S` | Brake / reverse |
| `A` / `D` | Steer left / right |
| `Space` | Pick up or use an item |

| Leap Motion gesture | Action |
| --- | --- |
| Press the left hand down | Accelerate; lower means faster |
| Rotate the left hand left or right | Steer |
| Push the right hand forward | Activate or use the current item |

For best gesture detection, keep your hands approximately **25–60 cm above the sensor**.

## Game modes

- **AI Battle:** Race against an AI opponent using keyboard or gesture controls.
- **Online Battle:** Two players race against each other; Player 1 uses the keyboard and Player 2 uses Leap Motion gestures.

## Project files

This repository shares the game documentation and a downloadable Windows build. The Unity editor project is not included in this build. To open or modify the game in Unity, the original project files are needed, including `Assets`, `Packages`, and `ProjectSettings`.

---

## 中文说明

HandRacer 是一款 Unity 赛车游戏，支持键盘和 Leap Motion 手势操控。你可以与电脑对战，也可以让一位玩家使用键盘、另一位玩家使用手势进行双人比赛。赛道包含加速区域和道具箱。

从[最新版本](../../releases/latest)下载 Windows ZIP，**完整解压**后运行 `HandRacer.exe`。使用手势前，请连接 Leap Motion 设备并安装所需的追踪软件，再用 `-leap` 参数启动游戏。键盘操作为 `W` 加速、`S` 刹车或倒车、`A/D` 转向、空格键拾取或使用道具。手势操作为左手下压加速、左手左右旋转转向、右手前推使用道具；建议双手位于传感器上方约 25–60 厘米。
