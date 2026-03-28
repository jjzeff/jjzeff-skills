# 巴西葡语游戏本地化参考手册（PT-BR）

---

## 第1节：巴西葡语游戏本地化核心特征

### 1.1 为什么游戏行业选择 PT-BR？

巴西是全球**第5大游戏市场**，葡语玩家中超过95%来自巴西。PT-BR 与 PT-PT（欧洲葡语）在词汇、语法、语气上存在显著差异，使用错误会让巴西玩家产生疏离感。游戏本地化默认使用 **PT-BR（巴西葡语）**，仅在针对葡萄牙/非洲市场时才切换为 PT-PT。

### 1.2 PT-BR vs PT-PT 关键差异

| 类别 | PT-BR（巴西） | PT-PT（欧洲） | 说明 |
|------|-------------|-------------|------|
| **"你/您"** | você（通用，正式+非正式均可）| tu（非正式）/ você（正式）| 巴西几乎全用você |
| **动词变位** | Você joga（第三人称）| Tu jogas（第二人称）| 巴西não用tu变位 |
| **手机** | celular | telemóvel | 高频词，必须区分 |
| **公共汽车** | ônibus | autocarro | 游戏内交通类文案 |
| **火车/地铁** | metrô / trem | metro / comboio | — |
| **文件(file)** | arquivo | ficheiro | 技术文档常见 |
| **应用程序** | aplicativo / app | aplicação | UI文案必须区分 |
| **下载** | baixar / fazer download | descarregar / fazer download | "baixar"是巴西日常说法 |
| **冰箱** | geladeira | frigorífico | 生活模拟类游戏 |
| **充值/加值** | recarga | carregamento | 支付类UI |
| **语气/基调** | 热情、口语化、感叹号多 | 正式、克制、保守 | 活动文案差异最大 |
| **缩写/俚语** | 大量英文借词+本土俚语 | 较少英文借词 | 见1.3节 |

### 1.3 巴西游戏圈的英文借词习惯

巴西玩家普遍接受并使用大量英文游戏词汇，**无需翻译，直接借用**：

| 英文词 | 在PT-BR中的用法 | 示例 |
|--------|----------------|------|
| skin | skin / skins | "Nova skin disponível!" |
| boss | boss / bosses | "Derrotou o boss final!" |
| rank / ranked | rank / ranqueado | "Partida ranqueada" |
| craft | craft / craftar | "Crafta seu equipamento" |
| buff / nerf | buff / nerf / buffar / nerfar | "Herói buffado nesse patch" |
| patch | patch / atualização | "Patch notes de hoje" |
| streamer | streamer | — |
| gameplay | gameplay | — |
| build | build | "Qual a build certa?" |
| drop | drop / dropar | "Dropou item raro!" |
| farm | farm / farmar | "Vai farmar recursos" |
| grind | grind / grinding | "Muito grinding nesse jogo" |
| meta | meta | "Isso tá no meta agora" |
| bug | bug / bugado | "Tá bugado!" |
| lag | lag / lagado / laguei | "Tô lagando muito" |
| update | update / atualização | 两种均可 |
| login | login / logar | "Faça seu login" |
| quest | quest / missão | 两种均用 |

### 1.4 você vs tu

- **巴西标准**：全国通用 **você**，适合所有正式和非正式场合
- **tu 的使用**：仅在南部（Rio Grande do Sul、部分SC/PR）和 Rio de Janeiro 口语中出现
- **游戏本地化规则**：统一使用 **você**，避免区域性混乱
- **命令语气（imperative）**：
  - 对应 você：使用第三人称祈使 → *Clique aqui!* / *Escolha seu herói!*
  - 口语化可用 infinitivo：*Clicar aqui!* 
  - ❌ 避免：*Clica aqui!*（这是 tu 的变位，不适合全国发行游戏）

### 1.5 巴西玩家文化特点

- **热情外向**：巴西玩家对游戏极度热情，喜欢夸张表达，如 "ABSURDO! 🔥🔥🔥"
- **表情包文化（Meme culture）**：巴西互联网meme传播极快，游戏营销中使用meme效果显著
- **Twitch/直播文化**：巴西是全球Twitch第二大市场（仅次于美国），streamer合作是重要推广方式
- **WhatsApp社群**：游戏公会、活动通知常通过WhatsApp群组传播
- **感叹号风格**：活动文案多用 "!"，与欧洲葡语的克制形成对比
- **家庭向娱乐**：巴西家庭一起游戏的比例高，休闲/全家向游戏有特殊市场

