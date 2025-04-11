---
title: Class VectorStoreFileBatchFileListQueryParameters
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.AI.VectorStoreFileBatchFileListQueryParameters 类。用于列出向量存储文件批次文件的查询参数对象
type: docs
weight: 1290
url: /zh/net/aspose.pdf.ai/vectorstorefilebatchfilelistqueryparameters/
---
## VectorStoreFileBatchFileListQueryParameters 类

用于列出向量存储文件批次文件的查询参数对象。

```csharp
public class VectorStoreFileBatchFileListQueryParameters : BaseListQueryParameters, IQueryParameters
```

## 构造函数

| 名称 | 描述 |
| --- | --- |
| [VectorStoreFileBatchFileListQueryParameters](vectorstorefilebatchfilelistqueryparameters/)() | 默认构造函数。 |

## 属性

| 名称 | 描述 |
| --- | --- |
| [After](../../aspose.pdf.ai/baselistqueryparameters/after/) { get; set; } | 获取或设置用于分页的游标。 after 是一个对象 ID，定义您在列表中的位置。例如，如果您发出列表请求并接收到 100 个对象，以 obj_foo 结束，则您的后续调用可以包含 after=obj_foo 以获取列表的下一页。 |
| [Before](../../aspose.pdf.ai/baselistqueryparameters/before/) { get; set; } | 获取或设置用于分页的游标。 before 是一个对象 ID，定义您在列表中的位置。例如，如果您发出列表请求并接收到 100 个对象，以 obj_foo 结束，则您的后续调用可以包含 before=obj_foo 以获取列表的上一页。 |
| [Filter](../../aspose.pdf.ai/vectorstorefilebatchfilelistqueryparameters/filter/) { get; set; } | 获取或设置按文件状态过滤的条件。可以是 in_progress、completed、failed、cancelled 之一。 |
| [Limit](../../aspose.pdf.ai/baselistqueryparameters/limit/) { get; set; } | 获取或设置要返回的对象数量限制。限制可以在 1 到 100 之间，默认值为 20。 |
| [Order](../../aspose.pdf.ai/baselistqueryparameters/order/) { get; set; } | 获取或设置按对象的 created_at 时间戳排序的顺序。asc 表示升序，desc 表示降序。 |

## 方法

| 名称 | 描述 |
| --- | --- |
| [GetQueryParameters](../../aspose.pdf.ai/vectorstorefilebatchfilelistqueryparameters/getqueryparameters/)() | 获取用于列出存储文件批次文件的查询参数。 |

### 另请参阅

* 类 [BaseListQueryParameters](../baselistqueryparameters/)
* 接口 [IQueryParameters](../iqueryparameters/)
* 命名空间 [Aspose.Pdf.AI](../../aspose.pdf.ai/)
* 程序集 [Aspose.PDF](../../)