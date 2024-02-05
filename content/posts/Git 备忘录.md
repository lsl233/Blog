---
title: "Git 备忘录"
date: 2023-07-03T17:20:18+08:00
draft: true
---

# Git Message emoji
| code                          | note                     |
| ----------------------------- | ------------------------ |
| `:bug:`                       | 修复bug                  |
| `:sparkles:`                  | 新功能                   |
| `:bookmark:`                  | 发布/版本标签             |
| `:construction:`              | 工作正在进行中           |
| `:twisted_rightwards_arrows:` | 合并分支                 |
| `:rewind:`                    | 还原更改                 |
| `:hammer:`                    | 添加或更新构建脚本       |
| `:wrench:`                    | 添加或更新配置文件       |
| `:recycle:`                   | 重构代码                 |
| `:heavy_plus_sign:`           | 添加依赖项               |
| `:heavy_minus_sign:`          | 删除依赖项               |
| `:chart_with_upwards_trend:`  | 添加或更新分析或跟踪代码 |

# Tips
查看分支是基于哪一个分支创建的 
```
git reflog --date=local | grep <分支名>
```

取消合并
```
git merge --abort 
```