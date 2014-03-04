这是我的emacs配置，来自于 [purcell](https://github.com/purcell/emacs.d.git) ，在 purcell 的基础上做了一些适合我自己的必要的修改，我的 emacs 是运行在 Mac 上的，但是这些配置文件同样适用于 Ubuntu ，通过git将此配置文件克隆到主文件夹中，如下所示：  
  
`git clone https://github.com/abnerwang/emacs.d.git ~/.emacs.d`  
  
克隆完毕后，首先需要修改 .emacs.d 中文件 init.el 第84行 `split string` 后面双引号括起来的所有路径为你的电脑中的对应位置，通过以下命令在 shell 中获得这些路径：  
  
`echo "" | g++ -v -x c++ -E -`  
  
修改完路径后，保存文件 init.el ，打开 emacs ，自动下载插件，下载完成后，就可以使用了  
  
Ubuntu 环境下 Emacs 的配置与以上过程完全类似  
  
by abner wang  
2014-03-04