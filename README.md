## 例1，tab按钮在上
````md
```minitabs
tabs
`按钮1` `按钮2` `可以一直写下去……` 
===
第一个按钮对应的页面
===
按钮二对应的页面
===
按钮三对应的页面
```
````
## 例2，tab按钮在下
````md
```minitabs
tabsBottom
`按钮1` `按钮2` `可以一直写下去……` 
===
第一个按钮对应的页面
===
按钮二对应的页面
===
按钮三对应的页面
```
````


## 上下tab按钮相互套娃
这只是一个示例！实际上，如果需要套娃更推荐用`![[link]]`链接到第二层 tabs。
``````md
`````minitabs
tabs
`按钮1` `按钮2` `按钮3` 
---
>[!Note]+ 1
># 1
````minitabs
tabsBottom
`按钮1` `按钮2` `按钮3` 
===
>[!Note]+ 1
># 1.1
===
>[!Note]+ 1
># 1.2
===
>[!Note]+ 1
># 1.3
````
---
>[!Note]+ 1
># 2
````minitabs
tabsBottom
`按钮1` `按钮2` `按钮3` 
===
>[!Note]+ 1
># 2.1
===
>[!Note]+ 1
># 2.2
===
>[!Note]+ 1
># 2.3
````
---
>[!Note]+ 1
># 3
````minitabs
tabsBottom
`按钮3.1` `按钮3.2` `按钮3.3` 
===
>[!Note]+ 1
># 3.1
===
>[!Note]+ 1
># 3.2
===
>[!Note]+ 1
># 3.3
````
`````
``````


