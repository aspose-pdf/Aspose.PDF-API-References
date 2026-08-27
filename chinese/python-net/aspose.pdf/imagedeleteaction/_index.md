---
title: "ImageDeleteAction"
second_title: "Aspose.PDF for Python via .NET API 参考"
description: "当图像从集合中移除时对图像对象执行的操作。如果图像对象被移除"
type: docs
weight: 6450
url: /zh/python-net/aspose.pdf/imagedeleteaction/
---

## ImageDeleteAction enumeration

当图像从集合中移除时对图像对象执行的操作。如果图像对象被移除

## Members
| Member name | 描述 |
| :- | :- |
| KEEP_CONTENTS | 图像将从集合中移除。如果页面内容包含对该图像的引用，则这些引用不会被移除。文档可能会变得无效。 |
| NONE | 图像将从集合和页面内容中移除，但图像对象不会被删除。文件大小不会减少。 |
| FORCE_DELETE | 图像将从集合中移除，图像对象也将从文档中移除。如果同一对象上存在其他引用，文档可能会损坏。 |
| CHECK | 仅当其他页面没有对该图像的引用时，图像才会从集合中移除并删除图像对象。这可能比 ForceDelete 选项需要更多时间。 |

### 另请参阅

* namespace [aspose.pdf](/pdf/python-net/aspose.pdf/)
* assembly [Aspose.PDF](/pdf/python-net/)

