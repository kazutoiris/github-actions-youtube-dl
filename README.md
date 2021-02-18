# Github-actions-youtube-dl ![CI](https://github.com/kazutoiris/github-actions-youtube-dl/workflows/CI/badge.svg)

使用 GitHub Actions 下载 YouTube 最高画质视频，并自动发布到国内 CDN。


## 注意！

- **最高可以发布 2G 大小的文件，注意每个视频最大大小不要超过 2G。**

## 使用

1. Fork 本仓库 或者 Use this template。

2. 创建好自己的仓库后，在 Actions 中启用 GitHub Actions（Use this template 默认启用）。

3. 将你要下载的 YouTube 视频的地址填进 **playlist.txt** 中，每行限一个视频链接，commit push 提交。

4. Actions 自动运行后会将所有下载好的视频分开上传至奶牛快传和 WeTransfer。链接在每个 Action 的详情内看。

## License

[Anti 996 License Version 1.0](https://github.com/kazutoiris/github-actions-youtube-dl/blob/main/LICENSE)

## 鸣谢

[justjavac](https://github.com/justjavac/github-actions-youtube-dl)
[Heraldik](https://github.com/Heraldik/github-actions-youtube-dl)

