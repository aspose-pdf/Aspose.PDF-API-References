---
title: "Класс Aspose::Pdf::XmpPdfAExtensionValueType"
linktitle: "XmpPdfAExtensionValueType"
second_title: "Справочник API Aspose.PDF для C++"
description: "Класс Aspose::Pdf::XmpPdfAExtensionValueType. Схема PDF/A ValueType требуется для всех типов значений свойств, которые не определены в спецификации XMP 2004, т.е. для типов значений, не входящих в следующий список: в C++."
type: docs
weight: 20800
url: /ru/cpp/aspose.pdf/xmppdfaextensionvaluetype/
---
## XmpPdfAExtensionValueType class


Схема PDF/A ValueType требуется для всех типов значений свойств, не определённых в спецификации XMP 2004, то есть для типов значений, не входящих в следующий список:

```cpp
class XmpPdfAExtensionValueType : public Aspose::Pdf::XmpPdfAExtensionObject
```

## Методы

| Метод | Описание |
| --- | --- |
| [Add](./add/)(const System::SharedPtr\<XmpPdfAExtensionField\>\&) | Добавить новое поле. |
| [AddRange](./addrange/)(const System::ArrayPtr\<System::SharedPtr\<XmpPdfAExtensionField\>\>\&) | Добавляет диапазон полей. |
| [Clear](./clear/)() | Очищает все поля. |
| [get_Fields](./get_fields/)() const | Получает список полей. |
| [get_NamespaceUri](./get_namespaceuri/)() const | Возвращает URI пространства имён. |
| [get_Prefix](./get_prefix/)() const | Возвращает префикс. |
| [get_Type](./get_type/)() const | Получает тип значения. |
| [GetXml](./getxml/)(System::SharedPtr\<System::Xml::XmlDocument\>) override | Возвращает список XML‑элементов, представляющих тип значения в XML‑дереве. |
| [Remove](./remove/)(const System::SharedPtr\<XmpPdfAExtensionField\>\&) | Удаляет поле из списка полей. |
| [XmpPdfAExtensionValueType](./xmppdfaextensionvaluetype/)(const System::String\&, const System::String\&, const System::String\&, const System::String\&) | Инициализирует новый объект. |
## Примечания


* Array types (these are container types which may contain one or more fields): Alt, Bag, Seq
* Basic value types: Boolean, (open and closed) Choice, Date, Dimensions, Integer, Lang Alt, Locale, MIMEType, ProperName, Real, [Text](../../aspose.pdf.text/), Thumbnail, URI, URL, XPath
* Media Management value types: AgentName, RenditionClass, ResourceEvent, ResourceRef, Version
* Basic Job/Workflow value type: Job
* EXIF schema value types: Flash, CFAPattern, DeviceSettings, GPSCoordinate, OECF/SFR, Rational Schema namespace URI: [http://www.aiim.org/pdfa/ns/type#](http://www.aiim.org/pdfa/ns/type#) Required schema namespace prefix: pdfaType


## См. также

* Class [XmpPdfAExtensionObject](../xmppdfaextensionobject/)
* Namespace [Aspose::Pdf](../)
* Library [Aspose.PDF for C++](../../)
