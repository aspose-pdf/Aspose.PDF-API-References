---
title: "权限"
second_title: "Aspose.PDF for Python via .NET API 参考"
description: "此枚举表示用户对 PDF 的权限。"
type: docs
weight: 6560
url: /zh/python-net/aspose.pdf/permissions/
---

## Permissions enumeration

此枚举表示用户对 PDF 的权限。

## Members
| Member name | 描述 |
| :- | :- |
| PRINT_DOCUMENT | (Security handlers of revision 2) 打印文档。<br/>            (Security handlers of revision 3 or greater) 打印文档 <br/>            （可能不是最高质量水平，<br/>            取决于是否也设置了 [PRINTING_QUALITY](/pdf/python-net/aspose.pdf/permissions/)）。 |
| MODIFY_CONTENT | 通过除受 [MODIFY_TEXT_ANNOTATIONS](/pdf/python-net/aspose.pdf/permissions/) 控制的操作、<br/>            [FILL_FORM](/pdf/python-net/aspose.pdf/permissions/) 和 11 之外的操作来修改文档内容。 |
| EXTRACT_CONTENT | (Security handlers of revision 2) 复制或以其他方式提取<br/>            文档中的文本和图形，包括提取<br/>            文本和图形（以支持残障用户的可访问性<br/>            或用于其他目的）。<br/>            (Security handlers of revision 3 or greater) 通过除受 [EXTRACT_CONTENT_WITH_DISABILITIES](/pdf/python-net/aspose.pdf/permissions/) 控制的操作之外的操作，复制或以其他方式提取文档中的文本和图形。 |
| MODIFY_TEXT_ANNOTATIONS | 添加或修改文本批注，填写交互式表单字段，<br/>            并且如果同时设置了 [MODIFY_CONTENT](/pdf/python-net/aspose.pdf/permissions/)，则创建或修改交互式表单字段（包括签名字段）。 |
| FILL_FORM | (Security handlers of revision 3 or greater) 填写已有的<br/>            交互式表单字段（包括签名字段），即使 [MODIFY_TEXT_ANNOTATIONS](/pdf/python-net/aspose.pdf/permissions/) 未被设置。 |
| EXTRACT_CONTENT_WITH_DISABILITIES | (Security handlers of revision 3 or greater) 提取文本和<br/>            图形（以支持残障用户的可访问性<br/>            或用于其他目的）。 |
| ASSEMBLE_DOCUMENT | (Security handlers of revision 3 or greater) 组装文档<br/>            （插入、旋转或删除页面并创建书签或缩略图<br/>            图像），即使 [MODIFY_CONTENT](/pdf/python-net/aspose.pdf/permissions/) 未被设置。 |
| PRINTING_QUALITY | (Security handlers of revision 3 or greater) 将文档打印为<br/>            可生成 PDF 内容忠实数字副本的表示形式。当此位未设置（且第 3 位已设置）时，<br/>            打印仅限于外观的低级表示，<br/>            可能质量下降。 |

### 另请参阅

* namespace [aspose.pdf](/pdf/python-net/aspose.pdf/)
* assembly [Aspose.PDF](/pdf/python-net/)

