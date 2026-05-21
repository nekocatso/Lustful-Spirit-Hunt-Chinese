# 游戏翻译术语表设计文档

> **注意**：此文件的术语表格由 `glossary.py` 自动生成。修改术语请编辑 `glossary.py`，改完后同步此文件。

**项目**：成人向恐怖游戏本地化（简体中文）
**设计目标**：建立完整的中文术语表，统一 9 个 CSV 文件中的所有专有名词翻译

---

## 设计原则

1. **日文名基准**：角色名以日文名（Others 列）为基础翻译中文名
2. **恐鬼症专业感保留**：证据工具、证据类型保持恐鬼症标准术语风格
3. **驱鬼工具色情化**：以"阴"字为核心构建色情+灵异双关体系
4. **日式恐怖美学**：鬼魂名采用日式妖怪/灵异命名风格
5. **变体识别**：每个角色的所有名称变体（英文名/日文名/昵称/敬称/全名）统一映射到同一个中文名

---

## 一、鬼魂类型（26+1 种）— 日式恐怖美学

| 编号 | 原名 | 中文名 | 说明 |
|------|------|--------|------|
| 0 | Wendy | 温蒂 | 首个鬼魂，保留音译 |
| 1 | Powerghost | 暴灵 | Poltergeist 风格的暴烈灵体 |
| 2 | Kupper | 河童妖 | Kappa 传说的河童妖怪 |
| 3 | Shy | 羞影 | Shade 的影子 + 羞怯感 |
| 4 | Countlanak | 哭啼女 | Kuntilanak 印尼女鬼传说 |
| 5 | Bloody Mariam | 血殇玛丽安 | 血腥 + 悲伤的玛丽安 |
| 6 | Bansheep | 哀嚎妖 | Banshee 的哀嚎女妖 |
| 7 | Weseen | 冤魂 | Gwisin 韩国冤魂概念 |
| 8 | Tall Lady | 八尺夫人 | Hachishakusama 直译 |
| 9 | Willy Wisp | 鬼火 | Onibi 日式鬼火 |
| 10 | Conjurer | 咒唤师 | 召唤系灵媒 |
| 11 | You-Rei? | 幽灵姬 | 日式幽灵 + 姬 |
| 12 | Thundergirl | 雷女 | Rai-onna 雷之女 |
| 13 | Suck-ass-bee | 吸淫蜂 | Succubus 淫魔 + 蜂的双关 |
| 14 | Photogenic | 映魅 | 拍照相关的魅影 |
| 15 | Serpent-End | 濡女 | Nure-onna 日式濡女 |
| 16 | Cloaked Menace | 赤覆面 | Aka-manto 赤覆面直译 |
| 17 | Sex Priestess | 淫祭女 | 祭祀 + 淫的组合 |
| 18 | Tick-talk / Tick-take | 追音鬼 | Teke-teke 追跑的音鬼 |
| 19 | Oh-baker | 大化妖 | Obake 变身妖怪 |
| 20 | Darkness | 暗影 | 保持恐怖感 |
| 21 | Manifest | 显形 | 现形的灵体 |
| 22 | Water Girl | 水灵女 | 水之灵体 |
| 23 | Weeping Doll | 泣偶 | 哭泣的灵偶 |
| 24 | Doppleganger | 二重身 | 日式直接借用 |
| 25 | Others | 其他 | 泛指 |
| 99 | Spirit | 游魂 | 泛指灵体 |

---

## 二、角色人名（日文名基准 + 全变体映射）

### 核心规则

- 中文名以日文名（Others 列）为基准
- 所有变体（英文名/昵称/敬称/全名）统一映射到同一个中文名
- 翻译脚本 `SPECIAL_CELL_MAP` 需覆盖所有变体

### 完整映射表

#### 主要角色

