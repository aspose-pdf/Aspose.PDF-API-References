---
title: "System::Xml::Schema::XmlSchemaSimpleTypeUnion класс"
linktitle: "XmlSchemaSimpleTypeUnion"
second_title: "Справочник API Aspose.PDF для C++"
description: "System::Xml::Schema::XmlSchemaSimpleTypeUnion класс. Представляет элемент union для простых типов из XML Schema, как указано World Wide Web Consortium (W3C). Тип данных union может использоваться для указания содержимого simpleType. Значение элемента simpleType должно быть одним из набора альтернативных типов данных, указанных в union. Типы union всегда являются производными типами и должны включать как минимум два альтернативных типа данных в C++."
type: docs
weight: 6600
url: /ru/cpp/system.xml.schema/xmlschemasimpletypeunion/
---
## XmlSchemaSimpleTypeUnion class


Представляет элемент **union** для простых типов из XML [Schema](../) согласно World Wide [Web](../../system.web/) Consortium (W3C). Тип данных **union** может использоваться для указания содержимого **simpleType**. Значение элемента **simpleType** должно быть одним из набора альтернативных типов данных, указанных в union. Типы union всегда являются производными типами и должны включать как минимум два альтернативных типа данных.

```cpp
class XmlSchemaSimpleTypeUnion : public System::Xml::Schema::XmlSchemaSimpleTypeContent
```

## Методы

| Метод | Описание |
| --- | --- |
| [get_BaseMemberTypes](./get_basemembertypes/)() | Возвращает массив объектов [XmlSchemaSimpleType](../xmlschemasimpletype/), представляющих тип элемента **simpleType**, основанный на значениях [XmlSchemaSimpleTypeUnion::get_BaseTypes](./get_basetypes/) и [XmlSchemaSimpleTypeUnion::get_MemberTypes](./get_membertypes/) простого типа. |
| [get_BaseTypes](./get_basetypes/)() | Возвращает коллекцию базовых типов. |
| [get_MemberTypes](./get_membertypes/)() | Возвращает массив квалифицированных имён членов встроенных типов данных или элементов **simpleType**, определённых в этой схеме (или в другой схеме, указанной заданным пространством имён). |
| [set_MemberTypes](./set_membertypes/)(const ArrayPtr\<SharedPtr\<XmlQualifiedName\>\>\&) | Устанавливает массив квалифицированных имён членов встроенных типов данных или элементов **simpleType**, определённых в этой схеме (или в другой схеме, указанной заданным пространством имён). |
| [XmlSchemaSimpleTypeUnion](./xmlschemasimpletypeunion/)() | Инициализирует новый экземпляр класса [XmlSchemaSimpleTypeUnion](./). |
## Typedefs

| Типовое определение | Описание |
| --- | --- |
| [Ptr](./ptr/) | Псевдоним для shared pointer к экземпляру этого класса. |
## Примечания



Объекты этого класса должны выделяться только с помощью функции [System::MakeObject()](../../system/makeobject/). Никогда не создавайте экземпляры этого типа в стеке или с помощью оператора new, так как это приведёт к ошибкам выполнения и/или сбоям утверждений. Всегда оборачивайте этот класс в указатель [System::SmartPtr](../../system/smartptr/) и используйте этот указатель для передачи его в функции в качестве аргумента.

## См. также

* Class [XmlSchemaSimpleTypeContent](../xmlschemasimpletypecontent/)
* Namespace [System::Xml::Schema](../)
* Library [Aspose.PDF for C++](../../)
