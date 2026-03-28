# 越南语游戏本地化参考手册

## 节1：越南语游戏本地化核心特征

### 1.1 六声调符号——绝对不能省略

越南语共有6个声调，声调符号是单词含义的核心组成部分，绝对不可省略或替代：

| 声调名称 | 符号示例 | 说明 |
|----------|----------|------|
| ngang（平声） | ma | 无符号，读平调 |
| huyền（玄声） | mà | 声调符号：` ̀`，低降调 |
| sắc（锐声） | má | 声调符号：` ́`，高升调 |
| hỏi（问声） | mả | 声调符号：` ̉`，低升调 |
| ngã（折声） | mã | 声调符号：` ̃`，高折调 |
| nặng（重声） | mạ | 声调符号：` ̣`，低降重 |

**⚠️ 同字不同调，意思天差地别：**
- **ma** = 鬼/幽灵
- **má** = 妈妈（南方口语）
- **mà** = 但是（转折连词）
- **mả** = 坟墓
- **mã** = 代码/马（文言）
- **mạ** = 水稻秧苗

> 游戏本地化如果漏掉声调，轻则不专业，重则词义错误，造成玩家困惑甚至冒犯。例如把"mua vũ khí"（购买武器）写成"mua vu khi"完全无法辨认。

---

### 1.2 南北方言差异

| 方面 | 北方（Hà Nội 标准） | 南方（TP.HCM 口语） | 建议用法 |
|------|---------------------|---------------------|----------|
| 标准地位 | 官方普通话标准 | 口语化，亲近感强 | 游戏UI/系统文本用北方标准 |
| 部分词汇差异 | bát（碗）/ thìa（勺） | chén（碗）/ muỗng（勺） | 注意避免混用 |
| 人称代词 | tôi/mình（我） | tui/mình（我，更口语） | 对话/NPC可用南方增加亲近感 |
| 疑问词 | không（否定/疑问） | hông（口语否定） | 非正式对话可用 |
| 部分词汇 | ăn cơm（吃饭） | ăn cơm（相同） | 大部分词汇一致 |
| 感叹语气 | ôi trời（天啊） | ôi trời ơi / trời ơi（更口语） | 活动文案可用南方 |

**推荐策略：**
- 系统提示、UI按钮、错误信息 → **北方标准**
- NPC对话、活动文案、社区内容 → **可适当融入南方口语**，增加亲近感
- 商务邮件/合同 → **严格北方标准书面语**

---

### 1.3 英越混用（Việt-English Code-switching）

越南游戏玩家习惯直接使用以下英文词汇，**无需翻译**：

| 类别 | 直接使用的词 |
|------|-------------|
| 游戏机制 | skill, buff, nerf, boss, lag, bug, hack, farm, carry, feed, tank, support, damage, heal |
| 元游戏 | meta, tier list, build, combo, cooldown (CD), ultimate (ult) |
| 社交 | GG, AFK, noob, pro, toxic, troll |
| 平台 | app, store, update, download, login, account |
| 货币 | token, gem, crystal, diamond, coin |

> 强行翻译这些词会显得生硬不自然。例如 "buff" 翻成"增益效果"反而让越南玩家困惑。

---

### 1.4 人称代词选择

| 场景 | 推荐人称 | 说明 |
|------|----------|------|
| 游戏内UI/通知 | **bạn**（你，友好中性） | 最常用，既不失礼又亲切 |
| NPC对长者/主公 | **ngài**（阁下/您） | 表示尊敬 |
| NPC对英雄 | **bạn** 或 **chiến binh**（勇士） | 角色扮演感强 |
| 商务邮件 | **Quý vị**（贵方/您）或对方头衔 | 正式商务场合 |
| 玩家社区非正式 | **mình**（我/自己，亲切） | 帖子/SNS偶尔用 |
| ⚠️ 避免 | **mày/tao**（你/我，粗俗） | 仅限极非正式/玩笑场合，游戏内不用 |

---

### 1.5 越南手游市场特点