| 中文名 | 英文名 | 日文名 | 其他变体 | 身份 |
|--------|--------|--------|---------|------|
| 太一 | Ted | Taichi | Mr. Ted, Mr. Shiratori, MR Protagonist | 主角 |
| 月子 | Luna | Tsukiko | — | 助手 |
| 拓 | Tess / Michelle | Misae / Misai / Tatsuka | — | 増夫的亲戚 |
| 纯纱 | Judy | Junsa | Mrs. Shepherd, Mrs. Sakurai, Slutty Elf | 教师 |
| 葵 | Angela | Aoi | Ms. Angela, Ms. Aoi | 猜拳女孩 |
| 静香 | Suzy | Shizuka | Horny Cop | 警察 |
| 珠子 | Jennifer | Juko | Milk Factory, 珠子阿姨 | 家庭主妇 |
| 桃子 | Melanie | Momoko | Cumslut, 桃子阿姨 | 厨师/送餐 |
| 真理 | Martha | Mari | — | 角色 |
| 鸠 | Harper | Hanako | — | 角色 |
| 薫 | Rose | Rose | Big Boob Anko | 服务员 |
| 雅典娜 | Athena | Athena | Jealous Bitch | 店员/漫画家 |
| 増夫 | Mason | Masuo | Mr. Raven, Mr. Karasuyama, Mr. Karausyama, Raven | 幽灵猎人 |
| 留美亚 | Rebecca | Rumia | — | 増夫的妻子 |
| 香织 | Wendy | Kaori | — | 鬼妻 |
| 澪子 | Sabrina | Sawako | Ms. Sabrina | 月子的姐姐 |
| 凉子 | Regina | Ryoko | — | 老板 |

#### 招募角色

| 中文名 | 英文名 | 日文名 | 其他变体 | 能力 |
|--------|--------|--------|---------|------|
| 名都子 | Necola | Nadeko | Lady Necola, Lady Nadeko | 温度计升级 |
| 奈美 | Nina | Nabiki | — | 狐妖，KTE 治疗 |
| 泉 | Irene | Izumi | — | 恶魔猎人，救援 |
| 美佐枝 | Michelle | Misae | Misai | 奖金 |
| 蓮 | Len | Len / Liz | — | 双倍精力 |
| 朋 | Tori | Tomori | — | 第二钱包 |
| 瑠美 | Rachel | Ryomi | — | 性爱治疗 |

#### 配角

| 中文名 | 英文名 | 日文名 | 其他变体 | 身份 |
|--------|--------|--------|---------|------|
| 博美 | Harleen | Hinata | Mrs. Fisher, Mrs. Fuyutsuki, Harleen Fisher | Fisher 家 |
| 朋 | Taylor | Tomo | — | 角色 |
| 裕美 | Hailey | Himawari | — | 角色 |
| 真澄 | Masie | Masumi | short Masumi | 角色 |
| 瑞希 | Anya | Anko | Anya Sawyer, Anko Sato, Big Boob Anko | 角色 |
| 一 | Harold | Hajime | — | 角色 |
| 美琴 | Gina Wayne | Mrs. Yamada | Mrs. Wayne, Loretta Wayne | Wayne 家 |
| 堇 | Sylvia | Sumire | Sylvia Cole | 角色 |
| 由美子 | Ursula | Yumiko | Dr. Ursula | 角色 |
| 真理 | Faith | Mariko | — | 角色 |
| 美月 | Megan | Megumi | — | 角色 |
| 香 | Kent / Kevin | Kunio | — | 角色 |
| 霞 | Katherine / Kristina | Kasumi | Kate Kramer, Kasumi Kobayashi | 助手 |
| 梓 | Alex | Azusa | — | 角色 |
| 千秋 | Carmen | Chiaki | — | 角色 |
| 芽衣 | Maya | Mei | Aunt Maya, Aunt Mei | 角色 |
| 大辅 | Derek | Daisuke | — | 角色 |
| 純美 | Jessica | Junmi | — | 大辅的妻子 |
| 紫苑 | Aster | Shion | — | 角色 |
| 彩音 | Alice | Akane | — | 角色 |
| 伊奈 | Isabella | Ine | — | 阿姨 |
| 花 | Hannah | Hana | Hannah of the Toilet, Hana-chan of the Toilet | 厕所怪谈 |
| 光 | Donut | Deko | — | 送餐女孩 |
| 桜 | Ginger | Sakura | — | 送餐女孩 |
| 香理 | Kara | Kana | Ms. Kana | 餐厅老板 |

#### 送餐女孩（同名不变）

| 中文名 | 原名 | 说明 |
|--------|------|------|
| 蜜儿 | Honey | 同名 |
| 巧可 | Choco | 同名 |
| 小杯 | Buttercup | 同名 |

#### 其他角色（仅出现在 Others 列）

