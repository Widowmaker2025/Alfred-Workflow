# Alfred-Workflow
维护 Alfred 上 个人开发 和 使用的 Workflow


## rime词库维护
> 使用场景: rime 个人词库维护追加 自造词,常用词</br>
> 使用要求:</br>
>   1. 软件(rime-Squirrel, Alfred)</br>
>   2. $home/Library/Rime内需要有 custom_phrase.txt文件夹 (一般导入过主流输入方案的 都会有这个文件,例如 雾凇拼音,万象拼音)</br>
>
> 使用方法: 双击 导入到Alfred 即可</br>
> 使用格式: rime Go协程 go 99 (rime 为 触发词 , Go协程 为 目标单词 go 为 简写词  99为权重,数字越大权重越高 数字可选)</br>
> 使用效果: 可查看 目标文件中是否 录入特定的内容 , 该workflow是自动部署和更新</br>
> 备注:  代码非常简单,若担心 自行查看源代码</br>
>
> 当前版本 只做 追加Add,不做更新update;  追加是 高频核心需求.  查找和更新 低频直接在文件中修改即可</br>
