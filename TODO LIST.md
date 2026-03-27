# 📋 待解决问题

```tasks
not done
group by function \
    const headings = task.file.cachedMetadata?.headings; \
    if (!headings) return ''; \
    headings.sort((a, b) => b.position.start.line - a.position.start.line); \
    const topHeading = headings.find(h => h.level === 1 && h.position.start.line < task.lineNumber); \
    return topHeading ? topHeading.heading : '(未分类)';
sort by function reverse \
    const priorityNum = task.priorityNumber; \
    if (priorityNum !== undefined && priorityNum !== null) return priorityNum; \
    const desc = task.description; \
    if (desc.includes('🔺') || desc.includes('⏫')) return 3; \
    if (desc.includes('🔽')) return 1; \
    return 2;
sort by due date
short mode
```

---

# 数学方面
## 微积分
## 线性代数
## 概率论
## 复变函数
- [ ] 📅 2026-03-26 复数函数的多值到底是怎么来的 ⏫
# 物理方面
## 力学
## 热学
## 理论力学
- [ ] 🔽 知道朗道的那一套推导过程 🔽 📅 2026-04-02
## 电磁学
## 电动力学
- [ ] 📅 2026-03-28 🔺  我不知道为什么这里将不知道的叉乘，并且对于方向我一无所知。
- [ ] 📅 2026-03-29 🔽 狠狠地看一遍Griffiths的书关于E和D，B和H的相似性的评注。
- [ ] 📅 2026-03-29 欧姆定律
- [ ] 📅 2026-03-26 ⏫ Griffiths的第七章电动力学导论和守恒定律
## 光学
- [ ] 📅 2026-03-30 🔽 跟上课程
