---
title: "Метод System::Xml::Xsl::XsltContext::ResolveVariable"
linktitle: "ResolveVariable"
second_title: "Справочник API Aspose.PDF для C++"
description: "Метод System::Xml::Xsl::XsltContext::ResolveVariable. При переопределении в производном классе разрешает ссылку на переменную и возвращает IXsltContextVariable, представляющий переменную, в C++."
type: docs
weight: 500
url: /ru/cpp/system.xml.xsl/xsltcontext/resolvevariable/
---
## XsltContext::ResolveVariable method


При переопределении в производном классе разрешает ссылку на переменную и возвращает [IXsltContextVariable](../../ixsltcontextvariable/), представляющий переменную.

```cpp
virtual SharedPtr<IXsltContextVariable> System::Xml::Xsl::XsltContext::ResolveVariable(String prefix, String name)=0
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| prefix | String | Префикс переменной, как он появляется в выражении [XPath](../../../system.xml.xpath/). |
| имя | String | Имя переменной. |

### ReturnValue

Объект [IXsltContextVariable](../../ixsltcontextvariable/), представляющий переменную во время выполнения.

## См. также

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IXsltContextVariable](../../ixsltcontextvariable/)
* Class [String](../../../system/string/)
* Class [XsltContext](../)
* Namespace [System::Xml::Xsl](../../)
* Library [Aspose.PDF for C++](../../../)
