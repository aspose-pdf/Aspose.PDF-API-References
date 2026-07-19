---
title: "System::Xml::Xsl::IXsltContextVariable class"
linktitle: "IXsltContextVariable"
second_title: "Справочник API Aspose.PDF для C++"
description: "System::Xml::Xsl::IXsltContextVariable class. Предоставляет интерфейс к заданной переменной, определённой в таблице стилей во время выполнения в C++."
type: docs
weight: 200
url: /ru/cpp/system.xml.xsl/ixsltcontextvariable/
---
## IXsltContextVariable class


Предоставляет интерфейс к заданной переменной, определённой в таблице стилей во время выполнения.

```cpp
class IXsltContextVariable : public virtual System::Object
```

## Методы

| Метод | Описание |
| --- | --- |
| virtual [Evaluate](./evaluate/)(SharedPtr\<XsltContext\>) | Выполняет оценку переменной во время выполнения и возвращает объект, представляющий значение переменной. |
| virtual [get_IsLocal](./get_islocal/)() | Возвращает значение, указывающее, является ли переменная локальной. |
| virtual [get_IsParam](./get_isparam/)() | Возвращает значение, указывающее, является ли переменная параметром Extensible Stylesheet Language Transformations (XSLT). Это может быть параметром таблицы стилей или шаблона. |
| virtual [get_VariableType](./get_variabletype/)() | Возвращает XPathResultType, представляющий тип языка XML Path Language ([XPath](../../system.xml.xpath/)) переменной. |
## См. также

* Class [Object](../../system/object/)
* Namespace [System::Xml::Xsl](../)
* Library [Aspose.PDF for C++](../../)