- **SEA核心市场**：越南是东南亚最重要的手游市场之一，月活玩家超过2000万
- **手游为主**：90%以上玩家通过手机游戏，Android占比更高
- **热门品类**：MOBA（Liên Quân Mobile极受欢迎）、RPG、Battle Royale、SLG
- **支付偏好**：便利店充值卡、电子钱包（MoMo、ZaloPay、VNPay）、银行转账
- **社区活跃**：Facebook Group、TikTok、YouTube游戏直播非常活跃
- **价格敏感**：小额充值包（5,000–50,000 VND）转化率高

---

## 节2：游戏UI/系统提示

### 2.1 核心按钮（30个）

| 中文 | 越南语 | 备注 |
|------|--------|------|
| 确认 | Xác nhận | 通用确认 |
| 取消 | Hủy | 取消操作 |
| 返回 | Quay lại | 返回上一页 |
| 开始 | Bắt đầu | 开始游戏/关卡 |
| 继续 | Tiếp tục | 继续进行 |
| 退出 | Thoát | 退出游戏/界面 |
| 重试 | Thử lại | 重新尝试 |
| 领取 | Nhận | 领取奖励 |
| 购买 | Mua | 购买道具 |
| 升级 | Nâng cấp | 升级装备/角色 |
| 制造/合成 | Chế tạo | 合成道具 |
| 卸下 | Tháo ra | 卸下装备 |
| 装备 | Trang bị | 穿戴装备 |
| 卸装备 | Bỏ trang bị | 脱下装备 |
| 跳过 | Bỏ qua | 跳过剧情/动画 |
| 分享 | Chia sẻ | 分享至社交 |
| 设置 | Cài đặt | 游戏设置 |
| 任务 | Nhiệm vụ | 任务系统 |
| 背包 | Túi đồ | 物品栏 |
| 地图 | Bản đồ | 游戏地图 |
| 商店 | Cửa hàng | 商城/道具商店 |
| 排行榜 | Xếp hạng | 排名榜单 |
| 公会/帮派 | Hội / Bang | 公会系统 |
| 活动 | Sự kiện | 限时活动 |
| 战斗 | Chiến đấu | 进入战斗 |
| 胜利 | Chiến thắng | 战斗胜利 |
| 失败 | Thất bại | 战斗失败 |
| 暂停 | Tạm dừng | 暂停游戏 |
| 继续游戏 | Tiếp tục chơi | 从暂停恢复 |
| 结算 | Kết toán | 战斗/关卡结算 |

---

### 2.2 状态消息（15条）

| 场景 | 越南语文本 |
|------|-----------|
| 加载中 | Đang tải... |
| 连接中 | Đang kết nối... |
| 正在保存 | Đang lưu... |
| 保存成功 | Lưu thành công! |
| 网络错误 | Lỗi kết nối mạng. Vui lòng thử lại. |
| 服务器维护中 | Máy chủ đang bảo trì. Vui lòng quay lại sau. |
| 版本过旧 | Phiên bản cũ. Vui lòng cập nhật game. |
| 背包已满 | Túi đồ đã đầy! |
| 金币不足 | Không đủ vàng! |
| 钻石不足 | Không đủ kim cương! |
| 体力不足 | Không đủ thể lực! |
| 道具获取成功 | Nhận vật phẩm thành công! |
| 登录成功 | Đăng nhập thành công! |
| 已离线 | Đã mất kết nối. |
| 每日奖励已领取 | Đã nhận thưởng hằng ngày! |

---

### 2.3 战斗反馈（10条）

| 场景 | 越南语文本 |
|------|-----------|
| 暴击 | Chí mạng! / Crit! |
| 连击 | Combo x[N]! |
| 完美 | Hoàn hảo! |
| 闪避 | Né tránh! / Dodge! |
| 格挡 | Chặn đòn! |
| 技能释放 | Kỹ năng kích hoạt! |
| 击杀 | Tiêu diệt! |
| 被击杀 | Bị tiêu diệt! |
| 助攻 | Hỗ trợ! / Assist! |
| 连杀 | Chuỗi tiêu diệt! / [N] kills! |

---

## 节3：活动运营文案

### 3.1 越南风格活动标题

