---
title: "SvgSaveOptions"
second_title: "Aspose.PDF for Python via .NET API 参考"
description: "导出为 SVG 格式的保存选项。"
type: docs
weight: 1460
url: /zh/python-net/aspose.pdf/svgsaveoptions/
---

## SvgSaveOptions class

导出为 SVG 格式的保存选项。

SvgSaveOptions 类型公开以下成员:
## 构造函数
| 名称 | 描述 |
| :- | :- |
| SvgSaveOptions() | 初始化 SvgSaveOptions 类的新实例 |
## 属性
| 名称 | 描述 |
| :- | :- |
| warning_handler | 回调用于处理生成的任何警告。 <br/>            WarningHandler 返回 ReturnAction 枚举项，指定为 Continue 或 Abort。 <br/>            Continue 是默认操作，保存操作将继续，但用户也可以返回 Abort，此时保存操作应停止。 |
| save_format | 数据保存的格式。 |
| close_response | 获取或设置布尔值，指示在文档保存到响应后是否关闭 Response 对象。 |
| extract_ocr_sublayer_only | None |
| try_merge_adjacent_same_background_images | None |
| treat_target_file_name_as_directory | 此选项定义是否将创建目标目录<br/>（如果尚不存在）其名称与请求的输出文件相同<br/>而不是直接使用请求的输出文件本身。<br/>这样，目录将包含所有页面的输出 SVG 图像（如下面所述）。<br/>如果选择否，则除第一页之外的页面输出文件将直接在请求的目录中创建<br/>作为主输出文件，但文件名会带有后缀 _[2...n]，该后缀由页码决定，例如如果您将输出文件定义为 "C:\\AsposeTests\\output.svg"<br/>且输出将包含多个页面的 svg 文件，<br/>那么页面文件也会在目录 "C:\\AsposeTests\\" 中创建，名称分别为 'output.svg'、'output_2.svg'、'output_3.svg' 等。 |
| compress_output_to_zip_archive | 指定输出是否将创建为单个 zip 压缩包。<br/>请参阅对 'TreatTargetFileNameAsDirectory' 选项的注释，以查看多页源文档的页面 svg 文件的命名规则，这些规则同样适用于压缩的输出文件集合。 |
| scale_to_pixels | 指定是否将输出文档从排版点（points）缩放为像素。 |

### 另请参阅

* namespace [aspose.pdf](/pdf/python-net/aspose.pdf/)
* assembly [Aspose.PDF](/pdf/python-net/)