---

## 第2节：游戏UI/系统提示

### 2.1 按钮文案（30个）

| 功能 | PT-BR | 说明 |
|------|-------|------|
| 开始 | Começar / Iniciar | "Começar" 更口语，"Iniciar" 更正式 |
| 继续 | Continuar | — |
| 返回 | Voltar | — |
| 确认 | Confirmar | — |
| 取消 | Cancelar | — |
| 退出 | Sair | — |
| 设置 | Configurações | — |
| 商城/商店 | Loja | — |
| 背包/仓库 | Mochila / Inventário | 休闲游戏用"Mochila"，RPG用"Inventário" |
| 任务 | Missões | — |
| 活动 | Eventos | — |
| 战斗 | Batalhar / Lutar | — |
| 升级 | Melhorar / Evoluir / Upar | "Upar"是巴西游戏圈口语 |
| 强化 | Aprimorar / Fortalecer | — |
| 购买 | Comprar | — |
| 免费获取 | Pegar Grátis | — |
| 收集 | Coletar | — |
| 分享 | Compartilhar | — |
| 邀请好友 | Convidar Amigos | — |
| 排行榜 | Ranking | 直接借用英文 |
| 锁定 | Travar / Bloquear | — |
| 解锁 | Desbloquear | — |
| 删除 | Excluir / Deletar | "Deletar"是巴西口语 |
| 保存 | Salvar | — |
| 加载 | Carregar | — |
| 跳过 | Pular | — |
| 重试 | Tentar Novamente | — |
| 帮助 | Ajuda | — |
| 客服 | Suporte / Atendimento | — |
| 签到 | Check-in / Presença Diária | — |

### 2.2 状态提示（15个）

| 状态 | PT-BR | 示例语境 |
|------|-------|----------|
| 加载中 | Carregando... | 进度条 |
| 连接中 | Conectando... | 网络状态 |
| 已满 | Cheio / Máximo atingido | 背包满 |
| 不足 | Insuficiente / Recursos insuficientes | 资源不够 |
| 冷却中 | Em recarga / Cooldown | 技能CD |
| 维护中 | Em manutenção | 服务器维护 |
| 即将开始 | Em breve / Começando em breve | 活动倒计时 |
| 已过期 | Expirado / Prazo encerrado | 礼包到期 |
| 新内容 | Novo! | 标签角标 |
| 限时 | Por tempo limitado! | 限时活动 |
| 在线 | Online | 好友状态 |
| 离线 | Offline | — |
| 匹配中 | Procurando partida... | 匹配等待 |
| 已完成 | Concluído / Feito! | 任务完成 |
| 锁定中 | Bloqueado | 内容未解锁 |

### 2.3 战斗反馈（10个）

| 反馈 | PT-BR | 风格说明 |
|------|-------|----------|
| 胜利 | VITÓRIA! | 全大写，配特效 |
| 失败 | DERROTA! | — |
| 完美 | PERFEITO! | — |
| 连击 | COMBO x{n}! | 保留英文combo |
| 暴击 | CRÍTICO! | — |
| 闪避 | ESQUIVOU! | — |
| 格挡 | BLOQUEOU! | — |
| 击倒 | ABATIDO! | — |
| 超级技能 | HABILIDADE SUPREMA! | — |
| 五杀 | PENTAKILL! | 保留英文（MOBA通用）|

---

## 第3节：活动运营文案

### 3.1 活动标题风格（巴西风格：热情、感叹、强CTA）

| 类型 | 中文原文 | PT-BR 译文 | 说明 |
|------|---------|-----------|------|
| 节日活动 | 新年活动来袭！ | O Ano Novo chegou com tudo! 🎆 | 感叹+emoji |
| 限时礼包 | 限时礼包，错过不再有！ | Pacote EXCLUSIVO por tempo limitado! Não perca! | 全大写强调 |
| 赛季更新 | 新赛季正式开启！ | A nova temporada CHEGOU! Prepare-se! | 多感叹号 |
| 登录奖励 | 每日登录领取好礼 | Faça login todo dia e ganhe recompensas incríveis! | 动词起头 |
| 联名活动 | ×× 联名活动开启 | Colaboração exclusiva com ×× chegou! | collab术语 |
| 充值回馈 | 充值享双倍奖励 | Recarregue e ganhe o DOBRO de recompensas! | — |

