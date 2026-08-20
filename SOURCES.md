# 场记训练场：案例与方法来源

核验日期：2026-08-21

每条内容都按大白话写清楚：

- 我实际看到了什么。
- 它适合教哪一步。
- 它不能保证什么。
- 原文、代码或成片能不能转载。

公开可看不自动等于可下载、可重传或可打包。网页只托管明确随 MIT 许可进入本地仓库的四段示例视频；其余案例只放教学摘要与一手链接。

## 剧本与故事训练

1. Pixar × Khan Academy, The Art of Storytelling  
   https://www.khanacademy.org/computing/pixar/storytelling
   我看到：Pixar 与 Khan Academy 联合课程，包含角色、故事结构、视觉语言、电影语法、分镜和反馈练习。它能教小白把故事压成关键节点，但不能保证写出的故事一定好看。

2. BBC Writersroom, Screenplay Format  
   https://downloads.bbc.co.uk/writersroom/scripts/screenplay.pdf  
   状态：官方格式指南，link-only。

3. eternityspring, shuohao-skills  
   https://github.com/eternityspring/shuohao-skills  
   状态：Apache-2.0；可学习剧本、分镜和镜头字段结构。

## 分镜与生产结构

4. Wonder Unit, Storyboarder  
   https://wonderunit.com/storyboarder/  
   https://github.com/wonderunit/storyboarder  
   我看到：官方工具页面和公开仓库都存在。它能用火柴人草图检查镜头顺序，但官方也把它称为小众工具；网站只借用“画三格、顺序播放、改掉看不懂的一格”这个练习，不要求安装。

5. LocalMiniDrama  
   https://github.com/xuanyustudio/LocalMiniDrama  
   状态：MIT；仓库媒体另行核对。

6. Jellyfish  
   https://github.com/Forget-C/Jellyfish  
   状态：Apache-2.0。

## 模型与官方提示方法

7. Runway, Image to Video Prompting Guide
   https://help.runwayml.com/hc/en-us/articles/48324313115155-Image-to-Video-Prompting-Guide
   我看到：当前官方指南针对 Gen-4.5。图生视频时，图片已经负责外观，文字主要写怎么动；官方建议从简单动作开始，每次只加一个变化。它不能保证一次生成成功，也不能保证别的平台得到同样结果。

8. Google Cloud, Veo video generation prompt guide  
   https://docs.cloud.google.com/vertex-ai/generative-ai/docs/video/video-gen-prompt-guide?hl=zh-CN  
   状态：官方文档；Google 文档页面许可按其页脚条款处理。

9. Adobe Firefly, Create AI video with first and last keyframes
   https://www.adobe.com/learn/firefly/web/create-ai-video-with-text-prompts
   https://helpx.adobe.com/ca/firefly/web/work-with-audio-and-video/work-with-video/generate-videos-using-images.html
   我看到：官方教程支持用第一帧和最后一帧引导视频开头和结尾。它能管住两头，不能保证中间运动自然，也不能保证人物脸、服装或文字细节完全一致。

10. ComfyUI Examples, Wan workflows  
    https://comfyanonymous.github.io/ComfyUI_examples/wan/  
    https://github.com/comfyanonymous/ComfyUI_examples  
    状态：工作流示例可按仓库许可证使用；图片、视频和模型权重许可分开。

11. Lightricks, LTX-Video  
    https://github.com/Lightricks/LTX-Video  
    状态：代码 Apache-2.0；具体模型权重有单独许可。

12. ByteDance Seed, Seedance 2.0 official launch  
   https://seed.bytedance.com/en/blog/seedance-2-0-official-launch  
   状态：官方发布页，link-only。

## 用户提供材料与网站教学修正（新增）

- 用户个人《每日 AI 创作简报》（私有对话，不公开链接）
  状态：长期学习材料的方法提炼；稳定主线包括参考职责、单镜单变化、故事板/关键帧、Image-to-Video、首中真实末帧和单变量复盘。网页只吸收方法，不公开转载私人对话。

13. 实战短剧 15 秒剧本分组拆解法  
    来源文件：《剧本拆解脚本案例.docx》  
    状态：用户提供的单一案例，成片验证未知；网页不转载其正文，只吸收“故事功能、段落落点、分组接力”，并用原创案例《旧影开场前》展示网站的教学修正。

14. 15 秒分镜脚本分层规范  
    来源文件：《剧本拆解分镜脚本 知识库&案例.docx》  
    状态：用户提供的单一案例，成片验证未知；网页不转载其正文，用原创案例《失物招领处》展示手法、画面、音效、台词、终态和组内时长，并修正原材料的超载与单镜混切问题。

