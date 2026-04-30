它是一个 AI 代码库巡检与重构规划 Agent，功能包括：

扫描本地代码库，识别硬编码密钥、危险 eval/exec、裸 except、复杂函数、TODO/FIXME、缺失 CI、调试日志等问题；然后通过多 Agent 流程生成风险分析、GitHub Issue 拆分、PR 执行计划、测试策略和静态 dashboard。
