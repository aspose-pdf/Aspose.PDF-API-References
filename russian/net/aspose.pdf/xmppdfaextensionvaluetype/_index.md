---
title: Class XmpPdfAExtensionValueType
second_title: Aspose.PDF for .NET API Reference
description: Класс Aspose.Pdf.XmpPdfAExtensionValueType. Схема ValueType PDF/A необходима для всех типов значений свойств, которые не определены в спецификации XMP 2004, т.е. для типов значений вне следующего списка - Массивы Alt, Bag, Seq - Основные типы значений Boolean, Choice, Date, Dimensions, Integer, Lang Alt, Locale, MIMEType, ProperName, Real, Text, Thumbnail, URI, URL, XPath - Типы значений управления медиа AgentName, RenditionClass, ResourceEvent, ResourceRef, Version - Основной тип значения задания/рабочего процесса Job - Типы значений схемы EXIF Flash, CFAPattern, DeviceSettings, GPSCoordinate, OECF/SFR, Rational Ссылка на пространство имен схемы http//www.aiim.org/pdfa/ns/type Обязательный префикс пространства имен схемы pdfaType
type: docs
weight: 11490
url: /ru/net/aspose.pdf/xmppdfaextensionvaluetype/
---
## Класс XmpPdfAExtensionValueType

Схема ValueType PDF/A необходима для всех типов значений свойств, которые не определены в спецификации XMP 2004, т.е. для типов значений вне следующего списка: - Массивы (это контейнерные типы, которые могут содержать одно или несколько полей): Alt, Bag, Seq - Основные типы значений: Boolean, (открытый и закрытый) Choice, Date, Dimensions, Integer, Lang Alt, Locale, MIMEType, ProperName, Real, Text, Thumbnail, URI, URL, XPath - Типы значений управления медиа: AgentName, RenditionClass, ResourceEvent, ResourceRef, Version - Основной тип значения задания/рабочего процесса: Job - Типы значений схемы EXIF: Flash, CFAPattern, DeviceSettings, GPSCoordinate, OECF/SFR, Rational Ссылка на пространство имен схемы: http://www.aiim.org/pdfa/ns/type# Обязательный префикс пространства имен схемы: pdfaType

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
| [Add](../../aspose.pdf/xmppdfaextensionvaluetype/add/)(XmpPdfAExtensionField) | Добавляет новое поле. |
| [AddRange](../../aspose.pdf/xmppdfaextensionvaluetype/addrange/)(XmpPdfAExtensionField[]) | Добавляет диапазон полей. |
| [Clear](../../aspose.pdf/xmppdfaextensionvaluetype/clear/)() | Очищает все поля. |
| override [GetXml](../../aspose.pdf/xmppdfaextensionvaluetype/getxml/)(XmlDocument) | Возвращает список xml-элементов, представляющих тип значения в xml-дереве. |
| [Remove](../../aspose.pdf/xmppdfaextensionvaluetype/remove/)(XmpPdfAExtensionField) | Удаляет поле из списка полей. |

### См. также

* класс [XmpPdfAExtensionObject](../xmppdfaextensionobject/)
* пространство имен [Aspose.Pdf](../../aspose.pdf/)
* сборка [Aspose.PDF](../../)