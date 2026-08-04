---
title: "PdfSaveOptions"
second_title: "Aspose.PDF for Python via .NET API 参考"
description: "导出为 Pdf 格式的保存选项。"
type: docs
weight: 1240
url: /zh/python-net/aspose.pdf/pdfsaveoptions/
---

## PdfSaveOptions class

导出为 Pdf 格式的保存选项。

PdfSaveOptions 类型公开以下成员：
## 构造函数
| 名称 | 描述 |
| :- | :- |
| PdfSaveOptions() | 初始化 PdfSaveOptions 类的新实例 |
## 属性
| 名称 | 描述 |
| :- | :- |
| warning_handler | 回调用于处理生成的任何警告。 <br/>            WarningHandler 返回 ReturnAction 枚举项，指定为 Continue 或 Abort。 <br/>            Continue 是默认操作，保存操作将继续，但用户也可以返回 Abort，此时保存操作应停止。 |
| save_format | 数据保存的格式。 |
| close_response | 获取或设置布尔值，指示在文档保存到响应后是否关闭 Response 对象。 |
| temp_path | 临时文件的路径。 |
| default_font_name | 默认使用的字体名称，用于计算机上缺失的字体。<br/>            当保存为 PDF 的文档包含在文档本身和设备上不可用的字体时，API 会将这些字体替换为默认字体（如果在设备上找到带有 [default_font_name](/pdf/python-net/aspose.pdf/pdfsaveoptions/) 的字体）。 |

### 另请参阅

* namespace [aspose.pdf](/pdf/python-net/aspose.pdf/)
* assembly [Aspose.PDF](/pdf/python-net/)

