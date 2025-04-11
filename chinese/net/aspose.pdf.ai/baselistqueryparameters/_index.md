---
title: Class BaseListQueryParameters
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.AI.BaseListQueryParameters 类。列出对象的基本查询参数
type: docs
weight: 160
url: /zh/net/aspose.pdf.ai/baselistqueryparameters/
---
## BaseListQueryParameters 类

列出对象的基本查询参数。

```csharp
public class BaseListQueryParameters
```

## 构造函数

| 名称 | 描述 |
| --- | --- |
| [BaseListQueryParameters](baselistqueryparameters/)() | 默认构造函数。 |

## 属性

| 名称 | 描述 |
| --- | --- |
| [After](../../aspose.pdf.ai/baselistqueryparameters/after/) { get; set; } | 获取或设置用于分页的游标。 after 是一个对象 ID，定义您在列表中的位置。例如，如果您发出列表请求并接收到 100 个对象，以 obj_foo 结尾，则您的后续调用可以包括 after=obj_foo 以获取列表的下一页。 |
| [Before](../../aspose.pdf.ai/baselistqueryparameters/before/) { get; set; } | 获取或设置用于分页的游标。 before 是一个对象 ID，定义您在列表中的位置。例如，如果您发出列表请求并接收到 100 个对象，以 obj_foo 结尾，则您的后续调用可以包括 before=obj_foo 以获取列表的上一页。 |
| [Limit](../../aspose.pdf.ai/baselistqueryparameters/limit/) { get; set; } | 获取或设置要返回的对象数量的限制。 Limit 可以在 1 到 100 之间，默认值为 20。 |
| [Order](../../aspose.pdf.ai/baselistqueryparameters/order/) { get; set; } | 获取或设置按对象的 created_at 时间戳排序的顺序。 asc 表示升序，desc 表示降序。 |

### 另请参阅

* 命名空间 [Aspose.Pdf.AI](../../aspose.pdf.ai/)
* 程序集 [Aspose.PDF](../../)