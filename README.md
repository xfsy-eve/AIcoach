# 幸福双翼教育AI学习教练

**个性化AI学习教练 · v1.0.0（第一版）**

让 AI 根据孩子的真实作答，一步一步引导思考，并持续安排有针对性的小练习。

这是一个在 **Codex 中使用的 Skill（技能）**，相当于一套可重复使用的辅导规则。适合家长陪伴小学、初中、高中孩子使用。

## 第一次使用，从这里开始

📖 **[小白使用手册](使用手册.md)**：从安装、建立档案，到上传作业、日常练习和下次续接，都有可复制的指令。

在 Codex 中发送下面这段话，安装本仓库的技能：

```text
请使用 $skill-installer，从下面的 GitHub 地址安装 child-learning-coach 技能：
https://github.com/Eveline160919103/AI-/tree/main/child-learning-coach
安装后请检查技能文件是否完整，并告诉我是否已安装成功。
```

已安装的用户可以直接发送：

```text
请用 $child-learning-coach，为孩子建立学习档案。
```

随后按提示填写年级、教材版本、学科、目前成绩、学习特点、近期目标。不清楚的信息可以先留空。

## 一次辅导怎样进行

1. 识别题目与孩子作答，等家长或孩子对照原材料确认。
2. 引用具体作答证据，选择本次最值得解决的一个薄弱点。
3. 一次只问一个问题，逐步提示，等孩子自己作答。
4. 用一道同类变式题和一次孩子复述，核验理解情况。
5. 根据实际结果安排一周练习，每天一个小任务。
6. 更新学习记录，向家长给出诊断、目标、每日练习和周末复盘建议。

表达方式会按小学低、中、高年级及初高中调整；辅导策略也会依据当前孩子的实际学习证据持续修正。

## 文件说明

| 文件 | 用途 |
| --- | --- |
| [使用手册.md](使用手册.md) | 家长从零开始的操作说明 |
| [child-learning-coach/SKILL.md](child-learning-coach/SKILL.md) | 教练的完整工作规则 |
| [child-learning-coach/references/learner-records.md](child-learning-coach/references/learner-records.md) | 学习档案格式、保存和续接规则 |
| [child-learning-coach/agents/openai.yaml](child-learning-coach/agents/openai.yaml) | 技能名称、简介及启动提示 |

## 使用约定

以孩子当前年级和已学内容为准，不代写作业，不承诺成绩提升，也不凭一次错误判断能力。学习记录只有实际写入文件后才算保存；跨任务使用时，需要读取同一份档案。

真实试卷、孩子作答与个人学习档案请保存在自己的学习文件夹中。本仓库用于分发技能和手册，不用于上传孩子资料。

安装与调用方式参考 [OpenAI 官方技能文档](https://learn.chatgpt.com/docs/build-skills)，具体操作见本仓库的使用手册。
