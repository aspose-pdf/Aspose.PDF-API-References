---
title: "类 BaseListQueryParameters"
second_title: "Aspose.PDF for .NET API 参考"
description: "Aspose.Pdf.AI.BaseListQueryParameters 类。列出对象的基础查询参数"
type: docs
weight: 160
url: /zh/net/aspose.pdf.ai/baselistqueryparameters/
---
## BaseListQueryParameters class

列出对象的基础查询参数。

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
| [After](../../aspose.pdf.ai/baselistqueryparameters/after/) { get; set; } | 获取或设置用于分页的游标。after 是定义您在列表中位置的对象 ID。例如，如果您发出列表请求并收到 100 个对象，最后一个为 obj_foo，则后续调用可以包含 after=obj_foo 以获取列表的下一页。 |
| [Before](../../aspose.pdf.ai/baselistqueryparameters/before/) { get; set; } | 获取或设置用于分页的游标。before 是定义您在列表中位置的对象 ID。例如，如果您发出列表请求并收到 100 个对象，最后一个为 obj_foo，则后续调用可以包含 before=obj_foo 以获取列表的上一页。 |
| [Limit](../../aspose.pdf.ai/baselistqueryparameters/limit/) { get; set; } | 获取或设置返回的对象数量上限。限制范围为 1 到 100，默认值为 20。 |
| [Order](../../aspose.pdf.ai/baselistqueryparameters/order/) { get; set; } | 获取或设置对象 created_at 时间戳的排序顺序。asc 表示升序，desc 表示降序。 |

### 另请参见

* namespace [Aspose.Pdf.AI](../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../)


