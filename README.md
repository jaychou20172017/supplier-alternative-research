# 备选原厂开发 Skill

将整个 `supplier-alternative-research` 文件夹复制到目标 Agent 的技能目录；也可以解压同名 zip，确保解压后得到 `supplier-alternative-research/SKILL.md` 和完整的 `references/` 目录。不要只复制 `SKILL.md`，因为它引用了参考文件。文件夹内使用相对路径，没有绑定某台电脑的路径、专有 MCP 或 API 密钥。

从 GitHub 获取时，可克隆仓库，或在仓库页面下载 Code ZIP；将得到的文件夹改名为 `supplier-alternative-research` 后放入目标 Agent 的技能目录。保持 `SKILL.md`、`references/` 和 `examples/` 的相对位置。

Codex 的常见用户级位置是 `~/.codex/skills/supplier-alternative-research/`；其他支持 `SKILL.md` 的 Agent，请放到该 Agent 文档指定的技能目录。启用前确认 Agent 能读取用户上传资料、访问网页，并具备生成和保存 `.docx` 的能力。默认交付 Word 研究报告，对比表嵌入文档；CSV 可作为辅助文件。不同 Agent 的自动发现和调用方式可能不同，也可在任务中明确要求使用 `supplier-alternative-research`。

调用示例：

> 使用 supplier-alternative-research 分析我上传的规格书，调查现有原厂，寻找 5–8 家国内外备选原厂及型号，并给出技术与供应商对比、替代难度排序和细分领域概况。

企业信息调查可参考当前 Agent 可访问的天眼查、企查查等平台，或用户提供的页面截图、导出资料。报告会注明平台、对应企业主体、查询日期和数据口径，并优先用原始登记或认证来源核验关键结论。此 Skill 不附带第三方数据库账号或权限，也不会自动联系供应商。

在新电脑上首次使用时，按 [跨 Agent 验收](references/acceptance-check.md)先运行 [模拟分类练习](examples/acceptance-case.md)，再用一份非保密真实规格书试跑。真实试跑需检查原厂链接、中文 `.docx` 的图表，以及 Word、`关键参数证据.csv` 和可选对比 CSV 的候选数、排序、关键数值是否一致。模拟练习是虚构数据，不是实际供应商研究结论；无需复制本项目的具体物料报告或本机脚本。
