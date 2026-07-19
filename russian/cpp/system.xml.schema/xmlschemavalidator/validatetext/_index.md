---
title: "Метод System::Xml::Schema::XmlSchemaValidator::ValidateText"
linktitle: "ValidateText"
second_title: "Справочник API Aspose.PDF для C++"
description: "Метод System::Xml::Schema::XmlSchemaValidator::ValidateText. Проверяет, разрешена ли указанная строка текста в контексте текущего элемента, и собирает текст для проверки, если текущий элемент имеет простой контент, в C++."
type: docs
weight: 2000
url: /ru/cpp/system.xml.schema/xmlschemavalidator/validatetext/
---
## XmlSchemaValidator::ValidateText(const String\&) method


Проверяет, разрешена ли указанная текстовая **string** в контексте текущего элемента, и собирает текст для проверки, если текущий элемент имеет простое содержимое.

```cpp
void System::Xml::Schema::XmlSchemaValidator::ValidateText(const String &elementValue)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| elementValue | const String\& | Текстовая **string** для проверки в контексте текущего элемента. |

## См. также

* Class [String](../../../system/string/)
* Class [XmlSchemaValidator](../)
* Namespace [System::Xml::Schema](../../)
* Library [Aspose.PDF for C++](../../../)
## XmlSchemaValidator::ValidateText(XmlValueGetter) method


Проверяет, разрешён ли текст, возвращаемый указанным объектом [XmlValueGetter](../../xmlvaluegetter/), в контексте текущего элемента, и собирает текст для проверки, если текущий элемент имеет простой контент.

```cpp
void System::Xml::Schema::XmlSchemaValidator::ValidateText(XmlValueGetter elementValue)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| elementValue | XmlValueGetter | Обратный вызов [XmlValueGetter](../../xmlvaluegetter/), используемый для передачи текстового значения в виде типа, совместимого с типом XML [Schema](../../) Definition Language (XSD) атрибута. |

## См. также

* Typedef [XmlValueGetter](../../xmlvaluegetter/)
* Class [XmlSchemaValidator](../)
* Namespace [System::Xml::Schema](../../)
* Library [Aspose.PDF for C++](../../../)
