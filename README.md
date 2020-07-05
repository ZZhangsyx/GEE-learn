// Hello Everyone!

// 这篇文章将用中文记录学习GEE中遇到的问题和跟着学总结出来的一套教程，希望对大家有所帮助。
// 现阶段主要用的是python，基于geemap做的一些总结。

1. 环境介绍
Windows64位, jupyter notebook, python，geemap

2. 安装
（1）GEE:科学上网，注册账号
（2）anaconda:
	安装：https://www.continuum.io/downloads/
	用法：
		升级conda(升级Anaconda前需要先升级conda)：conda update conda 
		升级anaconda：conda update anaconda 
		升级spyder：conda update spyder
		更新所有包：conda update --all
		安装包：conda install package
		更新包：conda update package
		换源：https://zhuanlan.zhihu.com/p/62899936

（3）jupyter notebook:
	安装anaconda后自带。
	用法：https://zhuanlan.zhihu.com/p/36858283
	优雅的用法：https://www.zhihu.com/question/59392251
（4）geemap：
	参考：https://github.com/giswqs/geemap
	安装：conda create -n gee python=3.7
	conda activate gee
	conda install mamba -c conda-forge
	mamba install geemap -c conda-forge

