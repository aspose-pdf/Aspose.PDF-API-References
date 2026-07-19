---
title: "System::Xml::Schema::XmlSchemaContentProcessing enum"
linktitle: "XmlSchemaContentProcessing"
second_title: "Справочник API Aspose.PDF для C++"
description: "System::Xml::Schema::XmlSchemaContentProcessing enum. Предоставляет информацию о режиме проверки замен элементов any и anyAttribute в C++."
type: docs
weight: 7300
url: /ru/cpp/system.xml.schema/xmlschemacontentprocessing/
---
## XmlSchemaContentProcessing enum


Предоставляет информацию о режиме проверки замен элементов **any** и **anyAttribute**.

```cpp
enum class XmlSchemaContentProcessing
```

### Значения

| Имя | Значение | Описание |
| --- | --- | --- |
| None | 0 | Элементы документа не проверяются. |
| Пропустить | 1 | Элементы документа должны состоять из корректного XML и не проверяются схемой. |
| Lax | 2 | Если найдено соответствующее схеме, элементы документа будут проверены. В противном случае ошибки не будут выдаваться. |
| Strict | 3 | Обработчик схемы должен найти схему, связанную с указанным пространством имён, чтобы проверить элементы документа. |

## См. также

* Namespace [System::Xml::Schema](../)
* Library [Aspose.PDF for C++](../../)
