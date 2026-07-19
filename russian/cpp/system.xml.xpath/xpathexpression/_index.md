---
title: "Класс System::Xml::XPath::XPathExpression"
linktitle: "XPathExpression"
second_title: "Справочник API Aspose.PDF для C++"
description: "Класс System::Xml::XPath::XPathExpression. Предоставляет типизированный класс, представляющий скомпилированное XPath-выражение в C++."
type: docs
weight: 300
url: /ru/cpp/system.xml.xpath/xpathexpression/
---
## XPathExpression class


Предоставляет типизированный класс, представляющий скомпилированное выражение [XPath](../).

```cpp
class XPathExpression : public System::Object
```

## Методы

| Метод | Описание |
| --- | --- |
| virtual [AddSort](./addsort/)(SharedPtr\<Object\>, SharedPtr\<Collections::Generic::IComparer\<SharedPtr\<Object\>\>\>) | При переопределении в производном классе сортирует узлы, выбранные выражением [XPath](../), в соответствии с указанным объектом IComparer. |
| virtual [AddSort](./addsort/)(SharedPtr\<Object\>, XmlSortOrder, XmlCaseOrder, String, XmlDataType) | При переопределении в производном классе сортирует узлы, выбранные выражением [XPath](../), в соответствии с переданными параметрами. |
| virtual [Clone](./clone/)() | При переопределении в производном классе возвращает клон этого [XPathExpression](./). |
| static [Compile](./compile/)(const String\&) | Компилирует указанное выражение [XPath](../) и возвращает объект [XPathExpression](./), представляющий выражение [XPath](../). |
| static [Compile](./compile/)(const String\&, const SharedPtr\<IXmlNamespaceResolver\>\&) | Компилирует указанное выражение [XPath](../) с объектом [IXmlNamespaceResolver](../../system.xml/ixmlnamespaceresolver/), указанным для разрешения пространств имён, и возвращает объект [XPathExpression](./), представляющий выражение [XPath](../). |
| virtual [get_Expression](./get_expression/)() | При переопределении в производном классе получает **string** представление [XPathExpression](./). |
| virtual [get_ReturnType](./get_returntype/)() | При переопределении в производном классе получает тип результата выражения [XPath](../). |
| virtual [SetContext](./setcontext/)(SharedPtr\<XmlNamespaceManager\>) | При переопределении в производном классе указывает объект [XmlNamespaceManager](../../system.xml/xmlnamespacemanager/), используемый для разрешения пространств имён. |
| virtual [SetContext](./setcontext/)(SharedPtr\<IXmlNamespaceResolver\>) | При переопределении в производном классе указывает объект [IXmlNamespaceResolver](../../system.xml/ixmlnamespaceresolver/), используемый для разрешения пространств имён. |
## Typedefs

| Типовое определение | Описание |
| --- | --- |
| [Ptr](./ptr/) | Псевдоним для shared pointer к экземпляру этого класса. |
## См. также

* Class [Object](../../system/object/)
* Namespace [System::Xml::XPath](../)
* Library [Aspose.PDF for C++](../../)
