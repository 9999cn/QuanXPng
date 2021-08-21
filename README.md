# QuanXPng
欢迎使用QuanXPng图标，立这个仓库的原因是补充大佬们所遗漏和没兴趣做的图标。都是自己PS做做玩的。
## 使用说明
### 方式对比
| 方式 | 添加图标 | 更新图标 | 图标维护 | 获取及时性 | 操作便利性 | 
| :---: | :---: | :---: | :---: | :---: | :---: |
| 远程图标 | 编辑配置 | 清理缓存 | 图标作者 | ✅ | ✅ |
| 本地图标 | 编辑配置+文件操作 | 文件操作 | 用户本人 | ❌ | ❌|

#### 方式一：远程图标<br>
*跨设备同步策略组图标，及时获取图标更新*<br>
*该操作以 Quantumult X v1.0.8-build249 为例*<br>
1. 在 [常规图标预览](https://github.com/Koolson/Qure#%E6%95%88%E6%9E%9C%E5%9B%BE%E9%A2%84%E8%A7%88)、[归档图标预览](https://raw.githubusercontent.com/Koolson/Qure/master/Other/Qure_Preview_Archived.png) 或 [IconSet 页面](https://github.com/Koolson/Qure/tree/master/IconSet) 中找到需要的策略组图标并记下**图标名称**；<br>
2. 在 Quantumult X 的“配置文件-编辑”中找到[policy]下的策略组字段，并在该策略组的最后一个节点后方加上：<br>
`img-url=https://raw.githubusercontent.com/Koolson/Qure/master/IconSet/图标名称.png`<br>
例如：<br>
`static=Hong Kong, 🇭🇰01, img-url=https://raw.githubusercontent.com/Koolson/Qure/master/IconSet/Hong_Kong.png`<br>

```ruby
注意：此处“img”前的英文逗号和空格以及“Hong_Kong.png”图标名称中的下划短横线和字母大小写
```

3. 重启 Quantumult X 即可见到效果。<br>

><font color=red>更新方法：当远程图标更新时，请手动清理本地图标缓存(打开“文件”应用，依次进入“**我的 iPhone 或 iCloud Drive-Quantumult X-Images**”，删除Images文件夹内所有缓存文件)，并重启 Quantumult X，远程图标会重新下载并生效。</font>