### 3.2 营销语句模板（PT-BR 热情风格）

```
1. 号召行动（CTA）
   - Jogue agora e ganhe recompensas épicas!
   - Não fique de fora! Participe agora!
   - Corra! Oferta por tempo LIMITADO!
   - É de graça! Pega logo!

2. 奖励描述
   - Recompensas ÉPICAS te esperando!
   - Itens exclusivos que você nunca vai querer perder!
   - Bônus especial para os primeiros jogadores!
   - Pack completo com tudo que você precisa!

3. 紧迫感
   - Termina em: {X} horas!
   - Últimas horas! Não deixa passar!
   - Só hoje! Aproveite!
   - Estoque limitado!

4. 社群引导
   - Chame seus amigos e ganhe juntos!
   - Compartilhe com a galera!
   - Mostre pro seus amigos quem manda!
```

### 3.3 奖励描述文案

| 奖励类型 | PT-BR 描述 |
|---------|-----------|
| 金币 | {n} Moedas de Ouro |
| 钻石/宝石 | {n} Gemas / {n} Diamantes |
| 礼包 | Pacote Especial / Bundle Exclusivo |
| 皮肤 | Skin Exclusiva — {nome} |
| 角色 | Personagem Épico — {nome} |
| 经验值 | {n} Pontos de EXP |
| 体力 | {n} Pontos de Energia |
| 随机道具 | Item Surpresa (Aleatório) |

---

## 第4节：剧情/NPC对话

### 4.1 巴西葡语角色语气类型

| 角色类型 | 语气特点 | 常用词汇/句式 |
|---------|---------|-------------|
| 英雄/主角 | 热血、自信、口语化 | "Tô pronto!", "Vamos nessa!", "Pode contar comigo!" |
| 老智者 | 正式、缓慢、古典句式 | "Jovem aventureiro...", "A sabedoria nos diz que..." |
| 反派 | 冷酷、嘲讷、夸张 | "Patéticos.", "Vocês não têm chance alguma.", "Hahaha!" |
| 商人NPC | 热情、促销语气 | "Boa escolha, amigo!", "Temos as melhores ofertas!" |
| 队友 | 随意、鼓励、表情包感 | "Mano, que jogada!", "GG!", "Vamo que vamo!" |
| 任务发布者 | 请求语气、紧张感 | "Preciso da sua ajuda urgente!", "Só você pode fazer isso!" |

### 4.2 常用台词模板

```
【任务接受】
- "Pode deixar comigo!"（包在我身上！）
- "Missão aceita! Vamo nessa!"（任务接受！出发！）
- "Tô dentro!"（我来了！/ 我加入！）

【战斗喊话】
- "Não vão me parar!"（没人能阻止我！）
- "Pela honra da guilda!"（为了公会的荣誉！）
- "VAMOS!"（走！）

【任务完成】
- "Missão concluída! Isso aí!"（任务完成！就是这样！）
- "Sabia que conseguiria!"（我就知道能做到！）
- "GG, galera!"（GG，大家！）

【死亡/失败】
- "Fui... mas vou voltar!"（我倒下了……但我会回来的！）
- "Dessa vez me pegaram..."（这次被他们抓住了……）

【提示/教学】
- "Ei, presta atenção!"（嘿，注意听！）
- "Dica: não esqueça de..."（提示：别忘了……）
```

### 4.3 情绪感叹词（巴西特色）

| 感叹词 | 含义/用法 | 对应情境 |
|--------|---------|---------|
| **Cara!** | 哥们！/ 天哪！（万能感叹）| 惊讶、感叹、打招呼 |
| **Nossa!** / **Nossa Senhora!** | 我的天！| 极度惊讶 |
| **Que saudade!** | 好想念哦！| 怀旧内容、回归活动 |
| **Caramba!** | 天啊！/ 见鬼！| 惊讶、轻微抱怨 |
| **Que absurdo!** | 太离谱了！| 夸张表达 |
| **Demais!** / **Que demais!** | 太棒了！| 极度喜悦 |
| **Uau!** | 哇！| 惊喜 |
| **Eita!** | 哎呀！| 惊讶、出乎意料 |
| **Oxente!** | 哎哟！（东北部地区）| 区域特色NPC |
| **Meu Deus!** | 我的上帝！| 强烈感叹 |
| **Que viagem!** | 太疯狂了！| 匪夷所思的情境 |
| **Valeu!** | 谢了！| 感谢 |
| **Boa!** | 好样的！/ 干得好！| 鼓励、称赞 |
| **Que medo!** | 好可怕！| 恐怖类内容 |
| **Pow!** / **Poxa!** | 哎呀（失望/轻叹）| 失败、遗憾 |