| 活动类型 | 越南语标题示例 |
|----------|---------------|
| 限时活动 | 🎉 SỰ KIỆN GIỚI HẠN – Đừng Bỏ Lỡ! |
| 节日活动 | 🌙 TẾT NGUYÊN ĐÁN – Quà Khủng Đón Xuân! |
| 新英雄上线 | ⚔️ TƯỚNG MỚI ĐÃ ĐẾN – Sẵn Sàng Chinh Chiến! |
| 充值活动 | 💎 NẠP TIỀN NHẬN QUÀ – Ưu Đãi Đặc Biệt! |
| 排名赛 | 🏆 MÙA GIẢI MỚI – Tranh Tài Cùng Top Server! |
| 签到活动 | 📅 ĐIỂM DANH 7 NGÀY – Nhận Ngay Vật Phẩm Hiếm! |
| 联盟战 | 🔥 LIÊN MINH ĐẠI CHIẾN – Bảo Vệ Lãnh Thổ! |

---

### 3.2 营销语句（10句，活泼风格）

1. 🎁 **Quà cực khủng đang chờ bạn! Đăng nhập ngay hôm nay!**
   （超豪华礼包等你来！今天就登录！）

2. ⚡ **Sự kiện chỉ còn [X] ngày – Đừng để hối tiếc!**
   （活动仅剩[X]天——不要留遗憾！）

3. 🏆 **Top 1 server sẽ nhận phần thưởng cực phẩm! Bạn có đủ sức không?**
   （服务器第一将获得顶级奖励！你敢挑战吗？）

4. 💎 **Nạp lần đầu TẶNG NGAY x10 lần – Cơ hội có 1 không 2!**
   （首充直送10倍奖励——千载难逢的机会！）

5. 🔥 **Gacha siêu hot – Tỷ lệ SSR tăng 3 lần trong hôm nay thôi!**
   （超热抽卡——仅今天SSR概率提升3倍！）

6. 🌟 **Hội bạn đang chờ bạn! Vào cùng farm quà hội nhé~**
   （你的公会在等你！一起进来刷公会福利吧~）

7. 🎮 **Tướng mới ra mắt – Skin độc quyền chỉ có trong tuần này!**
   （新英雄登场——本周独享专属皮肤！）

8. 🚀 **Mùa mới bắt đầu – Reset rank, cơ hội leo rank lại từ đầu!**
   （新赛季开始——段位重置，重新爬分的机会来了！）

9. 💰 **Hoàn tiền 20% mọi giao dịch nạp trong cuối tuần này!**
   （本周末所有充值交易返还20%！）

10. 🎉 **Cảm ơn [N] triệu người chơi đã đồng hành – Quà tri ân siêu to khổng lồ đang chờ!**
    （感谢[N]百万玩家的支持——超大感恩礼包等你领！）

---

### 3.3 奖励道具描述词汇

| 品质/类型 | 越南语 |
|-----------|--------|
| 传说级 | Huyền Thoại / Legendary |
| 史诗级 | Sử Thi / Epic |
| 稀有 | Hiếm / Rare |
| 普通 | Thường / Common |
| 限定 | Giới Hạn / Limited |
| 永久 | Vĩnh Viễn / Permanent |
| 限时 | Có Thời Hạn / Temporary |
| 独家 | Độc Quyền / Exclusive |
| 超值礼包 | Gói Siêu Giá Trị |
| 每日礼包 | Gói Hằng Ngày |
| 首充礼包 | Gói Nạp Lần Đầu |
| 奖励宝箱 | Hòm Thưởng |
| 幸运宝箱 | Hòm May Mắn |

---

## 节4：剧情/NPC对话

### 4.1 角色语气类型

| 角色类型 | 语气特点 | 越南语风格 |
|----------|----------|-----------|
| **英雄型** | 豪迈、坚定、鼓励 | 短促有力，常用"Chiến binh!"、"Đứng dậy!" |
| **长者/智者型** | 沉稳、智慧、语重心长 | 多用"Này con ơi"、"Hãy lắng nghe..."、文言感 |
| **反派型** | 嘲讽、狂傲、充满威胁感 | "Ngươi dám?"、"Haha, thật ngây thơ!" |
| **萌系** | 活泼、可爱、语尾带感叹 | 多用"~nè!"、"oke bạn ơi~"、"kawaii" |
| **搞笑型** | 接地气、玩梗、方言 | 南方口语、网络流行语、夸张感叹词 |

