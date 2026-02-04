# Pactbound-Wardens
Ever wished your enemies would fight by your side? Seal a pact to recruit mobs as loyal wardens: follow, hold, guard a post, or patrol a radius you choose. (No dependencies)

# [EN] Pactbound Wardens (v1.0.0)

**Ever wished your enemies would fight by your side?**  
Use the **Contract Sigil** to bind mobs into loyal wardens. They can follow you into the wild, hold position, guard your base from a post, or patrol a radius you choose.

**Game Version:** 1.20.1  
**Loader:** Forge  
**Environment:** Client + Server (BOTH)  
**Dependencies:** None  
**License:** MIT  
**Mod ID:** `contractedguards`

---

## Features
* **Contract mobs** with the Contract Sigil *(costs **5 XP levels**)*  
  * Contracted mobs **glow permanently** and **won’t naturally despawn**
* **4 modes** (cycle with **Shift + Right Click** on a contracted mob)
  * **Follow** → **Hold** → **Guard Post** → **Patrol**
* **Guard Post**: defend around a chosen point (great for bases)
* **Patrol Anchor**: patrol inside a chosen radius (great for farms/perimeters)
* **Clear range preview**
  * Opening the Post/Anchor GUI pulses a boundary ring
  * Holding the Contract Sigil continuously previews your current point range
* **Smart combat rules**
  * Contracted mobs attack **hostile mobs only** (Enemies)
  * Never attacks the owner or any contracted mob (no friendly fire)
  * Prioritizes attackers when the owner is hurt
* **Special: Contracted Creeper**
  * AOE blast **without block damage**
  * Won’t suicide-detonate
  * Never damages owner/players/contracted mobs

---

## How to Play (Quick Start)
### Crafting
* **Contract Sigil**: Paper + Redstone + Iron Ingot + Stick  
* **Guard Post**: Iron Ingot + Stick + Oak Planks  
* **Patrol Anchor**: Stone + Iron Ingot  
* **Manual Book**: Book + Paper (shapeless)

### Contract & Commands
1. Hold **Contract Sigil** and **Right Click** a mob to contract *(cost: 5 XP levels)*  
2. **Shift + Right Click** a contracted mob to cycle modes  
3. Place a **Guard Post** / **Patrol Anchor**, then **Right Click** to open GUI  
   * Opening the GUI sets it as your **current point** automatically  
   * Cycle radius: **8 / 16 / 24 / 32**

---

## FAQ
* **“My guard doesn’t attack anything.”**  
  They only attack **hostile mobs (Enemies)**. Passive/neutral mobs are ignored.
* **“It says no current point.”**  
  Place a Post/Anchor and open its GUI once (it auto-sets as current).
* **“How do I quickly see the range?”**  
  Open the GUI / cycle radius (particle ring), or hold the Contract Sigil.

---

## Planned for 2.0
* Contract **Clauses** (behavior “contract terms” system)
* **Patrol route editor** (player-built routes)
* **Alarm + redstone** outputs for Posts/Anchors
* **Goat Horn commands** (formation/rally orders)

---

## Credits
Created by **CZ**.


---

# [简体中文] Pactbound Wardens（v1.0.0）

**你想让你的敌人和你并肩战斗吗？**  
使用 **契约符印（Contract Sigil）** 与生物签订契约，让它们成为忠诚守卫：探索跟随、原地待命、岗哨守卫、半径巡逻。

**游戏版本：** 1.20.1  
**加载器：** Forge  
**环境：** Client + Server (BOTH)  
**依赖：** 无  
**许可证：** MIT  
**Mod ID：** `contractedguards`

---

## 功能
* 使用契约符印**签订契约**（消耗 **5 级经验**）
  * 契约后生物会**永久发光**，并且**不会自然消失**
* **四种模式**（对契约生物 **Shift+右键**循环）
  * 跟随 → 待命 → 岗哨守卫 → 巡逻
