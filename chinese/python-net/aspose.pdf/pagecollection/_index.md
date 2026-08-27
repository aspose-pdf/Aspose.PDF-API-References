---
title: "PageCollection"
second_title: "Aspose.PDF for Python via .NET API 参考"
description: "PDF 文档页面的集合。"
type: docs
weight: 1100
url: /zh/python-net/aspose.pdf/pagecollection/
---

## PageCollection class

PDF 文档页面的集合。

PageCollection 类型公开以下成员：
## 属性
| 名称 | 描述 |
| :- | :- |
| is_synchronized | 如果对象已同步则返回 true。 |
| sync_root | 获取集合的同步对象。 |
## Indexer
| 名称 | 描述 |
| :- | :- |
| [index] | 通过索引获取页面。 |
## 方法
| 名称 | 描述 |
| :- | :- |
| add(entity) | 向集合添加页面。 |
| add() | 向集合添加页面。 |
| add(pages) | 将列表中的所有页面添加到集合。 |
| add(pages) | 将数组中的所有页面添加到集合。 |
| delete(index) | 删除指定的页面。 |
| delete() | 删除指定的页面。 |
| delete(pages) | 删除数组中指定编号的页面。 |
| accept(visitor) | 接受 [AnnotationSelector](/pdf/python-net/aspose.pdf.annotations/annotationselector/) 访问器对象，提供处理注释的功能。 |
| accept(visitor) | 接受 [ImagePlacementAbsorber](/pdf/python-net/aspose.pdf/imageplacementabsorber/) 访问器对象，提供处理图像放置对象的功能。 |
| accept(visitor) | 接受 [TextFragmentAbsorber](/pdf/python-net/aspose.pdf.text/textfragmentabsorber/) 访问器对象，提供处理文本对象的功能。 |
| accept(visitor) | 接受 [TextAbsorber](/pdf/python-net/aspose.pdf.text/textabsorber/) 访问器对象，提供处理文本对象的功能。 |
| insert(page_number) | 在指定位置向集合插入空页。 |
| insert(page_number, entity) | 在指定位置向集合插入空页。 |
| insert(page_number, pages) | 将集合中的页面插入文档。 |
| insert(page_number, pages) | 将数组中的页面插入文档。 |
| index_of(entity) | 返回指定页面的索引。 |
| flatten() | 删除页面上所有字段，并用其值替代。 |
| free_memory() | 清除缓存数据 |

### 另请参阅

* namespace [aspose.pdf](/pdf/python-net/aspose.pdf/)
* assembly [Aspose.PDF](/pdf/python-net/)

