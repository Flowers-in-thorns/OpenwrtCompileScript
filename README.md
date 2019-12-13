# OpenwrtCompileScript

## 序言

用于辅助Openwrt编译，但不会帮你完成整个编译过程，需要一点Openwrt编译基础

降低编译难度，减少重复的步骤，但不利于学习，此脚本适用于有点openwrt编译的基础的最佳，完全没有编译基础的请去补充相关知识

 此脚本并不是无脑脚本，这个脚本对新手是无脑的但要点基础，起码你要会选择机型与插件，有点基础的可以说是辅助，加快你的编译速度，写这个脚本的初衷就是编译的过程重复太多，所以写了脚本


## 支持系统

The script is made to work on these OS :

- Ubuntu 16.4
- Ubuntu 18.4 （首选，脚本基于此版本编写测试）
- win10子系统（ubuntu 18.04 LTS）

## Usage 使用方法

1、使用git克隆下载脚本并赋予执行权限

```bash
git clone https://github.com/Flowers-in-thorns/OpenwrtCompileScript.git && chmod +x OpenwrtCompileScript/openwrt.sh

```

2、进入脚本目录并执行

```bash
cd OpenwrtCompileScript && bash openwrt.sh
```

**注意**:执行脚本后会自动添加系统变量，第二次可使用如下命令运行脚本。

`bash $openwrt`