15. 核绘 / Seedance 画布实战经验与防错体系  
    来源文件：《核绘 案例讲解.docx》  
    状态：平台制作经验，无控制实验；保留其体型服装差异、全景站位图和正向描述经验。提示顺序与括号权重分别列为待 A/B 的经验，不升级为平台定律。

## 新片场与 Shotlab

这些页面用于两种不同练习：能看到制作过程的，才可以借用做法；只能看到成片的，只练逐镜观察，不猜提示词。

16. Shotlab 3D 导演台样例画布
   https://aigc.xinpianchang.com/canvas/view/f6da7cb4ff5b498dae02b7e297f7406e
   2026-08-21 未登录实际打开：看到了两张人物设定图、一个场景设定、3D 导演台和自由视角截图。它能教“先固定人物和房间，再换景别”，不能证明长片人物一定稳定。

17. Shotlab Seedance 2.5 1080P 样例画布
   https://aigc.xinpianchang.com/canvas/view/f924fd367d0c40819cb622a57ae82297
   2026-08-21 未登录实际打开：看到了一个图片节点和一个 20.1 秒视频节点。它只用于“一张图、一个动作、一条短视频”的第一次操作练习，不能当优秀剧本案例。

18. Shotlab《古言氛围感短剧教程》公开画布
   https://aigc.xinpianchang.com/canvas/view/b6fda7dba2f346379003f085aa1c9a37
   2026-08-21 实际打开：页面公开显示完整剧本、约 60 秒 24 镜分镜、人物图、团扇道具、男女声音和多个视频节点。网站只借用前三镜的作用顺序，不让小白照抄整条复杂短剧。没有做同模型对照测试，也没有确认 24 个镜头都生成成功。

19. 新片场成片《要么爆火出圈，要么就此收场》
   https://www.xinpianchang.com/a13785291
   2026-08-21 实际打开公开详情页：可以播放 1:02 成片并看到简介；没有公开可查看的分镜和 Shotlab 画布。网站只借“旧电视购物形式介绍新工具”的创意结构，不反推提示词。

20. 新片场成片《顾左右的世界末日》
   https://www.xinpianchang.com/a13787883
   2026-08-21 实际打开公开详情页：可以播放 8:31 成片，简介给出孩子遇到大人无法直说的问题并进入冒险。页面没有公开制作画布；网站只把开头一分钟用作“抽象问题变成可见异常”的观察题。

21. 新片场 × 与光 AI 学员作品公开专辑
   https://www.xinpianchang.com/user/collection/11061
   2026-08-21 公开页面显示 15 条 AI 作品及标题、时长和播放信息。它只用于练习数切镜、判断每镜让观众看清什么；专辑没有公开每条作品的剧本、提示词和完整制作过程，所以不能当成已验证工作流。

22. Liblib / LibTV《镜外之徒》公开画布
   https://www.liblib.tv/canvas?projectId=d7c07918c09a40978e19f5805b0c12e7&spaceId=4915092

23. 新片场《回到宇宙诞生之前》分镜页
   https://www.xinpianchang.com/storyboard/13572095
   2026-08-21 直接访问会跳到登录页；网站保留 2026-08-08 的部分记录：当时只核对前 8 镜。它不能进入“可以照着练”，只用于说明“看过成片”和“看过制作过程”是两件事。

## 本地许可媒体

24. vox-director
   https://github.com/Alisa0808/vox-director  
   固定提交：987be2f42332247a3ad7a244c76e86fca92c1f1d  
   本网页使用：showcase-tang.mp4  
   许可：MIT，见 /licenses/LICENSE-vox-director.txt。

25. VOX-COLLAGE-BROLL
   https://github.com/MegaTroll222/VOX-COLLAGE-BROLL  
   固定提交：2e9b8a93a2834e4d670700ab9e4827a8baf3b668  
   本网页使用：candles.mp4、dominoes.mp4、snowball.mp4  
   许可：MIT，见 /licenses/LICENSE-vox-collage-broll.txt。

完整第三方声明：/licenses/THIRD_PARTY_NOTICES.md

## 这些内容不能保证什么

网页里的练习和失败检查是教学设计，不是任何平台对生成成功率的保证。网页只能检查你有没有写清剧本、镜头和提示词；真实视频是否可用，仍要由你检查第一帧、中间动作、最后一帧，并亲自决定是否愿意继续使用。