| 中文名 | Others 名 | 备注 |
|--------|----------|------|
| 幸二 | Kouji | 仅 Others |
| 千紗 | Chisa | 仅 Others |
| 美咲 | Misaki | 仅 Others |
| 丽华 | Reika | 仅 Others |
| 真奈美 | Manami | 仅 Others |
| 光里 | Mitsuri | 仅 Others |
| 青音 | Aone | 仅 Others |
| 律 | Ristu | 仅 Others |
| 蓝宝石 | Sapphire | 仅 Others |
| 美沙 | Misa | 仅 Others |
| 浦井 | Urai | 仅 Others |
| 满都 | Mandus | 仅 Others |
| 智 | Satoshi | 仅 Others |
| 彩 | Aya | CSV 补充 |
| 猛 | Takeru | CSV 补充 |
| 惠奈 | Ena | CSV 补充 |
| 千留 | Chiru | CSV 补充 |
| 音惠 | Otoe | CSV 补充 |
| 白郎 | Hakuro | CSV 补充 |
| 城一 | Joichi | CSV 补充 |
| 五月 | Satsuki | CSV 补充 |
| 信太 | Nobita | CSV 补充 |
| 诚也 | Seiya | CSV 补充 |
| 久美 | Kumi | CSV 补充 |
| 琪琳 | Chirin | CSV 补充 |
| 花火 | Hanabi | CSV 补充 |

#### NPC（无变体或仅敬称变体）

| 中文名 | 英文名 | 日文名 | 其他变体 |
|--------|--------|--------|---------|
| 恋 | Lady Blossom | Lady Momo | — |
| 美露莎 | Lady Merusa | Lady Merusa | 同名 |
| 神秘女 | Lady Mystery | Lady Mystery | 同名 |
| 淫欲女 | Lady Lust | Lady Lust | 仅 Others |
| 亚米莉亚 | Lady Amelia | Lady Amelia | 仅 Others |
| 罗宾先生 | Mr. Robin | Mr. Shiratori | 区别于主角 |
| 増夫之妻 | Mrs. Raven | Mrs. Karasuyama | — |
| 松田先生 | Mr. Matsuda | Mr. Matsuda | 同名 |
| 基思先生 | Mr. Keith | Mr. Kanzaki | — |
| 汤姆森博士 | Dr. Thomson | Dr. Takemoto | — |
| 布莱特博士 | Dr. Blight | Dr. Blight | 同名 |
| 韦恩先生 | Mr. Wayne | Mr. Wayne | — |
| 石田夫人 | — | Mrs. Ishida | 仅 Others |
| 克莱默夫人 | Mrs. Kramer | Mrs. Kobayashi | — |
| 北本夫人 | — | Mrs. Kitamoto | 仅 Others |
| 松冢女士 | — | Ms. Matsuzaka | 仅 Others |
| 陌生人 | Stranger | Stranger | 同名 |

#### 鬼魂真名

| 中文名 | 英文名 | 说明 |
|--------|--------|------|
| 温蒂·凯楚姆 | Wendy Ketchum | 鬼魂 0 |
| 菲欧娜·福克斯 | Fiona Fox | 鬼魂相关 |
| 阿曼达·韦伯 | Amanda Webb | 鬼魂相关 |
| 薇拉·康纳 | Vera Connor | 鬼魂相关 |
| 吸血鬼之妻 | Vampire Wife | 鬼魂相关 |
| 玛丽安·希尔福德 | Mariam Hillford | 鬼魂 5 |
| 歌灵 | Singing Ghost | 鬼魂相关 |
| 索菲·哈珀 | Sophie Harper | 鬼魂相关 |
| 达莉亚·希尔福德 | Dahlia Hillford | 鬼魂相关 |
| 辛德瑞拉 | Cindrella | 鬼魂相关 |
| 夺魂者 | Soul Snatchers | 鬼魂相关 |
| 阿祖尔桑德拉 | Azulthundra | 鬼魂相关 |
| 妮可·史蒂文斯 | Nicole Stevens | 鬼魂相关 |
| 毒蛇 | Viper | 鬼魂相关 |
| 艾普莉尔·迈尔斯 | April Miles | 鬼魂相关 |
| 狐妖 | Fox Demons | 鬼魂相关 |

---

## 三、证据工具（7 件）— 恐鬼症专业风格

