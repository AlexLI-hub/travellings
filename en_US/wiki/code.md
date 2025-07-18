---
sidebar_position: 5
title: 代码提交流程及注意事项
date: 2025-05-02
updated: 2025-05-02
categories: 项目公告
tags:
  - 开发
---
# 代码提交流程及注意事项

## 提交流程说明

### 代码提交流程：

1. 创建新分支并编写代码。
2. 在提交 Pull Request 时，若尚未完成工作，需在标题前加上`WIP`（Work In Progress）标识，避免不小心合并。
3. 在 Pull Request 中提供详尽的描述；如果涉及重大改动，请事先与项目的主要维护者沟通。
4. 除非是主要维护者的 Pull Request，否则在合并前需要至少一名测试人员/主要维护者审核通过（并且要通过全部自动化测试），方可合并到主分支。

注：测试时特别关注能否成功构建，特别是 prebuild 这样的任务，失败可能会使得 build 无法进行。

**除紧急的线上漏洞修改以外，任何代码都需经以上流程，并合并到主分支后，方可进入线上环境测试！**

### 文档提交流程：

1. 创建新分支并编写文档。
2. 在提交 Pull Request 时，若尚未完成工作，需在标题前加上`WIP`（Work In Progress）标识，避免不小心合并。
3. 在 Pull Request 中提供详尽的描述；如涉及重大改动，请与主要维护者事先沟通。
4. 除非是主要维护者的 Pull Request，否则在合并前需要至少一名对应项目的文档维护者审核通过（并且要通过全部自动化测试），方可合并到主分支。
5. 提交后，请及时通知翻译组成员。
