# cmus-ncm
用于 [C* Music Player](https://cmus.github.io/) 的 [网易云音乐](https://music.163.com/) 解析插件

# 安装
自行复制文件，使得 `cmus-ncm` 命令有以下输出：

	usage: cmus-ncm [-h] [--stderr] URL
	cmus-ncm: error: the following arguments are required: URL
# 使用
## 配置
同 [PyNCM](https://github.com/greats3an/pyncm) 配置方法

## 提示
歌曲将存储在 `~/Music`

## 在 cmus 中的输入 (command)
	:shell cmus-ncm [URL]

### URL - 资源 URL
可通过网易云音乐的“分享链接”功能取得
如 `https://music.163.com/playlist?id=3199245372&userid=315542615`

## 示例
- 将 [Supernova - **单曲**](https://music.163.com/#/song?id=29732235) 添加到播放列表
	`:shell cmus-ncm "https://music.163.com/#/song?id=29732235"`

## 歌词可视化
### live-lyrics

用于 [C* Music Player](https://cmus.github.io/) 的 LRC 歌词外挂显示工具

#### 使用
直接执行即可；歌词会同 `cmus` 自动同步。

#### 要求
歌词 `(*.lrc)` 需要和歌曲文件同文件名，并在同一目录下

#### 使用
启动 `cmus` 后，在另一个终端内使用 `live-lyrics` 命令即可打开界面

# Credits
[cmus](https://cmus.github.io/)
[PyNCM](https://github.com/greats3an/pyncm) 
