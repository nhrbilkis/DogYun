# Midjourney 新手必读：超详细使用指南

## Discord 与 Midjourney 的关系

Discord 是一款类似于国内 YY 语音的聊天软件，起源于游戏语音、IM 工具服务，现已发展成为涵盖直播平台和游戏商店的社区平台。它是游戏玩家在游戏中沟通协作的首选工具。

Midjourney 是一款 AI 制图工具，只需输入关键字并设置参数，AI 算法便能快速生成对应图片，极大地提升创作效率。你可以将 Midjourney 视为 Discord 上的 BOT，类似于电报平台上的诸多 BOT，方便快捷地提供服务。本文将重点介绍 Midjourney 的使用方法。

---

## 注册账号

打开 Midjourney 官网，首页顶部是动态字符画，科技感十足。点击右下角的“Join the Beta”按钮，页面将自动跳转至 Discord，你可以选择注册或直接登录。

进入 Discord 首页后，还可以选择下载客户端，根据需求选择合适的版本。电脑客户端基于 Electron 等技术，操作体验与 web 端基本一致。

👉 [WildCard | 一分钟注册，轻松订阅海外线上服务](https://bbtdd.com/WildCard)

---

## 基础操作

Discord 平台设计人性化，提供了丰富的提示，帮助用户快速上手。

### 添加服务器

添加服务器是使用 Discord 的基本操作，你可以自行创建或按照模板创建。成功添加服务器后，页面中间会显示使用帮助，例如设置服务器图标、发送第一条消息等。

每个服务器包含文字频道和语音频道。在文字频道中，你可以直接发送消息；选择语音频道后，可进行远程视频、共享屏幕等操作，方便与他人互动。

如果网站申请摄像头权限被禁用，可在浏览器的隐私设置和安全性模块中找到网站设置，为 Discord 配置权限。

### 添加机器人

为了在自己的频道中查看创作内容，建议添加 Midjourney 机器人。否则，在公共频道中，发布的内容会迅速被淹没。

在探索公开服务器中，加入 Midjourney 服务器，可以看到许多用户在此进行创作。在右侧搜索 Midjourney BOT，选择带有机器人字样的结果，将其添加到指定服务器。添加成功后，服务器成员列表将新增一个成员。

---

## 创作图片

在频道中使用“/”选择合适的命令。在对话框中输入 `/imagine` + 提示词，回车后系统将开始生成图片。页面会展示从模糊到清晰的生成过程。如果英文不熟练，可以使用翻译工具生成对应描述。

经过短暂等待后，系统将生成 4 张图片供选择。你可以选择重新生成，或对其中一张进行 V 操作（基于所选图片风格重新生成）或 U 操作（放大像素并提升细节）。编号 1~4 对应左上到右下的图片。

如果生成的图片效果不理想，可能是描述不够精确或使用了默认参数，此时需要耐心调整，才能获得满意的结果。

---

## 常用命令和参数

### 命令

- `/info`：查看当前账户的使用情况。  
- `/subscribe`：进行订阅。  
- `/setting`：设置 Midjourney Bot 相关参数。

### 参数

- `--ar 9:16`：生成图像的宽高比，默认 1:1。  
- `--v <1, 2, 3, 4, 5>`：使用 Midjourney 算法的不同版本，默认 4。  
- `--s 100`：风格化数值越低越接近关键词，越高越艺术化。  
- `--q <.25,.5,1,2>`：默认值为 1，数值越高图片质量越高，渲染时间越长。  
- `--c <0-100>`：chaos 数值越低，生成结果在风格、构图上更相似；数值越高，结果差异越大。  
- `--niji`：调用专门针对动漫和二次元风格的模型。

---

## Midjourney 后台

### 基础操作

在 Midjourney 的个人中心页面，你可以查看历史创作和标记点赞的图片内容。在探索页面，可以浏览公开作品，下载保存图片，或复制描述和参数在 Discord 服务器中创作。

### 充值付费

Midjourney 已取消 25 张图片的免费额度，需付费使用。其付费版本包括：

- **基础版会员**：10 美金/月，可制作 200 张图。  
- **标准版会员**：30 美金/月，无限出图，包含 15 小时快速出图模式。  
- **专业版会员**：60 美金/月，无限出图，包含 30 小时快速出图模式。

可使用支持外币支付的信用卡通过 Stripe 平台进行购买。购买后，可在 Manage Sub 页面查看历史付费信息并取消续订。

### 退款

充值后务必关闭自动续费，否则下月将自动扣款。额外购买的快速出图时间不支持退款。

---

## 案例欣赏

以下是一些优秀的 Midjourney 作品示例：

1. **韩国女神油画**  
   `detailed paint of korean goddess, highly detailed painting by gaston bussiere, craig mullins, j.c. leyendecker and julie bell, 8k, dynamic lighting, colorful lighting --ar 9:16 --v 5 --s 500`

2. **多维剪纸艺术**  
   `Multi-dimensional paper kirigami craft, paper illustration, Chinese illustration on white background, Night, starry sky, Milky Way, above super wide angle, Thomas Kinkade, dreamy, 4K, romantic, trending on Artstation, colorful vanilla oil, 3d relief --ar 2:3 --v 5 --q 2 --s 750`

3. **动漫风格汉服女孩**  
   `anime girl, hanfu style, Authentic silk and brocade textured Hanfu, exquisite facial features, beautiful light and shadow, delicate hair, exquisite Hanfu style, Delicately patterned clothing, delicate earrings and item chains, delicate eyes, translucent skin, 8k picture quality, broken feeling, glass fragments, messy and smooth head, divinity, super detailed::hazy background --ar 9:16 --niji 5 --s 400 --q 2`

👉 [WildCard | 一分钟注册，轻松订阅海外线上服务](https://bbtdd.com/WildCard)