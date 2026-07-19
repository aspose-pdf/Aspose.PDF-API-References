---
title: "System::Xml::Xsl::XsltContext класс"
linktitle: "XsltContext"
second_title: "Справочник API Aspose.PDF для C++"
description: "System::Xml::Xsl::XsltContext класс. Инкапсулирует текущий контекст выполнения процессора Extensible Stylesheet Language for Transformations (XSLT), позволяя XML Path Language (XPath) разрешать функции, параметры и пространства имён внутри XPath‑выражений в C++."
type: docs
weight: 500
url: /ru/cpp/system.xml.xsl/xsltcontext/
---
## XsltContext class


Инкапсулирует текущий контекст выполнения процессора Extensible Stylesheet Language for Transformations (XSLT), позволяя XML Path Language ([XPath](../../system.xml.xpath/)) разрешать функции, параметры и пространства имён внутри выражений [XPath](../../system.xml.xpath/).

```cpp
class XsltContext : public System::Xml::XmlNamespaceManager
```

## Методы

| Метод | Описание |
| --- | --- |
| virtual [CompareDocument](./comparedocument/)(String, String) | При переопределении в производном классе сравнивает базовые Uniform Resource Identifiers (URIs) двух документов в зависимости от порядка их загрузки процессором XSLT (то есть классом [XslTransform](../xsltransform/)). |
| virtual [get_Whitespace](./get_whitespace/)() | При переопределении в производном классе получает значение, указывающее, следует ли включать узлы пробельных символов в вывод. |
| virtual [PreserveWhitespace](./preservewhitespace/)(SharedPtr\<System::Xml::XPath::XPathNavigator\>) | При переопределении в производном классе определяет, следует ли сохранять узлы пробельных символов или удалять их в данном контексте. |
| virtual [ResolveFunction](./resolvefunction/)(String, String, ArrayPtr\<System::Xml::XPath::XPathResultType\>) | При переопределении в производном классе разрешает ссылку на функцию и возвращает [IXsltContextFunction](../ixsltcontextfunction/), представляющий функцию. [IXsltContextFunction](../ixsltcontextfunction/) используется во время выполнения для получения возвращаемого значения функции. |
| virtual [ResolveVariable](./resolvevariable/)(String, String) | При переопределении в производном классе разрешает ссылку на переменную и возвращает [IXsltContextVariable](../ixsltcontextvariable/), представляющий переменную. |
## Typedefs

| Типовое определение | Описание |
| --- | --- |
| [Ptr](./ptr/) | Псевдоним для shared pointer к экземпляру этого класса. |
## См. также

* Class [XmlNamespaceManager](../../system.xml/xmlnamespacemanager/)
* Namespace [System::Xml::Xsl](../)
* Library [Aspose.PDF for C++](../../)
