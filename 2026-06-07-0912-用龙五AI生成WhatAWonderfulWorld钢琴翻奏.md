# 用龙五AI生成 What a Wonderful World 纯钢琴翻奏

## 操作意图
用龙五（M4 Mac Mini）上的本地 AI 模型生成一首纯钢琴版的《What a Wonderful World》器乐翻奏，嵌入 web 页面作为背景音乐，滑动自动播放 + 循环。

## 上下文
- 用户选定《What a Wonderful World》作为背景音乐
- 该歌曲版权仍有效（1967年创作），不能直接用原版录音
- 但旋律本身可通过 AI 生成翻奏（新创作），不涉及录音版权问题
- 龙五 M4 Mac Mini 有本地 Ollama 模型（Hermes 3 / Qwen2.5:7b）
- 需找能生成音乐的工具

## 执行计划
1. 确认龙五上是否有能生成音乐的模型/工具
2. 如无，考虑方案：
   - 用龙五跑音乐生成模型（如 MusicGen / AudioCraft 等）
   - 或直接找公开领域/CC协议的翻奏版本
3. 生成/获取 mp3 后替换到 `public/audio/`
4. 更新署名信息
5. 提交推送

## 状态
待确认技术方案后执行