* **守卫岗（Guard Post）**：以指定点为中心防守（护家神器）
* **巡逻锚点（Patrol Anchor）**：在指定半径内巡逻（农场/外围警戒）
* **清晰范围预览**
  * 打开岗哨/锚点 GUI 会短暂显示边界粒子圈
  * 手持契约符印可持续预览“当前点”的范围
* **战斗规则**
  * 只攻击**敌对怪物（Enemy）**
  * 不会攻击主人或其它契约单位（无友伤）
  * 主人被攻击时会优先反击攻击者
* **特殊：契约苦力怕**
  * AOE 伤害**不破坏方块**
  * 不自爆死亡
  * 不伤害主人/玩家/契约单位

---

## 快速上手
### 合成
* **契约符印**：纸 + 红石 + 铁锭 + 木棍  
* **守卫岗**：铁锭 + 木棍 + 橡木木板  
* **巡逻锚点**：石头 + 铁锭  
* **说明书**：书 + 纸（无序合成）

### 操作
1. 手持契约符印，对生物**右键**签订契约（消耗 5 级经验）  
2. 对契约生物 **Shift+右键** 循环切换模式  
3. 放置守卫岗/巡逻锚点并**右键打开 GUI**  
   * 打开 GUI 会自动设置为你的**当前点**  
   * 半径切换：**8 / 16 / 24 / 32**

---

## 常见问题
* **不攻击？** 只打敌对怪物（Enemy），中立/被动生物会被忽略。  
* **提示没有当前点？** 放置并打开一次岗哨/锚点 GUI 即可自动设置。  
* **怎么快速看范围？** 打开 GUI/切换半径会显示粒子圈；手持契约符印也会持续预览。

---

## 2.0 计划
* **契约条款**（用“条款”改变行为）
* **巡逻路线编辑**（玩家自定义路线）
* **警报 + 红石输出**
* **山羊角指令**（集合/队列命令）

---

## 署名
作者：**CZ**。

---

# [繁體中文] Pactbound Wardens（v1.0.0）

**想讓你的敵人與你並肩戰鬥嗎？**  
使用 **契約符印（Contract Sigil）** 與生物簽訂契約，讓它們成為忠誠守衛：探索跟隨、原地待命、崗哨守衛、半徑巡邏。

**遊戲版本：** 1.20.1  
**載入器：** Forge  
**環境：** Client + Server (BOTH)  
**依賴：** 無  
**授權：** MIT  
**Mod ID：** `contractedguards`

---

## 功能
* 使用契約符印**簽訂契約**（消耗 **5 級經驗**）
  * 契約後生物會**永久發光**，並且**不會自然消失**
* **四種模式**（對契約生物 **Shift+右鍵**循環）
  * 跟隨 → 待命 → 崗哨守衛 → 巡邏
* **守衛崗（Guard Post）**：以指定點為中心防守（護家好用）
* **巡邏錨點（Patrol Anchor）**：在指定半徑內巡邏（農場/外圍警戒）
* **清楚的範圍預覽**
  * 開啟崗哨/錨點 GUI 會短暫顯示邊界粒子圈
  * 手持契約符印可持續預覽「目前點」範圍
* **戰鬥規則**
  * 只攻擊**敵對怪物（Enemy）**
  * 不會攻擊主人或其它契約單位（無友傷）
  * 主人被攻擊時會優先反擊攻擊者
* **特殊：契約苦力怕**
  * AOE 傷害**不破壞方塊**
  * 不自爆死亡
  * 不傷害主人/玩家/契約單位

---

## 快速上手
### 合成
* **契約符印**：紙 + 紅石 + 鐵錠 + 木棍  
* **守衛崗**：鐵錠 + 木棍 + 橡木木板  
* **巡邏錨點**：石頭 + 鐵錠  
* **說明書**：書 + 紙（無序合成）

