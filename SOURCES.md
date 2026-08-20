# 场记训练场：案例与方法来源

核验日期：2026-08-19

本清单区分：

- 官方方法：用于核对平台当前公开建议。
- 开源结构：代码或工作流有明确许可证；媒体与模型权重仍需单独核对。
- 历史实证：此前在本机真实查看、记录过，但页面可能已经变化。
- 本地许可媒体：已随本网页保留许可证和第三方声明。

公开可看不自动等于可下载、可重传或可打包。网页只托管明确随 MIT 许可进入本地仓库的四段示例视频；其余案例只放教学摘要与一手链接。

## 剧本与故事训练

1. Pixar × Khan Academy, The Art of Storytelling  
   https://www.khanacademy.org/humanities/hass-storytelling  
   状态：官方免费课程，link-only。

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
   状态：作者公开称免费开源，但仓库当前未由 GitHub API 识别出 SPDX 许可证；仅外链，不复制源码或媒体。

5. LocalMiniDrama  
   https://github.com/xuanyustudio/LocalMiniDrama  
   状态：MIT；仓库媒体另行核对。

6. Jellyfish  
   https://github.com/Forget-C/Jellyfish  
   状态：Apache-2.0。

## 模型与官方提示方法

7. Runway, Gen-4 Video Prompting Guide  
   https://help.runwayml.com/hc/en-us/articles/39789879462419-Gen-4-Video-Prompting-Guide  
   状态：官方帮助页，link-only。

8. Google Cloud, Veo video generation prompt guide  
   https://docs.cloud.google.com/vertex-ai/generative-ai/docs/video/video-gen-prompt-guide?hl=zh-CN  
   状态：官方文档；Google 文档页面许可按其页脚条款处理。

9. Adobe Firefly, Create cinematic video from prompts and keyframes  
   https://helpx.adobe.com/firefly/how-to/create-ai-video-with-text-prompts.html  
   状态：官方练习；示例 stock assets 仅供练习，本网页未再分发。

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

13. 实战短剧 15 秒剧本分组拆解法  
    来源文件：《剧本拆解脚本案例.docx》  
    状态：用户提供的单一案例，成片验证未知；网页不转载其正文，只吸收“故事功能、段落落点、分组接力”，并用原创案例《旧影开场前》展示网站的教学修正。

14. 15 秒分镜脚本分层规范  
    来源文件：《剧本拆解分镜脚本 知识库&案例.docx》  
    状态：用户提供的单一案例，成片验证未知；网页不转载其正文，用原创案例《失物招领处》展示手法、画面、音效、台词、终态和组内时长，并修正原材料的超载与单镜混切问题。

15. 核绘 / Seedance 画布实战经验与防错体系  
    来源文件：《核绘 案例讲解.docx》  
    状态：平台制作经验，无控制实验；保留其体型服装差异、全景站位图和正向描述经验。提示顺序与括号权重分别列为待 A/B 的经验，不升级为平台定律。

## 历史实证案例

以下案例来自 2026-08-08 的本地工作簿与证据索引。网页保留当时的“已验证 / 部分验证 / 未知”边界，不把它们冒充 2026-08-19 的实时页面状态。

16. Shotlab《古言氛围感短剧教程》公开画布  
   https://aigc.xinpianchang.com/canvas/view/b6fda7dba2f346379003f085aa1c9a37

17. Liblib / LibTV《镜外之徒》公开画布  
   https://www.liblib.tv/canvas?projectId=d7c07918c09a40978e19f5805b0c12e7&spaceId=4915092

18. 新片场《回到宇宙诞生之前》分镜页  
   https://www.xinpianchang.com/storyboard/13572095

## 本地许可媒体

19. vox-director  
   https://github.com/Alisa0808/vox-director  
   固定提交：987be2f42332247a3ad7a244c76e86fca92c1f1d  
   本网页使用：showcase-tang.mp4  
   许可：MIT，见 /licenses/LICENSE-vox-director.txt。

20. VOX-COLLAGE-BROLL  
   https://github.com/MegaTroll222/VOX-COLLAGE-BROLL  
   固定提交：2e9b8a93a2834e4d670700ab9e4827a8baf3b668  
   本网页使用：candles.mp4、dominoes.mp4、snowball.mp4  
   许可：MIT，见 /licenses/LICENSE-vox-collage-broll.txt。

完整第三方声明：/licenses/THIRD_PARTY_NOTICES.md

## 教学推断边界

网页中的练习、评分规则、失败诊断和“回到哪一层”属于基于上述来源与本地失败证据形成的教学设计，不应被解读为任何平台对生成成功率的保证。训练分只检查结构要素和负载；真实输出仍需首帧、关键中间帧、真实尾帧和人工审美验收。
