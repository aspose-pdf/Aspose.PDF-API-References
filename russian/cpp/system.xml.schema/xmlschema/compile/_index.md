---
title: "Метод System::Xml::Schema::XmlSchema::Compile"
linktitle: "Compile"
second_title: "Справочник API Aspose.PDF для C++"
description: "Метод System::Xml::Schema::XmlSchema::Compile. Компилирует XML SchemaObject Model (SOM) в информацию схемы для проверки. Используется для проверки синтаксической и семантической структуры программно построенного SOM. Семантическая проверка выполняется во время компиляции в C++."
type: docs
weight: 200
url: /ru/cpp/system.xml.schema/xmlschema/compile/
---
## XmlSchema::Compile(ValidationEventHandler) method


Компилирует XML [Schema](../../)[Object](../../../system/object/) Model (SOM) в информацию схемы для проверки. Используется для проверки синтаксической и семантической структуры программно построенного SOM. Семантическая проверка выполняется во время компиляции.

```cpp
void System::Xml::Schema::XmlSchema::Compile(ValidationEventHandler validationEventHandler)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| validationEventHandler | ValidationEventHandler | Обработчик события проверки, получающий информацию об ошибках проверки XML [Schema](../../). |

## См. также

* Typedef [ValidationEventHandler](../../validationeventhandler/)
* Class [XmlSchema](../)
* Namespace [System::Xml::Schema](../../)
* Library [Aspose.PDF for C++](../../../)
## XmlSchema::Compile(ValidationEventHandler, const SharedPtr\<XmlResolver\>\&) method


Компилирует XML [Schema](../../)[Object](../../../system/object/) Model (SOM) в информацию схемы для проверки. Используется для проверки синтаксической и семантической структуры программно построенного SOM. Семантическая проверка выполняется во время компиляции.

```cpp
void System::Xml::Schema::XmlSchema::Compile(ValidationEventHandler validationEventHandler, const SharedPtr<XmlResolver> &resolver)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| validationEventHandler | ValidationEventHandler | Обработчик события проверки, получающий информацию об ошибках проверки XML [Schema](../../). |
| resolver | const SharedPtr\<XmlResolver\>\& | Класс [XmlResolver](../../../system.xml/xmlresolver/), используемый для разрешения пространств имён, указанных в элементах **include** и **import**. |

## См. также

* Typedef [ValidationEventHandler](../../validationeventhandler/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [XmlResolver](../../../system.xml/xmlresolver/)
* Class [XmlSchema](../)
* Namespace [System::Xml::Schema](../../)
* Library [Aspose.PDF for C++](../../../)
