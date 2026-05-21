# CSV 翻译任务指令

## 任务描述
将游戏 "Lustful Spirit Hunt" 的 CSV 文件从英文翻译为中文。

## 输入文件
- 术语库：`glossary.py`（`ALL_GLOSSARY` 字典，唯一真相源）
- CSV 文件：`dialogs.csv`, `ghostpedia.csv`, `jankengame.csv`, `journaltext.csv`, `mainmenu.csv`, `otherstrings.csv`, `translations.csv`, `tutorialtv.csv`, `videotubetext.csv`

## 输出格式
- 新文件命名：`{原名}_zh.csv`（如 `dialogs_zh.csv`）
- 保留原始 CSV 结构（ID、Others、Japanese 列不变）
- 仅翻译 English 列的内容

## 翻译规则

### 术语优先
- `glossary.py` 中 `ALL_GLOSSARY` 的词必须使用对应中文翻译
- 鬼魂类型（温蒂、暴灵、河童妖...）
- 角色名（太一、月子、拓、纯纱...）
- 地点名（山奈市、常春大学...）
- 工具名（摄像机、温度计、紫外线手电...）

### Token 保护（不可翻译）
- `@数字` 标记（如 `@0`, `@1-name`）
- `[REPLY]` 回复标记
- `{变量名}` 占位符（如 `{ghostName}`, `{value}`）
- `<标签>` 格式标记（如 `<color>`, `</color>`）
- 换行符 `\n`

### 翻译风格
- 角色对话：保持原文语气（醉酒含糊、恐惧颤抖、撒娇发嗲等）
- 成人内容：参考术语库标准译法，自然不生硬
- UI 文本：简洁准确
- 日式风格：地名、建筑名保持日式化

### 格式要求
- CSV 编码：UTF-8
- 行终止符：`\n`
- 引号处理：与原文件一致

## 执行步骤
1. 读取 `glossary.py` 获取 `ALL_GLOSSARY`
2. 读取分配的 CSV 文件
3. 逐行翻译 English 列
4. 保护 token 不被翻译
5. 写入新文件

### 术语同步规则
- `glossary.py`（`ALL_GLOSSARY` 字典）是唯一术语真相源
- 所有术语修改只改 `glossary.py`，改完后必须同步更新 `game-translation-design.md` 对应表格
- 同步方向：glossary.py → game-translation-design.md（单向）
- `game-translation-design.md` 为只读参考，不可直接编辑术语表格