### 操作
1. 手持契約符印，對生物**右鍵**簽訂契約（消耗 5 級經驗）  
2. 對契約生物 **Shift+右鍵** 循環切換模式  
3. 放置守衛崗/巡邏錨點並**右鍵開啟 GUI**  
   * 開啟 GUI 會自動設為你的**目前點**  
   * 半徑切換：**8 / 16 / 24 / 32**

---

## 常見問題
* **不攻擊？** 只打敵對怪物（Enemy），中立/被動生物會被忽略。  
* **提示沒有目前點？** 放置並開啟一次崗哨/錨點 GUI 即可自動設定。  
* **怎麼快速看範圍？** 開啟 GUI/切換半徑會顯示粒子圈；手持契約符印也會持續預覽。

---

## 2.0 計畫
* **契約條款**（用「條款」改變行為）
* **巡邏路線編輯**（玩家自訂路線）
* **警報 + 紅石輸出**
* **山羊角指令**（集合/隊列命令）

---

## 署名
作者：**CZ**。

---

# [日本語] Pactbound Wardens（v1.0.0）

**敵だったMobを味方にしたい？**  
**契約の印章（Contract Sigil）** で契約し、Mobを忠実な護衛に変えよう。探索の同行・その場待機・拠点警備・半径巡回まで、用途に合わせて使い分けできます。

**対応バージョン：** 1.20.1  
**ローダー：** Forge  
**動作環境：** Client + Server (BOTH)  
**依存Mod：** なし  
**ライセンス：** MIT  
**Mod ID：** `contractedguards`

---

## 特徴
* **契約**：契約の印章でMobを契約（**経験値レベル 5** 消費）
  * 契約したMobは**常に発光**し、**自然デスポーンしません**
* **4つのモード**（契約Mobに **Shift+右クリック**で循環）
  * Follow → Hold → Guard Post → Patrol
* **Guard Post（守衛岗）**：指定地点の周囲を警備（拠点防衛向き）
* **Patrol Anchor（巡邏錨点）**：指定半径内を巡回（外周・農場向き）
* **範囲表示が分かりやすい**
  * GUIを開く/半径変更で境界リングの粒子表示
  * 契約の印章を持っている間、現在地点の範囲を常時プレビュー
* **戦闘ルール**
  * 攻撃対象は**敵対Mob（Enemy）のみ**
  * オーナーや他の契約Mobには攻撃しない（フレンドリーファイア無し）
  * オーナーが攻撃された場合、加害者を優先して反撃
* **特殊：契約クリーパー**
  * **ブロック破壊なし**の範囲攻撃
  * 自爆で死なない
  * オーナー/プレイヤー/契約Mobにはダメージなし

---

## 使い方（クイックスタート）
### クラフト
* **Contract Sigil**：紙 + レッドストーン + 鉄インゴット + 棒  
* **Guard Post**：鉄インゴット + 棒 + オークの板材  
* **Patrol Anchor**：石 + 鉄インゴット  
* **マニュアル本**：本 + 紙（不定形）

### 操作
1. 契約の印章を持ってMobに**右クリック**（経験値 5 消費）  
2. 契約Mobに **Shift+右クリック**でモード切替  
3. Guard Post / Patrol Anchor を設置して**右クリックでGUI**  
   * GUIを開くと自動的に「現在地点」に設定  
   * 半径：**8 / 16 / 24 / 32**

---

## FAQ
* **攻撃しない**：敵対Mob（Enemy）のみ攻撃します。中立/受動Mobは無視されます。  
* **現在地点が無い**：Post/Anchor を設置してGUIを一度開いてください（自動設定）。  
* **範囲をすぐ見たい**：GUIを開く/半径変更で粒子リング表示。契約の印章を持つと常時表示。

---

## 2.0 予定
* **契約条項（Clause）**：条項で行動を細かく調整
* **巡回ルート編集**：プレイヤーが巡回ルートを作成
* **警報 + レッドストーン出力**
* **ヤギの角コマンド**：集合などの隊列命令

---

## クレジット
作者：**CZ**。
