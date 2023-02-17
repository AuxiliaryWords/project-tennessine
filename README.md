# project-tennessine
大体而言只是一个指导向内容。

## 如何获取bilibili视频并获取其音频？

建议:

1. bbdown下载视频（bbdown 地址），需要登录
2. 接下来是确认文件名，建议不要包含中文以及特殊符号。可能对命令行会造成不利影响。
3. ffmpeg -i "文件名（包含后缀)" -vn "提取结果文件名（包括后缀）"
4. 注意音频应当是aac流，因此提取结果建议使用.m4a作为后缀。可以直接 -c:a copy（如果你清楚的话）

[BBDown发布页(releases)](https://github.com/nilaoda/BBDown/releases)

## 加速访问Github？

网上已经有了，个人认为最好的方式是智慧学习上网。

## 这个怎么这样？

不明所以。请学习[提问的智慧(国内镜像)](https://lug.ustc.edu.cn/wiki/doc/smart-questions/)
