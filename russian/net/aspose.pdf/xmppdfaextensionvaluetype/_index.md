---
title: "Класс XmpPdfAExtensionValueType"
second_title: "Справочник API Aspose.PDF для .NET"
description: "Aspose.Pdf.XmpPdfAExtensionValueType класс. Схема PDF/A ValueType требуется для всех типов значений свойств, которые не определены в спецификации XMP 2004, т.е. для типов значений, не входящих в следующий список: типы массивов — это контейнерные типы, которые могут содержать одно или несколько полей Alt, Bag, Seq; базовые типы значений Boolean, open и closed, Choice, Date, Dimensions, Integer, Lang, Alt, Locale, MIMEType, ProperName, Real, Text, Thumbnail, URI, URL, XPath; типы значений управления медиа AgentName, RenditionClass, ResourceEvent, ResourceRef, Version; базовый тип значения задачи/рабочего процесса Job; типы значений схемы EXIF Flash, CFAPattern, DeviceSettings, GPSCoordinate, OECF/SFR, Rational; пространство имён схемы URI http//www.aiim.org/pdfa/ns/type; обязательный префикс пространства имён схемы pdfaType."
type: docs
weight: 11680
url: /ru/net/aspose.pdf/xmppdfaextensionvaluetype/
---
## XmpPdfAExtensionValueType class

Схема PDF/A ValueType требуется для всех типов значений свойств, которые не определены в спецификации XMP 2004, то есть для типов значений, не входящих в следующий список: - Типы массивов (это типы‑контейнеры, которые могут содержать одно или несколько полей): Alt, Bag, Seq - Базовые типы значений: Boolean, (открытый и закрытый) Choice, Date, Dimensions, Integer, Lang Alt, Locale, MIMEType, ProperName, Real, Text, Thumbnail, URI, URL, XPath - Типы значений управления медиа: AgentName, RenditionClass, ResourceEvent, ResourceRef, Version - Базовый тип значения Job/Workflow: Job - Типы значений схемы EXIF: Flash, CFAPattern, DeviceSettings, GPSCoordinate, OECF/SFR, Rational URI пространства имён схемы: http://www.aiim.org/pdfa/ns/type# Требуемый префикс пространства имён схемы: pdfaType.

```csharp
public sealed class XmpPdfAExtensionValueType : XmpPdfAExtensionObject
```

## Конструкторы

| Имя | Описание |
| --- | --- |
| [XmpPdfAExtensionValueType](xmppdfaextensionvaluetype/)(string, string, string, string) | Инициализирует новый объект. |

## Свойства

| Имя | Описание |
| --- | --- |
| [Description](../../aspose.pdf/xmppdfaextensionobject/description/) { get; } | Получает описание. |
| [Fields](../../aspose.pdf/xmppdfaextensionvaluetype/fields/) { get; } | Получает список полей. |
| [NamespaceUri](../../aspose.pdf/xmppdfaextensionvaluetype/namespaceuri/) { get; } | Получает URI пространства имен. |
| [Prefix](../../aspose.pdf/xmppdfaextensionvaluetype/prefix/) { get; } | Получает префикс. |
| [Type](../../aspose.pdf/xmppdfaextensionvaluetype/type/) { get; } | Получает тип значения. |
| [Value](../../aspose.pdf/xmppdfaextensionobject/value/) { get; set; } | Получает или задает значение. |

## Методы

| Имя | Описание |
| --- | --- |
| [Add](../../aspose.pdf/xmppdfaextensionvaluetype/add/)(XmpPdfAExtensionField) | Добавить новое поле. |
| [AddRange](../../aspose.pdf/xmppdfaextensionvaluetype/addrange/)(XmpPdfAExtensionField[]) | Добавляет диапазон полей. |
| [Clear](../../aspose.pdf/xmppdfaextensionvaluetype/clear/)() | Очищает все поля. |
| override [GetXml](../../aspose.pdf/xmppdfaextensionvaluetype/getxml/)(XmlDocument) | Возвращает список элементов xml, представляющих тип значения в дереве xml. |
| [Remove](../../aspose.pdf/xmppdfaextensionvaluetype/remove/)(XmpPdfAExtensionField) | Удаляет поле из списка полей. |

### См. также

* class [XmpPdfAExtensionObject](../xmppdfaextensionobject/)
* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)