---

### 4.2 常用台词（10句）

1. **英雄呼唤**：*"Chiến binh, thế giới đang cần bạn! Hãy đứng dậy và chiến đấu!"*
   （勇士，世界需要你！站起来战斗吧！）

2. **长者训诫**：*"Này con, sức mạnh thực sự không đến từ vũ khí, mà từ trái tim."*
   （孩子，真正的力量不来自武器，而来自内心。）

3. **反派嘲讽**：*"Ngươi dám chống lại ta? Thật buồn cười! Hãy chuẩn bị đón nhận thất bại!"*
   （你敢与我为敌？真可笑！准备好迎接失败吧！）

4. **萌系NPC**：*"Ôi bạn ơi~ Hôm nay bạn trông thật ngầu đó nè! 💕"*
   （哇你好帅哦～今天的你看起来超酷的呢！）

5. **任务发布**：*"Bạn có muốn nhận nhiệm vụ đặc biệt từ ta không? Phần thưởng rất hấp dẫn đấy!"*
   （你想接受我的特殊任务吗？奖励可是非常丰厚的哦！）

6. **胜利庆祝**：*"Xuất sắc! Bạn đã chứng minh mình là chiến binh thực sự!"*
   （出色！你已经证明了自己是真正的勇士！）

7. **失败安慰**：*"Đừng nản lòng, bạn ơi. Thất bại là mẹ thành công mà!"*
   （别气馁，朋友。失败是成功之母嘛！）

8. **商人对话**：*"Chào bạn! Hôm nay tôi có hàng hiếm đây, mua đi kẻo hết nhé!"*
   （你好！今天我这里有稀有物品，快来买，卖完就没了！）

9. **反派落败**：*"Không thể nào... Làm sao ngươi có thể đánh bại ta được?!"*
   （不可能……你怎么可能打败我？！）

10. **引导NPC**：*"Nhấn vào nút 'Bắt đầu' để bước vào hành trình của bạn nhé~"*
    （点击"开始"按钮，踏上你的旅程吧~）

---

### 4.3 情绪感叹词

| 感叹词 | 场景/含义 |
|--------|----------|
| **Ôi trời!** | 天啊！（惊讶/无奈） |
| **Trời ơi!** | 老天啊！（南方口语，更常用） |
| **Wow!** | 哇！（英文借词，直接用） |
| **Quá đỉnh!** | 太厉害了！（赞叹） |
| **Tuyệt vời!** | 太棒了！（称赞，正式） |
| **Không thể tin được!** | 难以置信！ |
| **Thật không?!** | 真的吗？！（惊讶） |
| **Đỉnh quá!** | 太顶了！（网络用语，赞叹） |
| **Xịn xò!** | 太酷了！（网络流行语） |
| **Ngon lành!** | 不错嘛！（南方口语夸奖） |
| **Ôi chao!** | 哎呀！（轻微惊叹） |
| **Trời đất ơi!** | 老天爷啊！（强烈惊讶） |

---

## 节5：越南玩家社区用语（20+个）

### 通用电竞/游戏术语（英文借词）

| 词汇 | 越南语使用方式 | 含义 |
|------|---------------|------|
| **GG** | GG / GG wp | 游戏结束/打得好（Good Game） |
| **AFK** | AFK / đi chỗ khác | 离开键盘/挂机 |
| **noob** | noob / gà | 菜鸟/新手 |
| **pro** | pro / cao thủ | 大神/高手 |
| **hack** | hack / cheat | 开挂 |
| **bug** | bug / lỗi game | 游戏漏洞 |
| **lag** | lag / giật game | 游戏卡顿 |
| **farm** | farm / đi farm | 刷资源/打野 |
| **carry** | carry / gánh team | 带队/carry全队 |
| **feed** | feed / nuôi địch | 送人头（给对方送击杀） |
| **meta** | meta / tướng mạnh nhất | 当前最强阵容/版本强势 |
| **skin** | skin / trang phục | 皮肤/外观 |
| **boss** | boss / trùm | 首领/强力怪 |

