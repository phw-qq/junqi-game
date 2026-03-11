# 军棋游戏 GitHub Pages 部署指南

## 快速部署（3 分钟搞定）

### 第 1 步：创建 GitHub 仓库

1. 打开 https://github.com/new
2. 仓库名：`junqi-game`
3. 设为 **Public**（公开）
4. 不要勾选 "Add README"
5. 点击 **Create repository**

### 第 2 步：推送代码

在终端执行以下命令（复制粘贴）：

```bash
cd /home/admin/.openclaw/workspace/junqi-game
git remote add origin https://github.com/phw-qq/junqi-game.git
git branch -M main
git push -u origin main
```

### 第 3 步：开启 GitHub Pages

1. 进入仓库页面：https://github.com/phw-qq/junqi-game
2. 点击 **Settings**（设置）
3. 左侧菜单找到 **Pages**
4. **Source** 选择 `Deploy from a branch`
5. **Branch** 选择 `main`，文件夹选 `/(root)`
6. 点击 **Save**

### 第 4 步：等待部署（约 1-2 分钟）

刷新 Pages 页面，会看到你的游戏链接：
```
https://phw-qq.github.io/junqi-game/
```

✅ 完成！这个链接 QQ 里直接能点开！

---

## 游戏说明

- 12x8 棋盘，48 个棋子
- 红蓝双方各 25 子
- 支持翻棋、移动、攻击
- 完整军棋规则（司令到工兵、炸弹、地雷、军旗）

## 分享

把链接发给 QQ 好友，直接点开就能对战！🎮
