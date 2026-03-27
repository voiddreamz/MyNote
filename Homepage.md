---
created: 2025-03-21
type: homepage
---

# 🏠 MyNote Dashboard

---

## 📋 今日任务

```tasks
not done
due today
sort by priority
```

## ⏰ 即将到期

```tasks
not done
due after today
due before in two weeks
sort by due date
limit 10
```

## 🔴 已逾期

```tasks
not done
due before today
sort by due date
limit 5
```

---

## 📚 快速导航

### 数学
| 笔记                    | 描述       |
| --------------------- | -------- |
| [[数学/高数I\|高数I]]       | 高等数学上册   |
| [[数学/高数II\|高数II]]     | 高等数学下册   |
| [[数学/微积分补充\|微积分补充]]   | 微积分补充笔记  |
| [[数学/级数\|级数]]         | 级数相关     |
| [[数学/复变函数\|复变函数]]     | 复变函数     |
| [[数学/概率论\|概率论]]       | 概率论与数理统计 |
| [[数学/数理方程\|数理方程]]     | 数学物理方程   |
| [[数学/矢量微积分基础\|矢量微积分]] | 矢量微积分    |

### 物理
| 笔记 | 描述 |
|------|------|
| [[物理/电磁学+电动力学/电磁学\|电磁学]] | 电磁学基础 |
| [[物理/电磁学+电动力学/电动力学\|电动力学]] | 电动力学 |
| [[物理/量子力学\|量子力学]] | 量子力学 |
| [[物理/光学\|光学]] | 光学 |
| [[物理/分析力学\|分析力学]] | 分析力学 |
| [[物理/狭义相对论\|狭义相对论]] | 狭义相对论 |

### 其他
| 笔记 | 描述 |
|------|------|
| [[泛函分析\|泛函分析]] | 泛函分析 |
| [[传感器组成原理\|传感器]] | 传感器组成原理 |
| [[题目收集\|题目收集]] | 题目汇总 |
| [[阅读有感/古文的力量\|古文的力量]] | 阅读笔记 |

---

## 📝 最近编辑

```dataview
TABLE
  file.mtime as "修改时间",
  file.folder as "目录"
FROM ""
WHERE file.name != "Homepage"
AND file.name != "未命名"
SORT file.mtime DESC
LIMIT 8
```

---

## 📊 笔记统计

```dataview
TABLE WITHOUT ID
  length(rows) as "笔记数量"
FROM ""
WHERE file.name != "Homepage"
GROUP BY true
```

| 目录 | 笔记数 |
|------|--------|
| 数学 | `= length(filter(dv.pages('"数学"'), (p) => p.file.name))` |
| 物理 | `= length(filter(dv.pages('"物理"'), (p) => p.file.name))` |
| 手写 | `= length(filter(dv.pages('"Handwrites"'), (p) => p.file.name))` |

---

## 🖊️ 快捷操作

> [!tip] 快速创建
> - [[数学/|📝 新建数学笔记]]
> - [[物理/|📝 新建物理笔记]]
> - [[Handwrites/|🖊️ 新建手写笔记]]

---

*最后更新: `$= dv.current().file.mtime`*