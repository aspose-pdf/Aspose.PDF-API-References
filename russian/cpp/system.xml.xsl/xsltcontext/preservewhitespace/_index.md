---
title: "Метод System::Xml::Xsl::XsltContext::PreserveWhitespace"
linktitle: "PreserveWhitespace"
second_title: "Справочник API Aspose.PDF для C++"
description: "Метод System::Xml::Xsl::XsltContext::PreserveWhitespace. При переопределении в производном классе определяет, следует ли сохранять узлы пробельных символов или удалять их для данного контекста в C++."
type: docs
weight: 300
url: /ru/cpp/system.xml.xsl/xsltcontext/preservewhitespace/
---
## XsltContext::PreserveWhitespace method


При переопределении в производном классе определяет, следует ли сохранять узлы пробельных символов или удалять их в данном контексте.

```cpp
virtual bool System::Xml::Xsl::XsltContext::PreserveWhitespace(SharedPtr<System::Xml::XPath::XPathNavigator> node)=0
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| узел | SharedPtr\<System::Xml::XPath::XPathNavigator\> | Узел пробельных символов, который должен быть сохранён или удалён в текущем контексте. |

### ReturnValue

**true** if the white space is to be preserved; **false** if the white space is to be stripped.

## См. также

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [XPathNavigator](../../../system.xml.xpath/xpathnavigator/)
* Class [XsltContext](../)
* Namespace [System::Xml::Xsl](../../)
* Library [Aspose.PDF for C++](../../../)
