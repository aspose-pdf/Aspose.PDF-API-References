---
title: "Класс System::Xml::Schema::XmlSchemaObjectTable"
linktitle: "XmlSchemaObjectTable"
second_title: "Справочник API Aspose.PDF для C++"
description: "Класс System::Xml::Schema::XmlSchemaObjectTable. Предоставляет коллекции содержащихся элементов в классе XmlSchema (например, Attributes, AttributeGroups, Elements и т.д.) на C++."
type: docs
weight: 5300
url: /ru/cpp/system.xml.schema/xmlschemaobjecttable/
---
## XmlSchemaObjectTable class


Предоставляет коллекции содержащихся элементов в классе [XmlSchema](../xmlschema/) (например, Attributes, AttributeGroups, Elements и т.д.).

```cpp
class XmlSchemaObjectTable : public System::Collections::Generic::IEnumerable<System::Collections::Generic::KeyValuePair<SharedPtr<System::Xml::XmlQualifiedName>, SharedPtr<System::Xml::Schema::XmlSchemaObject>>>
```

## Методы

| Метод | Описание |
| --- | --- |
| [Contains](./contains/)(const SharedPtr\<XmlQualifiedName\>\&) | Определяет, существует ли указанное квалифицированное имя в коллекции. |
| [get_Count](./get_count/)() | Возвращает количество элементов, содержащихся в [XmlSchemaObjectTable](./). |
| [get_Names](./get_names/)() | Возвращает коллекцию всех именованных элементов в [XmlSchemaObjectTable](./). |
| [get_Values](./get_values/)() | Возвращает коллекцию всех значений для всех элементов в [XmlSchemaObjectTable](./). |
| [GetEnumerator](./getenumerator/)() override | Возвращает перечислитель, который может проходить по [XmlSchemaObjectTable](./). |
| [idx_get](./idx_get/)(const SharedPtr\<XmlQualifiedName\>\&) | Возвращает элемент в [XmlSchemaObjectTable](./), указанный квалифицированным именем. |
## Typedefs

| Типовое определение | Описание |
| --- | --- |
| [Ptr](./ptr/) | Псевдоним для shared pointer к экземпляру этого класса. |
## Примечания



Объекты этого класса должны выделяться только с помощью функции [System::MakeObject()](../../system/makeobject/). Никогда не создавайте экземпляры этого типа в стеке или с помощью оператора new, так как это приведёт к ошибкам выполнения и/или сбоям утверждений. Всегда оборачивайте этот класс в указатель [System::SmartPtr](../../system/smartptr/) и используйте этот указатель для передачи его в функции в качестве аргумента.

## См. также

* Class [IEnumerable](../../system.collections.generic/ienumerable/)
* Namespace [System::Xml::Schema](../)
* Library [Aspose.PDF for C++](../../)
