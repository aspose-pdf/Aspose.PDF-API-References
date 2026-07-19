---
title: "System::Xml::Schema::XmlSchemaDerivationMethod enum"
linktitle: "XmlSchemaDerivationMethod"
second_title: "Справочник API Aspose.PDF для C++"
description: "System::Xml::Schema::XmlSchemaDerivationMethod enum. Предоставляет различные методы предотвращения наследования в C++."
type: docs
weight: 7600
url: /ru/cpp/system.xml.schema/xmlschemaderivationmethod/
---
## XmlSchemaDerivationMethod enum


Предоставляет различные методы предотвращения производных типов.

```cpp
enum class XmlSchemaDerivationMethod
```

### Значения

| Имя | Значение | Описание |
| --- | --- | --- |
| Empty | 0 | Переопределить метод наследования по умолчанию, чтобы разрешить любое наследование. |
| Substitution | 1 | Относится к наследованиям через **Substitution**. |
| Extension | 2 | Относится к наследованиям через **Extension**. |
| Restriction | 4 | Относится к наследованиям через **Restriction**. |
| List | 8 | Относится к наследованиям через **List**. |
| Объединение | 16 | Относится к наследованиям через **Union**. |
| Все | 255 | **#all**. Относится ко всем методам наследования. |
| None | 256 | Принимает метод наследования по умолчанию. |

## См. также

* Namespace [System::Xml::Schema](../)
* Library [Aspose.PDF for C++](../../)
