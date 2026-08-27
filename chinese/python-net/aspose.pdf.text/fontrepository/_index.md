---
title: "FontRepository"
second_title: "Aspose.PDF for Python via .NET API 参考"
description: "执行字体搜索。搜索系统已安装的字体和标准 PDF 字体。<br/>             还提供打开自定义字体的功能。"
type: docs
weight: 130
url: /zh/python-net/aspose.pdf.text/fontrepository/
---

## FontRepository class

执行字体搜索。搜索系统已安装的字体和标准 PDF 字体。<br/>             还提供打开自定义字体的功能。

FontRepository 类型公开以下成员：
## 构造函数
| 名称 | 描述 |
| :- | :- |
| FontRepository() | 初始化 FontRepository 类的新实例 |
## 属性
| 名称 | 描述 |
| :- | :- |
| substitutions | 获取字体替代策略集合。 |
| sources | 获取字体来源集合。 |
## 方法
| 名称 | 描述 |
| :- | :- |
| find_font(font_name) | 搜索并返回具有指定字体名称的字体。 |
| find_font(font_name, ignore_case) | 搜索并返回具有指定字体名称的字体，忽略或遵守大小写敏感性。 |
| find_font(font_family_name, stl) | 搜索并返回具有指定字体族名称和字体样式的字体。 |
| find_font(font_family_name, stl, ignore_case) | 搜索并返回具有指定字体族名称和字体样式的字体 <br/>             忽略或遵守大小写敏感性。 |
| open_font(font_stream, font_type) | 使用指定的字体流打开字体。 |
| open_font(font_file_path) | 使用指定的字体文件路径打开字体。 |
| open_font(font_file_path, metrics_file_path) | 使用指定的字体文件路径打开字体。 |
| load_fonts() | 加载系统已安装的字体和标准 Pdf 字体。此方法旨在加快字体加载过程。<br/>默认情况下，字体在首次请求任何字体时加载。使用此方法会在打开任何 Pdf 文档之前立即加载系统和标准 Pdf 字体。 |
| reload_fonts() | 重新加载属性 [sources](/pdf/python-net/aspose.pdf.text/fontrepository/) 指定的所有字体。 |

### 另请参阅

* namespace [aspose.pdf.text](/pdf/python-net/aspose.pdf.text/)
* assembly [Aspose.PDF](/pdf/python-net/)

