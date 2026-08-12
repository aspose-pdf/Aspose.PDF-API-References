---
title: "System::Xml::Xsl::IXsltContextVariable::Evaluate method"
linktitle: "Evaluate"
second_title: "Справочник API Aspose.PDF для C++"
description: "System::Xml::Xsl::IXsltContextVariable::Evaluate method. Оценивает переменную во время выполнения и возвращает объект, представляющий значение переменной в C++."
type: docs
weight: 100
url: /ru/cpp/system.xml.xsl/ixsltcontextvariable/evaluate/
---
## IXsltContextVariable::Evaluate method


Выполняет оценку переменной во время выполнения и возвращает объект, представляющий значение переменной.

```cpp
virtual SharedPtr<Object> System::Xml::Xsl::IXsltContextVariable::Evaluate(SharedPtr<XsltContext> xsltContext)=0
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| xsltContext | SharedPtr\<XsltContext\> | Экземпляр [XsltContext](../../xsltcontext/), представляющий контекст выполнения переменной. |

### ReturnValue

Экземпляр [Object](../../../system/object/), представляющий значение переменной. Возможные типы возвращаемого значения включают число, строку, [Boolean](../../../system/boolean/), фрагмент документа или набор узлов.

## См. также

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Object](../../../system/object/)
* Class [XsltContext](../../xsltcontext/)
* Class [IXsltContextVariable](../)
* Namespace [System::Xml::Xsl](../../)
* Library [Aspose.PDF for C++](../../../)
