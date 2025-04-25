```text
latex_project/                 # 项目根目录
├── main.tex                   # 主文档入口
├── config/                    # 配置
│   ├── packages.tex           # 所有宏包加载
│   ├── settings.tex           # 页面布局/字体等设置
│   └── commands.tex           # 自定义命令
├── chapter/                   # 章节内容
│   ├── chapter01.tex          # 第1章
│   ├── chapter02.tex          # 第2章
│   └── ...
├── misc/                      # 杂项内容
│   ├── abstract.tex           # 中英文摘要
│   ├── acknowledgement.tex    # 致谢
│   └── declaration.tex        # 原创声明
│   └── ...
├── pic/                       # 图片资源
│   ├── .png/.jpg              # 图片
│   └── .svg                   # 矢量图
│   └── ...
├── data/                      # 数据文件
│   ├── results.csv            # 实验数据  
│   └── code/                  # 代码输出
│   └── ...
├── reference/                 # 参考文献
│   ├── bibliography.bib       # BibTeX数据库
│   └── bst-styles/            # 自定义引用样式
└── output/                    # 编译输出（建议.gitignore）
    ├── main.pdf               # 最终PDF
    └── ...
```
