# Fork / Pull Request 流程测试

这是临时的 GitHub 提交流程样例，不是论文代码，不申请论文归档。
目录中的 WorkflowTest 和 TEST 是测试标记，不代表真实作者或期刊。

- 用途：验证 Fork、独立分支、上传单个目录、创建 Pull Request。
- 操作账号：durantjialiang。
- 论文全名、作者、期刊、论文链接：不适用，这是流程测试。
- 环境：Python 3.9 或更高版本，仅使用标准库。
- 数据、模型、检查点：不需要；输入为命令行中的示例整数。
- 正式论文复现、训练与评估：不适用。

## 运行

在本目录执行：

```bash
python3 demo.py 1 2 3
```

预期输出：

```json
{"numbers": [1, 2, 3], "sum": 6}
```

也可在仓库根目录运行：

```bash
python3 WorkflowTest_ForkPRSmoke_2026_TEST/demo.py 1 2 3
```

此测试 PR 请勿合并。
