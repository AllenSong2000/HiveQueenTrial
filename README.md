# Hive Queen's Trial / 蜂后试炼

Two unofficial Hollow Knight boss mods: **Vespa** (Hive Queen Vespa, a complete new boss fight) and **GrimmFlamewing** (one extra move, Crimson Wings, for Troupe Master Grimm). Neither depends on the other or on any other mod. Free, non-commercial.

**Download ⇒ [Releases](https://github.com/AllenSong2000/HiveQueenTrial/releases/latest)** · [Trailer (Bilibili)](https://www.bilibili.com/video/BV19rHG6EENt/) · [简体中文](#简体中文)

One set of zips per game build: file names carry `HK1.5.12620` (current build) or `HK1.5.78.11833` (older build). Check your game version on the main menu and take the matching set. Each zip's SHA256 and the changelog are on the Releases page; every zip also carries a `SHA256.json`.

## Contents

### Vespa
Hive Queen Vespa — the queen's ghost deep in the Hive, beside her body. Once you own the **Hiveblood** charm, strike her with the Dream Nail to enter the dream fight. In Godhome a new statue of her stands on the first floor of the Hall of Gods (three tiers), and she also appears in the Pantheon of Hallownest.
The first dream victory upgrades Hiveblood into **Hive Queen's Blood**, with its own charm icon. Comes with her own battle track "Hive Queen" and a Hunter's Journal entry. Once her statue has been cleared at any tier, dream-nail the orb on its base to face the **Absolute Hive Queen**, a far harder version of the fight.

### GrimmFlamewing
Grimm's **Crimson Wings** — one extra move for the native Troupe Master Grimm (tent fight and Hall of Gods): he teleports high above the arena centre, spreads his cape and fires 3 / 5 / 7 / 9 waves of straight-flying firebats, with three ground pillars under each wave.
Picked by Grimm's own random move selection; entrance, health, phases and rewards are untouched. Also fixes the vanilla stun-bat swarm roll that made the black bats drift one way (can be switched off in the Mods menu).

## Install
- Check your game version first (bottom-left of the main menu) and download the matching set; the two sets cannot be mixed.
- **Lumafly** (recommended): install the Modding API through Lumafly, then "Manually Install" the `Vespa-…zip` and the `GrimmFlamewing-…zip` **one at a time**.
  Do **not** feed the bundle `HiveQueenTrial-…zip` to Lumafly — it would nest everything in one folder and neither mod would load.
- **By hand**: unzip the bundle and drop the `Vespa/` and `GrimmFlamewing/` folders into `hollow_knight_Data/Managed/Mods/`, so that
  `Mods/Vespa/Vespa.dll` and `Mods/GrimmFlamewing/GrimmFlamewing.dll` exist.
- Updating: delete the old `Mods/Vespa` and `Mods/GrimmFlamewing` folders first, then install the new ones.

## Notes
- Back up your saves first (`%USERPROFILE%\AppData\LocalLow\Team Cherry\Hollow Knight\user*.dat`); not recommended on Steel Soul saves yet.
- Both game builds have been played through by testers on Windows; Mac / Linux are untested. Please report anything you hit.

## Feedback
Please include the mod version, the game version, a full recording, and the `Player.log` + `ModLog.txt` of the same session
(`%USERPROFILE%\AppData\LocalLow\Team Cherry\Hollow Knight`). Log lines from the mods start with `VESPA_` / `GRIMMFLAMEWING_`.
Contact: songallen462@gmail.com · GitHub AllenSong2000

## Credits and copyright
- Design and code: 独游Allen (Indie game Allen)
- Statue art and Hive Queen's Blood charm icon: PaintBag(包子) (used with permission)
- Recoloured Vespa frames: an artist uncredited for now (used with permission)
- Battle track "Hive Queen": 独游Allen (Indie game Allen)
- Hollow Knight / Hollow Knight: Silksong characters, art and sound: Team Cherry
- Both mods are unofficial, non-commercial fan works distributed free of charge and not affiliated with Team Cherry; no game, API or third-party mod files are included. Full notices: [NOTICE.md](NOTICE.md) and the `NOTICE.txt` inside each zip.

## Licensing
The author has not authorised any third-party port of this mod. Without written permission from the relevant rights holders, the mod's original code, music and added assets may not be ported to other platforms, nor integrated, modified or repackaged for distribution; credits may not be removed, and the mod may not be presented as an official release. For licensing enquiries contact the author. Rights to the base game and third-party material remain with their respective owners.

---

## 简体中文

Hollow Knight 非官方 boss 模组合集:**Vespa**(蜂巢女王维斯帕,一场完整的新 boss 战)+ **GrimmFlamewing**(给剧团团长格林加一招「猩红之翼」)。
两个模组互不依赖、也不依赖其它模组,可以只装一个。免费、非商业。

**下载 ⇒ [Releases](https://github.com/AllenSong2000/HiveQueenTrial/releases/latest)** · [宣传片(B 站)](https://www.bilibili.com/video/BV19rHG6EENt/)
每个游戏版本一组包,文件名里带 `HK1.5.12620`(当前版本)或 `HK1.5.78.11833`(老版);每个 zip 的 SHA256 与更新记录都在 Releases 页面,zip 内另有 `SHA256.json`。

### 内容

**Vespa** —— 蜂巢女王维斯帕:蜂巢深处蜂后遗体旁的鬼魂,拿到蜂巢之血护符后,用梦之钉入梦开打;神居万神殿大厅新增她的雕像(三档难度),圣巢万神殿里也有她。
首次梦中获胜后,蜂巢之血升级为「蜂后之血」,有自己的护符图标。自带战斗曲《Hive Queen》与猎人日志条目。雕像任意一档打过之后,用梦之钉点亮底座的球,可以挑战难得多的「无上蜂后」。

**GrimmFlamewing** —— 格林「猩红之翼」:给原版的剧团团长格林(帐篷战与神居)加一招空中扇形火蝠齐射,传送到场地中央高处张开斗篷,按血量放 3 / 5 / 7 / 9 波直飞火蝠,每波脚下三根地火柱。
由格林自己的随机选招挑出,入场、血量、阶段、奖励一概不动。顺带修了原版黑蝙蝠群只往一边漂的掷骰 bug(模组菜单可关)。

### 安装
- 先看游戏版本(主菜单左下角),下对应那一组;两组不能混用。
- **Lumafly**(推荐):先用 Lumafly 装好 Modding API,然后「手动安装」(Manually Install)**分别**选 `Vespa-…zip` 和 `GrimmFlamewing-…zip`。
  整包 `HiveQueenTrial-…zip` **不能**喂给 Lumafly —— 它会把整包塞进一个文件夹,两个模组都找不到。
- **手动**:解压整包,把 `Vespa/` 和 `GrimmFlamewing/` 两个文件夹放进 `hollow_knight_Data/Managed/Mods/`,
  最终应为 `Mods/Vespa/Vespa.dll` 与 `Mods/GrimmFlamewing/GrimmFlamewing.dll`。
- 更新:先删掉旧的 `Mods/Vespa`、`Mods/GrimmFlamewing` 再放新的。

### 注意
- 请先备份存档(`%USERPROFILE%\AppData\LocalLow\Team Cherry\Hollow Knight\user*.dat`),暂不建议在钢魂档使用。
- 两个游戏版本都有测试人员在 Windows 上实机打过;Mac / Linux 未实测。遇到问题请反馈。

### 反馈
请附:模组版本号、游戏版本、完整录像、同一局的 `Player.log` 与 `ModLog.txt`
(目录 `%USERPROFILE%\AppData\LocalLow\Team Cherry\Hollow Knight`)。日志行前缀:`VESPA_` / `GRIMMFLAMEWING_`。
联系:songallen462@gmail.com · GitHub AllenSong2000

### 署名与版权
- 设计与代码:独游Allen(Indie game Allen)
- 雕像图、蜂后之血护符图标:PaintBag(包子) 绘制,授权用于本模组
- 维斯帕若干帧的复原上色:暂不署名的画师 绘制,授权用于本模组
- 战斗音乐 "Hive Queen":独游Allen(Indie game Allen)
- Hollow Knight / Hollow Knight: Silksong 的角色、美术与音效:Team Cherry
- 两个模组都是非官方、非商业的同人作品,免费发布,与 Team Cherry 无关;包内不含游戏、API 或其他模组的文件。完整版权说明见 [NOTICE.md](NOTICE.md) 与各包内 `NOTICE.txt`。

### 授权声明
本人未授权任何第三方移植版本。未经相关权利人书面许可,不得将本模组原创代码、音乐及新增素材跨平台移植,或整合、修改、重打包后分发;不得移除署名或冒充官方版本。授权事宜请联系作者。原游戏及第三方素材权利归各自权利人。
