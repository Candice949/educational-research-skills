# 教育学研究 AI 工作流

专为高等教育研究者设计的 AI 助手工具集，聚焦于女生高等教育体验研究。

## 项目特色

本项目集成了 3 个 AI skill，形成完整的教育学研究工作流：

| 阶段 | Skill | 功能 | 使用场景 |
|------|-------|------|---------|
| 选题 | `literature-finder` | SSCI 文献快速检索 | 论文选题、文献综述、研究议题设计 |
| 申报 | `proposal-helper` | 课题申报助手 | 国家/省级课题申报书撰写与检查 |
| 反馈 | `assignment-feedback` | 学生作业/论文反馈 | 学生作业评阅、论文初稿反馈、质量把控 |

## 研究方向

- 高等教育中学生尤其是女生的就读体验
- 大学生归属感、学业适应与心理健康
- 校园支持系统与教育公平
- 性别差异与教学环境设计

## 项目结构

```
educational-research-skills/
├── README.md
├── WORKFLOW.md
├── KEYWORDS.md
├── EXAMPLES.md
├── skills/
│   ├── literature-finder/
│   │   └── SKILL.md
│   ├── proposal-helper/
│   │   └── SKILL.md
│   └── assignment-feedback/
│       └── SKILL.md
└── templates/
    ├── proposal-template.md
    ├── literature-review-template.md
    └── feedback-rubric.md
```

## 快速开始

### 1. 论文选题阶段
使用 `literature-finder`：

输入：
```
检索：大学女生在高等教育中的就读体验
```

输出：
- 相关 SSCI 论文 3–5 篇
- 关键词建议
- 研究空白与可选题方向

### 2. 课题申报阶段
使用 `proposal-helper`：

输入：
```
帮我检查这份课题申报书
[粘贴申报书内容]
```

输出：
- 研究意义是否充分
- 理论基础是否清晰
- 创新点是否突出
- 可行性评估
- 改进建议

### 3. 论文/作业反馈阶段
使用 `assignment-feedback`：

输入：
```
请对这篇学生论文进行评阅
[粘贴论文初稿]
```

输出：
- 研究问题与目标清晰度
- 文献综述质量
- 研究设计合理性
- 论证逻辑
- 总体评级和具体建议

## 工作流说明

```
选题与文献阅读
  ↓
  用 literature-finder 检索相关论文
  ↓
  生成文献综述与研究空白

课题设计与申报
  ↓
  起草课题申报书
  ↓
  用 proposal-helper 自检与改进
  ↓
  提交申报

执行与产出
  ↓
  学生小组研究
  ↓
  用 assignment-feedback 进行反馈
  ↓
  完成论文产出
```

## 适用人群

- 高校教师
- 研究生导师
- 教育学研究者
- 课题申报参与者
- 教育学论文写作者
