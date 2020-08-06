# cmus-ncm
用于 [C* Music Player](https://cmus.github.io/) 的 [网易云音乐](https://music.163.com/) 解析插件

# 安装
**请先安装好 Python 3.X 版本**，然后该命令即可一键完成安装
	
	curl https://raw.githubusercontent.com/greats3an/cmus-ncm/master/setup | bash -s [Python 解释器]
e.g. `curl https://raw.githubusercontent.com/greats3an/cmus-ncm/master/setup | bash -s python3.8`

# 使用
## 配置
同 [PyNCM](https://github.com/greats3an/pyncm) 配置方法

## 警告
该脚本会将现有的媒体库清空，并以 [PyNCM](https://github.com/greats3an/pyncm) 的保存目录代之，请事先做好备份，并配置好 [PyNCM](https://github.com/greats3an/pyncm)  的保存目录

## 在 cmus 中的输入 (command)
	:shell cmus-ncm [TYPE] [ID]
### TYPE - 类型
cmus-ncm 支持三类网易云音乐资源的解析：

|TYPE|解释|
|-|-|
|song|单曲|
|playlist|歌单|
|album|专辑|

### ID - 资源ID
可通过网易云音乐的“分享链接”功能取得
如 `https://music.163.com/playlist?id=3199245372&userid=315542615`，该ID即为`3199245372`

## 示例
- 将 [Supernova - **单曲**](https://music.163.com/#/song?id=29732235) 添加到播放列表
	`:shell cmus-ncm song 29732235`
- 将 [各色怪猫[monstercat]色环EP - **歌单**](https://music.163.com/#/playlist?id=36890629) 添加到播放列表
	`:shell cmus-ncm playlist 36890629`
- 将 [The Eminem Show - **专辑**](https://music.163.com/#/album?id=3069044) 添加到播放列表
	`:shell cmus-ncm album 3069044`
	
# Credits
[cmus](https://cmus.github.io/)
[PyNCM](https://github.com/greats3an/pyncm) 