| 原名 | 中文名 | 说明 |
|------|--------|------|
| Video Camera | 摄像机 | 恐鬼症标准术语 |
| Thermometer | 温度计 | 恐鬼症标准术语 |
| UV Torch / UV Flashlight | 紫外线手电 | 恐鬼症标准术语 |
| Laser Projector / Laser Grid Projector | 激光投射器 | 恐鬼症标准术语 |
| EMF Reader / EMF Sensor | EMF 读数器 | 恐鬼症标准术语 |
| Notebook | 灵异笔记 | 恐鬼症灵异记录本 |
| Audio Box / Ghost Box | 通灵盒 | 恐鬼症标准术语（Spirit Box） |

---

## 四、驱鬼工具（6 件）— 色情化命名

| 原名 | 中文名 | 说明 |
|------|--------|------|
| Cursed Dagger | 破阴刃 | 驱鬼之刃，破阴双关 |
| Cum Salt | 射精盐 | 直译保留色情原意 |
| Dark Mirror | 照阴镜 | 驱鬼镜，照见阴物 |
| Special Rope | 缚阴索 | 绑缚灵体的绳索 |
| Cum Water | 淫水 | 直译保留 |
| Candle | 蜡精烛 | 蜡烛 + 精的双关 |

---

## 五、其他工具/消耗品 — 色情化命名

| 原名 | 中文名 | 说明 |
|------|--------|------|
| Flour | 阴尘粉 | 驱鬼用的灵异粉尘 |
| Incense Stick | 迷魂香 | 迷魂 + 香 |
| Motion Camera | 动态感应摄像头 | 恐鬼症专业风格 |
| Honey Burger | 蜜汁汉堡 | 蜜 + 汁的双关 |
| Fear Pills | 定魂丸 | 镇定恐惧的药丸 |
| Energy Can / Energy Drink | 精力罐 | 精力（精液双关） |
| Power Breaker | 电闸 | — |
| CCTV Computer | 监控电脑 | — |
| Sink | 水槽 | — |
| Lunch Box / Bento | 便当 | 日式便当 |
| Honey Milk | 蜜乳 | 蜜 + 乳的双关 |
| Magic Ring | 魔法戒指 | 游戏核心道具 |
| Earth Ranger | 地球游侠 | 游戏内阵营 |

---

## 六、收集品

| 原名 | 中文名 | 说明 |
|------|--------|------|
| Flash Drive / Pen Drive | U盘 | — |
| Soul Orb | 魂珠 | 灵魂之珠 |
| Ghostpedia Page | 幽灵笔记 | 鬼魂图鉴的散页 |
| Evergreen Master Key | 常春校万能钥匙 | — |
| Old University Master Key | 旧校万能钥匙 | — |
| Masturbator Toy | 飞机杯 | 中文通用成人用品名 |
| Strange Doll | 怪异人偶 | — |
| Used Masturbator | 用过的飞机杯 | 直译 |
| Penis Like Thing | 似屌之物 | 直译 + 色情化 |
| Life Size Doll | 等身人偶 | — |

---

## 七、状态/属性系统

| 原名 | 中文名 | 说明 |
|------|--------|------|
| Health (HP) | 生命值 | — |
| Fear Meter | 惧意条 | 恐惧计量 |
| Stamina | 精力值 | 精力（精液双关） |
| Climax Bar | 高潮条 | 直译保留 |
| Speed Handler | 速度控制器 | — |
| Coins | 金币 | — |
| Night Vision | 夜视 | — |
| Zoom | 缩放 | — |

---

## 八、疾病系统

| 原名 | 中文名 | 说明 |
|------|--------|------|
| Madness | 疯癫 | 精神失常 |
| Fatigue | 虚脱 | 体力耗尽 |
| GTD | 阴病 | Ghostly Transmitted Disease 的缩写 |
---

## 九、证据类型（7 种）— 恐鬼症风格

| 原名 | 中文名 | 说明 |
|------|--------|------|
| UV Prints | 紫外线指纹 | 恐鬼症标准术语 |
| Laser Apparition | 激光显影 | 恐鬼症标准术语 |
| Ghost Orbs | 灵异光球 | 恐鬼症标准术语 |
| Writing | 灵异笔迹 | 恐鬼症标准术语 |
| Freezing Temperature | 寒温 | 恐鬼症标准术语 |
| Audio Response | 通灵回音 | 恐鬼症标准术语 |
| EMF Lvl. 4-5 | EMF 4-5级 | 恐鬼症标准术语 |

---

## 十、游戏机制术语