### 越南语特有游戏用语

| 词汇 | 含义 | 使用场景 |
|------|------|---------|
| **trùm** | 老大/Boss（越南本土说法） | "Con trùm này khó lắm!"（这个Boss好难！） |
| **thợ rừng** | 打野位（字面：森林工人） | MOBA中的jungler角色 |
| **quẩy** | 玩得嗨/carry起来（活泼用语） | "Quẩy nào anh em!"（一起嗨起来兄弟们！） |
| **bánh kẹo** | 辅助型玩家（字面：糖果饼干，甜甜的辅助） | "Ai đi bánh kẹo không?"（谁去打辅助？） |
| **cần thủ** | ADC/远程输出位（字面：钓鱼者，持远程武器） | MOBA底路输出角色 |
| **đi bẫy** | Gank（字面：设陷阱） | "Đi bẫy mid đi!"（去gank中路！） |
| **ngáo ngơ** | 懵逼的新手（字面：发呆迷糊） | "Ngáo ngơ vãi, đi lộn đường rồi!"（懵了，走错路了！） |
| **phế vật** | 废物/没用的玩家 | 语气较重，骂人用语 |
| **chạy làng** | 逃跑/溜（字面：跑出村子） | "Hắn chạy làng rồi!"（他逃了！） |
| **gánh team** | 背负整个团队（carry全队） | "Mình phải gánh team thôi!"（我得自己扛全队了！） |
| **troll** | 故意捣乱的玩家 | 直接用英文借词 |
| **báo cáo** | 举报 | "Báo cáo thằng này hack!"（举报这个人开挂！） |
| **đồng đội** | 队友（正式用法） | 比"teammate"更常用 |
| **leo rank** | 爬段位 | "Đang leo rank, đừng quấy phá!"（正在爬分，别捣乱！） |
| **trình** | 操作水平/技术 | "Trình này cao quá!"（这个水平太强了！） |

---

## 节6：直译陷阱对照表（12条）

| 中文 | ❌ 错误直译 | ✅ 正确越南语 | 问题说明 |
|------|-----------|-------------|---------|
| 打野（打野位） | ~~đánh dã~~ | **thợ rừng / đi rừng** | "đánh dã"无意义，越南玩家用本土说法 |
| 吃鸡（大逃杀胜利） | ~~ăn gà~~ | **"ăn gà"** ✅ | 罕见例外：越南玩家也接受了"ăn gà"这个说法 |
| 坦克（职业） | ~~cái bể~~ | **tank / chịu đòn** | 不要按字面翻"水箱" |
| 公会 | ~~công hội~~ | **hội / bang / guild** | "công hội"太文言，玩家不用 |
| 服务器 | ~~máy phục vụ~~ | **server / máy chủ** | 直译很奇怪，"server"或"máy chủ"最常用 |
| 技能CD（冷却） | ~~kỹ năng lạnh~~ | **cooldown (CD) / hồi chiêu** | "lạnh"="冷"，词义不对 |
| 首领/老大 | ~~đầu lĩnh~~ | **trùm / boss** | "đầu lĩnh"过于书面，玩家说"trùm"或"boss" |
| 传送 | ~~truyền tống~~ | **dịch chuyển / teleport** | "truyền tống"是"驱逐"的意思，千万别用 |
| 皮肤 | ~~da~~ | **skin / trang phục** | "da"是"皮肤（人体）"，游戏里说"skin"或"trang phục" |
| 升星 | ~~nâng sao~~ | **nâng sao** ✅ | 这个是对的，可以直接用 |
| 开黑（组队） | ~~mở đen~~ | **rủ team / đi team / party up** | "mở đen"="开黑色"，完全错误 |
| 送人头 | ~~tặng đầu~~ | **feed / nuôi địch** | "tặng đầu"有歧义，玩家说"feed"或"nuôi địch"（喂敌人） |
