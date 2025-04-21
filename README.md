# 哈尔滨工业大学本科毕业论文 Word 模板

![License](https://img.shields.io/badge/license-CC_BY--SA_4.0-green) 
![Word Version](https://img.shields.io/badge/Word-2019%2B-blueviolet) 
![Zotero Required](https://img.shields.io/badge/Zotero-6.0%2B-FF6F00)

Harbin Institute of Technology (HIT) undergraduate thesis Word template | updated continuously​

​**持续更新维护 | 适配学校格式规范 | 自动化排版解决方案**

---

## 🌟 项目亮点

### 一键式排版功能
- 📊 图表自动编号与交叉引用  
- 📑 绝大部分格式自动生成  
- 📚 符合规范的文献引用格式
- 🔄 续图/续表智能编号系统
  
---

## 🚀 快速入门

### 视频教程
[![HIT论文模板教程封面](https://i2.hdslb.com/bfs/archive/0c9f5d5e7d5e9d7e5f5d7e5d9e7d5e9d.jpg@640w_400h_1c_!web-video-card.webp)](https://www.bilibili.com/video/BV1415bzLEid)

| 平台 | 地址 |
|------|------|
| 哔哩哔哩 | [【最新版】](https://www.bilibili.com/video/BV1415bzLEid) |


### 文件位置说明
```tree
hit-thesis-template-word/
├── templates/
│   └── 哈工大本科毕业论文模板（理工类）.dotx  # 核心模板文件
├── styles/
│   └── china-national-standard-gb-t-7714-2015-numeric-etal-nodoi-fullwidth-nonumber.csl # 文献引用样式
└── README.md
```

### 使用前置
1. 下载安装 [Zotero](https://www.zotero.org/)
2. 自行熟悉Zotero使用；
3. 导入文献样式：
   ```diff
   Zotero > 编辑 > 首选项 > 引用 > 样式 > ‘+’
   选择项目内 styles/ 目录下的：
   + china-national-standard-gb-t-7714-2015-numeric-etal-nodoi-fullwidth-nonumber.csl
   ```

### 模板安装
1. ​**定位模板文件**​  
   - 项目文件 → `templates/哈工大本科毕业论文模板（理工类）.dotx`
2. ​**复制到 Office 模板目录**​  
   ```diff
   + Windows 默认路径：
     C:\Users\你的用户名\Documents\自定义 Office 模板
   或
     文档\自定义 Office 模板
   ```

### 创建新文档
```diff
   新建word > 文件 > 新建 > 个人 > 选择模板 > 保存
   选择期望位置，最后保存成.docx文档，开始编辑。
```

---

## 🛠️ 已知限制与解决方案

公式的编号问题，有以下几种解决方案，但是个人不太满意；
1. 利用Mathtype进行编号，需要自己添加章节符，较为麻烦；
2. 利用word无线框表格编号，需要手动编号，自动编号问题尚未解决；
3. 直接手敲编号，并用输入空格的方式控制公式位置，暴力方法，工作量较大。

---

## 📜 协议声明
- 模板本体采用 [CC BY-SA 4.0](https://creativecommons.org/licenses/by-sa/4.0/) 协议  
- 文献样式文件改编自 [eduyob/chinese-gbt7714-2015-numeric-etal-nodoi.csl](https://gitee.com/eduyob/citation-styles)
- 修改内容：去除文献引用(Bibliography)自动序号。