| 原名 | 中文名 |
|------|--------|
| Ghost is Hunting | 鬼魂猎杀中 |
| Hunting State | 猎杀状态 |
| Wandering State | 游荡状态 |
| Haunt Room | 鬼域 |
| Ghost Room | 鬼房 |
| Contract | 契约 |
| Case # | 案件编号 |
| Ghost Identification | 鬼魂鉴定 |
| Ghost Banishment | 鬼魂驱逐 |
| Ghostpedia | 幽灵笔记 |
| K.T.E. | K.T.E. |
| Hunt | 狩猎 |
| Capture | 捕获 |
| Ghost is repelled | 鬼魂已击退 |
| Ghost is satisfied | 鬼魂已满足 |
| Ghost is down | 鬼魂已倒下 |
| Ghost has escaped | 鬼魂已逃脱 |
| Infinite Stamina | 无限精力 |
| Faster Climax | 加速高潮 |
| Ghost is Angry | 鬼魂暴怒 |

---

## 十一、城市/地区名（日式地名化）

| 原名 | 中文名 | 说明 |
|------|--------|------|
| Nature Hill City | 山奈市 | Yamanama 的音译化 |
| Cherry Blossom City / Sakura City | 樱花市 | Sakura 的意译 |
| River Village / Kawa Village | 河之村 | Kawa 的意译 |
| Sunflower City / Himawari City | 向日葵市 | Himawari 的意译 |
| Red Pine Village / Akamatsu Village | 赤松村 | Akamatsu 的意译 |
| Moondew Valley / Getsuro Valley | 月露谷 | Getsuro 的意译 |
| Old Wood City | 古森市 | 意译 |
| Sweetlake City | 甜湖市 | 意译 |
| Assex Village | 尻之村 | Oshiri 的意译（保留性暗示） |
| Widehill Prefecture | 广丘县 | 日式行政区划 |

---

## 十二、建筑/场所名

| 原名 | 中文名 | 说明 |
|------|--------|------|
| Hillford Asylum | 平冢病院 | Hirakawa 的音译化 |
| Evergreen University | 常春大学 | 意译 |
| Sunrays Apartments | 朝日庄 | 日式公寓命名 |
| Butt Naked Hotel (BN Hotel) | 露出旅馆 | 直译 + 色情化 |
| Erotic World | 淫乐世界 | 直译色情化 |
| Ghost Bangers Base | 鬼狩本部 | 鬼猎人基地 |
| Star Plum Restaurant | 星梅轩 | 日式餐厅名 |
| Hillford Cinema | 平冢映画馆 | 日式影院名 |
| Hot Girl Club | 美人俱乐部 | 意译 |
| Karasuyama Household | 乌山家 | 増夫家 |
| Sakurai Household | 樱井家 | 纯纱家 |

---

## 十三、UI/系统术语

| 原名 | 中文名 |
|------|--------|
| Main Menu | 主菜单 |
| Start Game | 开始游戏 |
| Options | 选项 |
| Exit Game | 退出游戏 |
| Key Configuration | 按键设置 |
| Journal | 灵异日志 |
| Collections | 收藏 |
| Conclusion | 结论 |
| End Investigation | 结束调查 |
| Contract Board | 契约板 |
| My Phone | 手机 |
| VideoTube | 影管 |
| File Explorer | 文件管理 |
| Web Browser | 网页浏览器 |
| TV Channels | 电视频道 |
| Ghost Data | 鬼魂数据 |
| Janken Game | 猜拳游戏 |
| Possessed Items | 附魔物品 |
| Haunted Items | 灵异物品 |
| Travel Passes | 通行令 |
| Lifetime Pass | 终身通行证 |

---

## 十四、VideoTube 频道名

| 原名 | 中文名 |
|------|--------|
| GhostEnthusiast | 鬼魂狂热者 |
| LunaTheHunter | 月子狩猎频道 |
| ParanormalCouple | 灵异情侣 |
| TheChosenOne | 天选之人 |
| GhostCatalog | 鬼魂目录 |
| SemenDoctor | 精液博士 |
| RingMan | 戒指男 |
| Sunflower City NEWS | 向日葵市新闻 |
| MilkingMommy | 榨乳妈咪 |
| RiceballGames | 饭团游戏 |
| KennedyStudios | 肯尼迪工作室 |
| HaileyMovieStudios | 裕美映画 |
| ComicEnthusiastic | 漫画狂热 |
| TedRayner | 太一频道 |
| NapajNEWS | 日本新闻 |

---

## 十五、TV 节目名

