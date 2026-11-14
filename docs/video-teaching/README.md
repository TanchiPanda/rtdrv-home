# 视频教程目录

介绍站的「视频教程」区块默认读取本目录下的 `tutorial.mp4`。

- 文件名：`tutorial.mp4`（改了名字需要同步修改 `index.html` 里 `<source src="docs/video-teaching/...">`）
- 编码：H.264 + AAC，16:9，建议 1080p，5–10 分钟一集
- 封面：可选 `poster.jpg`，需要时在 `<video poster="docs/video-teaching/poster.jpg">` 里引用
- 字幕：可选 `tutorial.vtt`，内嵌或外挂均可

文件放进本目录并推到 main，Pages 构建完成后页面会自动显示播放器；文件不存在时页面保留「待上传」占位。