---

## 第5节：巴西玩家社区用语

| 词汇 | 含义 | 使用场景 |
|------|------|---------|
| **mano** | 哥们/兄弟（万能称呼）| "Mano, que jogada incrível!" |
| **véi** | 老兄（口语，比mano更随意）| "Véi, esse boss é impossível" |
| **gg** | Good Game（干得好/游戏结束）| 对局结束时 |
| **ff** | Forfeit（投降/认输）| "Vamo ff" = 我们认输吧 |
| **tá on** | 在线/在线状态（tá = está）| "Tô on, bora jogar!" |
| **zueira** | 搞笑/捣蛋/玩梗 | "É zueira" = 开玩笑的 |
| **noob** | 新手/菜鸟（负面）| "Para de jogar que você é noob" |
| **hackeou** | 作弊/外挂（动词形式）| "Esse cara hackeou!" |
| **lag** / **lagou** / **laguei** | 延迟/卡了 | "Laguei na hora H" |
| **bugou** | 出BUG了 | "O jogo bugou de novo!" |
| **pocpoc** | 轻松碾压/单人屠杀 | 形容打架不费力 |
| **smurf** | 小号/隐藏高手账号 | "Esse cara é smurf" |
| **carregar** | 背队友/carry全队 | "Tive que carregar o time todo" |
| **feed** / **feeder** | 送人头/送死 | "Para de dar feed!" |
| **meta** | 当前最强玩法/主流策略 | "Isso tá no meta" |
| **tiltar** | 心态崩（来自tilt）| "Tiltei com esse resultado" |
| **flanar** / **flanador** | 游荡玩家/野路子 | MOBA中不走分路 |
| **1v1** | 单挑 | "Me desafia pro 1v1" |
| **trash talk** | 嘲讽/语言攻击 | "Menos trash talk, mais jogo" |
| **POG** / **Pog** | 太秒了（来自PogChamp表情）| 直播/Twitch文化 |

---

## 第6节：直译陷阱对照表（12条）

> 从中文直译到葡语时，容易出现的错误及正确译法

| # | 中文原文 | ❌ 错误直译 | ✅ 正确PT-BR | 说明 |
|---|---------|-----------|------------|------|
| 1 | 点击这里 | Toque aqui | **Toque aqui** ✅ (手机) / **Clique aqui** ✅ (PC) | 区分触屏和鼠标操作 |
| 2 | 免费领取 | Obter de graça | **Pegar Grátis** / **Resgatar Grátis** | "Pegar"更口语，"Resgatar"用于兑换码 |
| 3 | 删除角色 | Deletar personagem | **Excluir personagem** (正式UI) / **Deletar** (口语) | 重要操作用Excluir |
| 4 | 下载游戏 | Descarregar o jogo | **Baixar o jogo** | "Descarregar"是PT-PT，巴西用"Baixar" |
| 5 | 手机版 | Versão telemóvel | **Versão celular** / **Versão mobile** | "telemóvel"是PT-PT |
| 6 | 加载中 | Carregamento | **Carregando...** | 动词-ndo形式更自然 |
| 7 | 你的角色 | Tu personagem | **Seu personagem** | 巴西用"seu/sua"（você的物主代词）|
| 8 | 恭喜你 | Parabéns para você | **Parabéns!** / **Parabéns, {nome}!** | 不需要"para você"，冗余 |
| 9 | 限时特惠 | Oferta de tempo limitado | **Oferta por tempo limitado!** | 介词用"por"而非"de" |
| 10 | 游戏结束 | Fim do jogo | **Fim de Jogo** / **Game Over** | 大写；MOBA/动作类可直接用"Game Over" |
| 11 | 请稍候 | Por favor, espere um momento | **Aguarde...** / **Um momento...** | UI中更简洁 |
| 12 | 升级成功 | Atualização bem-sucedida | **Level up!** / **Evoluiu!** / **Nível acima!** | 游戏语境下"level up"比直译更自然 |
