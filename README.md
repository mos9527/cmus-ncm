# cmus-ncm
用于 [C* Music Player](https://cmus.github.io/) 的 [网易云音乐](https://music.163.com/) 解析插件

# 安装
**请先安装好 Python 3.X 版本**，使用以下脚本可快速完成安装
	
	curl https://raw.githubusercontent.com/greats3an/cmus-ncm/master/setup | bash -s [Python 解释器]
e.g. `curl https://raw.githubusercontent.com/greats3an/cmus-ncm/master/setup | bash -s python3.8`
	在随后的选项中，选择 1 安装 cmus-ncm
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

#### 安装
**请先安装好 Python 3.X 版本**，使用以下脚本可快速完成安装
	
	curl https://raw.githubusercontent.com/greats3an/cmus-ncm/master/setup | bash -s [Python 解释器]
e.g. `curl https://raw.githubusercontent.com/greats3an/cmus-ncm/master/setup | bash -s python3.8`
	在随后的选项中，选择 2 安装 live-lyrics

#### 要求
歌词 `(*.lrc)` 需要和歌曲文件同文件名，并在同一目录下

#### 使用
启动 `cmus` 后，在另一个终端内使用 `live-lyrics` 命令即可打开界面

# Credits
[cmus](https://cmus.github.io/)
[PyNCM](https://github.com/greats3an/pyncm) 
