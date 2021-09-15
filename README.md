# rime_pro
## rime 懒人版配置文件
### 安装步骤：
#### 第一步
下载并安装鼠须管输入法
#### 第二步
备份现有的配置，打开终端输入 cp -a ~/Library/Rime ~/Library/Rime_ori_$(date +%Y%m%d%H%M%S) 会得到一个类似 ~/Library/Rime_ori_20170501225630 的文件夹 即为备份
(linux 配置文件在/home/user/.config/ibus/rime)
#### 第三步 
下载并解压出 rime_pro 增强包 里的文件复制到 ~/Library/Rime 文件夹 覆盖默认文件
#### 第四步
切换到鼠须管输入法，重新部署(约1分钟)  `ibus restart`

### 软件介绍：
rime_pro 增强包是鼠须管输入法的第三方增强包，仅由我业余爱好制作，和原版软件作者无关。如果想要卸载本增强包，那么把刚刚备份的 Rime_ori_20170501225630 文件夹 重命名为 Rime 即可。
