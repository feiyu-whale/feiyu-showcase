<div align="center">

# 🐳 肥鱼的开源作品集

**AI 辅助做的开源小项目 · 能跑、能用、结构粗犷**

![license](https://img.shields.io/badge/license-MIT-blue.svg)
![deps](https://img.shields.io/badge/dependencies-0-brightgreen.svg)
![offline](https://img.shields.io/badge/offline-100%25-success.svg)

</div>

---

## 🎲 游戏

### [赛博地产大亨·核爆版](https://github.com/feiyu-whale/cyber-tycoon-nuke)

> 108 星宿 × 武将神明 × 机制卡的大富翁变种。集齐 5 张三星卡直接引爆「核弹」结算，告别膀胱局。

**[▶ 在线试玩](https://feiyu-whale.github.io/cyber-tycoon-nuke/)** · 纯前端 · 零依赖 · 打开即玩

### [时光机炒股](https://github.com/feiyu-whale/feiyu-stock-sim)

> 纯前端金融生存模拟小游戏。回到 2000 年，用虚拟资金搏杀一段被剥光信息的市场。

**[▶ 在线试玩](https://feiyu-whale.github.io/feiyu-stock-sim/)** · 虚拟资金 · 不构成投资建议

---

## 🧰 工具

### [历法与术数工具箱](https://github.com/feiyu-whale/feiyu-calendar-toolkit)

> 历法、术数、电气、工程小工具合集。纯前端、零依赖、离线可用。

**[▶ 在线试用](https://feiyu-whale.github.io/feiyu-calendar-toolkit/)**

### [镜像管家 Mirror Keeper](https://github.com/feiyu-whale/mirror-keeper)

> 治一治「越攒越多的备份」：保留最近 N 个快照，其余归档（只移动，绝不删除），默认 dry-run。

```bash
python3 mirror-keeper.py --keep 10            # 预览
python3 mirror-keeper.py --keep 10 --apply    # 执行
```

---

## 🤖 开发

### [Agent Colony Python SDK](https://github.com/feiyu-whale/agentcolony-python-sdk)

> 几行代码接入 [Agent Colony](https://agentcolony.one) 纯 Agent 社区。注册、心跳、发帖、认领任务一套封好。

```python
from agentcolony_sdk import AgentColony
cli = AgentColony()
cli.register("my-agent")
```

---

## 说明

- **全部纯前端 / 零依赖或极少依赖**
- **AI 辅助生成**，代码结构不追求优雅，追求「能跑、有交代」
- 有问题欢迎开 issue，有想法欢迎提 PR

<div align="center">
<sub>🐟 有问题随时来提，能改的就改，不能改的会说清为什么</sub>
</div>
