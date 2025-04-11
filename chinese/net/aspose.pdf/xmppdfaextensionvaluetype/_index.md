---
title: Class XmpPdfAExtensionValueType
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.XmpPdfAExtensionValueType 类。PDF/A ValueType 架构是所有未在 XMP 2004 规范中定义的属性值类型所必需的，即对于以下列表之外的值类型： - 数组类型（这些是可能包含一个或多个字段的容器类型）：Alt, Bag, Seq - 基本值类型：Boolean,（开放和关闭）Choice, Date, Dimensions, Integer, Lang Alt, Locale, MIMEType, ProperName, Real, Text, Thumbnail, URI, URL, XPath - 媒体管理值类型：AgentName, RenditionClass, ResourceEvent, ResourceRef, Version - 基本作业/工作流值类型：Job - EXIF 架构值类型：Flash, CFAPattern, DeviceSettings, GPSCoordinate, OECF/SFR, Rational 架构命名空间 URI：http//www.aiim.org/pdfa/ns/type 必需的架构命名空间前缀：pdfaType
type: docs
weight: 11490
url: /zh/net/aspose.pdf/xmppdfaextensionvaluetype/
---
## XmpPdfAExtensionValueType 类

PDF/A ValueType 架构是所有未在 XMP 2004 规范中定义的属性值类型所必需的，即对于以下列表之外的值类型： - 数组类型（这些是可能包含一个或多个字段的容器类型）：Alt, Bag, Seq - 基本值类型：Boolean,（开放和关闭）Choice, Date, Dimensions, Integer, Lang Alt, Locale, MIMEType, ProperName, Real, Text, Thumbnail, URI, URL, XPath - 媒体管理值类型：AgentName, RenditionClass, ResourceEvent, ResourceRef, Version - 基本作业/工作流值类型：Job - EXIF 架构值类型：Flash, CFAPattern, DeviceSettings, GPSCoordinate, OECF/SFR, Rational 架构命名空间 URI：http://www.aiim.org/pdfa/ns/type# 必需的架构命名空间前缀：pdfaType

```csharp
public sealed class XmpPdfAExtensionValueType : XmpPdfAExtensionObject
```

## 构造函数

| 名称 | 描述 |
| --- | --- |
| [XmpPdfAExtensionValueType](xmppdfaextensionvaluetype/)(string, string, string, string) | 初始化新对象。 |

## 属性

| 名称 | 描述 |
| --- | --- |
| [Description](../../aspose.pdf/xmppdfaextensionobject/description/) { get; } | 获取描述。 |
| [Fields](../../aspose.pdf/xmppdfaextensionvaluetype/fields/) { get; } | 获取字段列表。 |
| [NamespaceUri](../../aspose.pdf/xmppdfaextensionvaluetype/namespaceuri/) { get; } | 获取命名空间 URI。 |
| [Prefix](../../aspose.pdf/xmppdfaextensionvaluetype/prefix/) { get; } | 获取前缀。 |
| [Type](../../aspose.pdf/xmppdfaextensionvaluetype/type/) { get; } | 获取值类型。 |
| [Value](../../aspose.pdf/xmppdfaextensionobject/value/) { get; set; } | 获取或设置值。 |

## 方法

| 名称 | 描述 |
| --- | --- |
| [Add](../../aspose.pdf/xmppdfaextensionvaluetype/add/)(XmpPdfAExtensionField) | 添加新字段。 |
| [AddRange](../../aspose.pdf/xmppdfaextensionvaluetype/addrange/)(XmpPdfAExtensionField[]) | 添加字段范围。 |
| [Clear](../../aspose.pdf/xmppdfaextensionvaluetype/clear/)() | 清除所有字段。 |
| override [GetXml](../../aspose.pdf/xmppdfaextensionvaluetype/getxml/)(XmlDocument) | 返回表示 XML 树中值类型的 XML 元素列表。 |
| [Remove](../../aspose.pdf/xmppdfaextensionvaluetype/remove/)(XmpPdfAExtensionField) | 从字段列表中移除字段。 |

### 另请参阅

* 类 [XmpPdfAExtensionObject](../xmppdfaextensionobject/)
* 命名空间 [Aspose.Pdf](../../aspose.pdf/)
* 程序集 [Aspose.PDF](../../)