| 原名 | 中文名 |
|------|--------|
| Kara Loft | 香织物语 |
| 50 Days Anal Sex | 后穴五十日 |
| No Extraction | 禁止拔出 |
| Spy Files | 间谍档案 |
| Discreet Clappers | 秘密拍手党 |

---

## 十六、服装/外观

| 原名 | 中文名 |
|------|--------|
| College Uniform (Blouse, Skirt, Socks) | 校服（上衣、裙子、袜子） |
| Lust Leotard & Gloves | 淫欲紧身衣与手套 |
| Lust Horns | 淫欲犄角 |
| Lust Boots & Tail | 淫欲靴与尾巴 |
| Maid Uniform | 女仆装 |
| Sexy Cloths | 性感装 |
| Ragged Clothes | 破烂衣 |
| Ghost T-Shirt | 鬼魂T恤 |
| Red Kats Blouse/Skirt/Socks | 红猫帮上衣/裙子/袜子 |
| Necola's Outfit | 名都子套装 |
| Ringman Outfit | 戒指男套装 |
| Earth Ranger Uniform | 地球游侠制服 |
| Hot Girlfriend Cloths | 辣妹装 |

---

## 十七、应用/功能名

| 原名 | 中文名 |
|------|--------|
| Ghost Data | 百鬼数据 |
| Sex Video Maker | 色情录像机 |
| Janken Game | 猜拳游戏 |

---

## 十八、成人内容术语

### 体位名（VideoTube 分类）

| 原名 | 中文名 |
|------|--------|
| Cowgirl Fly | 飞骑乘 |
| Prone Anal | 俯卧后入 |
| Thighjob | 腿交 |
| Standing | 站立式 |
| Triangle | 三角式 |
| Stand Handjob | 站立撸管 |
| Doggy Anal | 后入肛交 |
| Doggystyle | 后入式 |
| Stand Cowgirl | 站立骑乘 |
| Stand Anal | 站立后入 |
| Stand Doggy | 站立后入 |
| Cowgirl | 骑乘位 |
| Blowjob | 口交 |
| Stand Boobjob | 站立乳交 |
| Front Kneel | 正面跪交 |
| 69 | 69式 |
| R Cowgirl | 反骑乘 |
| Double Pen | 双插 |
| Boobjob | 乳交 |
| Fly Blowjob | 飞行口交 |
| Milking | 榨乳 |
| CG Anal | 骑乘肛交 |
| Tail Job | 尾交 |
| Leg Hold | 抱腿式 |

### 动画类型

| 原名 | 中文名 |
|------|--------|
| Regular | 普通 |
| Uniform | 制服 |
| Ragged | 破衣 |
| Lust | 淫欲 |
| Turtle | 龟甲缚 |
| Tshirt | T恤 |
| Naked | 裸体 |
| Naked Anal | 裸体肛交 |
| Clothed | 着衣 |
| Fox Demon | 狐妖 |
| Spooning | 侧入式 |
| Missionary | 传教士 |
| Pronebone | 俯卧式 |
| Doctor | 医生 |

### 解锁动画名

| 原名 | 中文名 |
|------|--------|
| Melanie X Mason | 桃子 × 増夫 |
| Mason X Saleswoman | 増夫 × 女销售 |
| Ruth X Mason | 露丝 × 増夫 |
| Abigail Double Penetration | 阿比盖尔双插 |
| Luna X Mason | 月子 × 増夫 |
| Mason X Jennifer | 増夫 × 珠子 |
| Mason X Tess | 増夫 × 拓 |
| Sex Orgy | 性爱狂欢 |
| Tori X Leon | 朋 × 利昂 |
| Anya X Harold | 瑞希 × 一 |

---

## 十九、猜拳游戏术语

| 原名 | 中文名 |
|------|--------|
| Rock, Paper, Scissors | 石头剪刀布 |
| Janken | 猜拳 |
| Butt Sex Janken | 后穴猜拳秀 |
| Janken Queen | 猜拳女王 |
| Big Boob Anko | 巨乳杏子 |
| Slutty Elf | 淫荡精灵 |
| Jealous Bitch | 嫉妒婊 |
| Horny Cop | 发情女警 |
| Milk Factory | 产奶工厂 |
| Cumslut | 精液母狗 |

---

## 二十、公司/工作室名

| 原名 | 中文名 |
|------|--------|
| Tomb Explorer Co. | 探墓公司 |
| Ruth-Mason Studios | 露丝-増夫工作室 |
| Riceball Games | 饭团游戏 |

---
