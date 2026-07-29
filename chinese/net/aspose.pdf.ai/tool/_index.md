---
title: "类 Tool"
second_title: "Aspose.PDF for .NET API 参考"
description: "Aspose.Pdf.AI.Tool 类。表示模型可以调用的工具。"
type: docs
weight: 1280
url: /zh/net/aspose.pdf.ai/tool/
---
## Tool class

表示模型可以调用的工具。

```csharp
public class Tool
```

## 构造函数

| 名称 | 描述 |
| --- | --- |
| [Tool](tool/#constructor)() | 初始化 `Tool` 类的新实例。 |
| [Tool](tool/#constructor_1)(Function) | 使用指定的函数初始化 `Tool` 类的新实例。 |
| [Tool](tool/#constructor_2)(string) | 使用指定的工具类型初始化 `Tool` 类的新实例。 |

## 属性

| 名称 | 描述 |
| --- | --- |
| static [CodeInterpreter](../../aspose.pdf.ai/tool/codeinterpreter/) { get; } | 获取表示代码解释器的工具实例。 |
| static [FileSearch](../../aspose.pdf.ai/tool/filesearch/) { get; } | 获取表示文件搜索工具的工具实例。 |
| [ToolFunction](../../aspose.pdf.ai/tool/toolfunction/) { get; set; } | 获取或设置模型可以调用的函数。 |
| [ToolType](../../aspose.pdf.ai/tool/tooltype/) { get; set; } | 获取或设置工具的类型。目前仅支持 function。 |

## 方法

| 名称 | 描述 |
| --- | --- |
| static [Function](../../aspose.pdf.ai/tool/function/)(Function) | 使用指定的函数创建一个新的工具实例。 |

### 另请参见

* namespace [Aspose.Pdf.AI](../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../)


