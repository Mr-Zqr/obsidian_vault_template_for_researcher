---
title: 文献库作者排序
date: 2021-11-11 20:10:51
top_n: 20
obsidianUIMode: preview
---

1. 点击下方按钮即可对文献库中作者出现的次数进行统计并排序。
2. 如果要修改显示的数量，请修改 front-matter 中 top_n 的数值，不要超过100。
3. 注意此按钮所执行的templater自定义函数仅对此页面生效，所以不可引用。
4. 如果您的文献库数量太少，建议将 top_n 数值设置为 3 进行测试。

%%button如果使用模板，则模板应存放于 09-Templates的根目录，不能为其子目录%%

```button
name 🐼作者统计
type append template
action author_count
replace [22,122]
```
^button-7x0p

### 2023-09-18
471
[[M. Hutter]] : 16
[[M. Fallon]] : 12
[[M. Camurri]] : 9
[[Axel Barrau]] : 7
[[Silvere Bonnabel]] : 6
[[P. Fankhauser]] : 6
[[R. Siegwart]] : 5
[[M. Bloesch]] : 5
[[D. Berenson]] : 4
[[C. Semini]] : 4
[[L. Wellhausen]] : 4
[[Maurice Fallon]] : 4
[[M. Ramezani]] : 4
[[X. Xinjilefu]] : 3
[[K. Walas]] : 3
[[M. Bjelonic]] : 3
[[Marco Hutter]] : 3
[[Guoquan Huang]] : 3
[[S. Khattak]] : 3
[[R. Hartley]] : 3