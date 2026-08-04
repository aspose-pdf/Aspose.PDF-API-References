---
title: "LatexLoadOptions"
second_title: "Aspose.PDF for Python via .NET API 参考"
description: "表示将 TeX 文件加载/导入到 PDF 文档的选项。"
type: docs
weight: 820
url: /zh/python-net/aspose.pdf/latexloadoptions/
---

## LatexLoadOptions class

表示将 TeX 文件加载/导入到 PDF 文档的选项。

LatexLoadOptions 类型公开以下成员：
## 构造函数
| 名称 | 描述 |
| :- | :- |
| LatexLoadOptions() | 初始化 LatexLoadOptions 类的新实例 |
## 属性
| 名称 | 描述 |
| :- | :- |
| warning_handler | 回调以处理生成的任何警告。 <br/>            WarningHandler 返回 ReturnAction 枚举项，指定 Continue 或 Abort。 <br/>            Continue 是默认操作，加载过程将继续，但用户也可以返回 Abort，此时加载过程应停止。 |
| load_format | 表示由 [LoadOptions](/pdf/python-net/aspose.pdf/loadoptions/) 描述的文件格式。 |
| job_name | 获取/设置 作业的名称。 |
| input_directory | 获取/设置 TeX 输入目录。 |
| output_directory | 获取/设置 TeX 输出目录。 |
| repeat | 获取/设置 标志，指示在某些情况下是否需要运行 TeX 作业两次，例如，输入 TeX 文件中存在引用。一般来说，此行为在以下情况下有用，<br/>            引擎在排版过程中收集一些数据并将其存储在辅助文件中，<br/>            所有这些都在第一次运行时完成。第二次运行时，引擎会以某种方式使用这些数据。 |
| subset_fonts | 获取/设置 标志，指示是否在输出文件中子集化字体。 |
| show_terminal_output | 获取/设置 标志，指示是否在控制台上显示终端输出。 |
| date_time | 获取/设置 日期/时间原语（如 \year、\month、\day 和 \time）的特定值。 |
| no_ligatures | 获取/设置 取消所有字体连字的标志。 |
| rasterize_formulas | 获取/设置 允许光栅化数学公式的标志。 |

### 另请参阅

* namespace [aspose.pdf](/pdf/python-net/aspose.pdf/)
* assembly [Aspose.PDF](/pdf/python-net/)

